---
toc: true
layout: post
description: A minimal example of using markdown with fastpages.
categories: [markdown]
title: First Markdown Post 
---
# About me

## My Goals in APCSP

I took this class because I plan on majoring in computer science in college.  Ever since I was a little kid I was into computers and video games.  I realized that I was more advanced than most people in computers and how to navigate.  I want to learn about coding and python coding so I can take these skills further into college classes and my major.

## My background life

My name is Ethan Truong and I am 16 years old born on July 28th, 2006.  I live at home with my mom, dad, and my brother.  My brother is a freshman here at this school.  I grew up in the area of Linda Vista with my grandparents and eventually moved out to 4s Ranch.  I love to play basketball and video games on my freetime.  Video games I play include valorant and warzone.  Thanks for reading!

---

## Lists

Here's a list:

- item 1
- item 2

And a numbered list:

1. item 1
1. item 2

## Boxes and stuff

> This is a quotation

{% include alert.html text="You can include alert boxes" %}

...and...

{% include info.html text="You can include info boxes" %}

## Images

![]({{ site.baseurl }}/images/logo.png "fast.ai's logo")

## Code

You can format text and code per usual 

General preformatted text:

    # Do a thing
    do_thing()

Python code and output:

```python
# Prints '2'
print(1+1)
```

    2

Formatting text as shell commands:

```shell
echo "hello world"
./some_script.sh --option "value"
wget https://example.com/cat_photo1.png
```

Formatting text as YAML:

```yaml
key: value
- another_key: "another value"
```


## Tables

| Column 1 | Column 2 |
|-|-|
| A thing | Another thing |


## Tweetcards

{% twitter https://twitter.com/jakevdp/status/1204765621767901185?s=20 %}


## Footnotes



[^1]: This is the footnote.

