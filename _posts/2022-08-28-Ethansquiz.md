---
toc: true
layout: post
description: Liav's Python Quiz questions
categories: [markdown]
title: Python Quiz
---
## Python Quiz:

import getpass, sys

def question_with_response(prompt):
    print("Question: " + prompt)
    msg = input()
    return msg

questions = 3
correct = 0

print('Hello, ' + getpass.getuser() + " running " + sys.executable)
print("You will be asked " + str(questions) + " questions.")
question_and_answer("Are you excited and ready to take this quiz?")

rsp = question_with_response("What command is used to verify that you installed a tool?")
if rsp == "-version":
    print(rsp + " is correct!")
    correct += 1
else:
    print(rsp + " is incorrect!")

rsp = question_with_response("How can you verify the packages and versions of tools you've installed with Anaconda?")
if rsp == "conda list":
    print(rsp + " is correct!")
    correct += 1
else:
    print(rsp + " is incorrect!")

rsp = question_with_response("What is the code editor we use in class called?")
if rsp == "VSCode":
    print(rsp + " is correct!")
    correct += 1
else:
    print(rsp + " is incorrect!")

print(getpass.getuser() + " you scored " + str(correct) +"/" + str(questions))

def question_and_answer():
    print("Question: " + prompt)
    msg = input()
    print("Infinitely knowledgable: " + msg)
