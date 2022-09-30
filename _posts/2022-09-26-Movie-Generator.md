---
toc: true
layout: post
description: This will generate random movies 
title: Movie Data Generator
categories: [markdown, csp]
permalink: /moviegeneratordata/
---
# Movie Generator
- This is a button that will randomly generate a movie name 

<button id="1">Click Me!</button>
<p id="random"></p>

<script> 
var players = ["End Game" , "The Conjurinng", "The Avengers", "Thor", "Superman", "Iron Man", "Ant Man", "Insidious", "Green Lantern"]

var button = document.getElementById("1")
        var random2 = document.getElementById("random")
        button.onclick=function() {
            let random = players[Math.floor(Math.random()*players.length)];
            random2.innerHTML = random
        }
</script>

Using Javascript, you have to insert in the variables that you want to be included into your random generator. 
In my case, my variables were a bunch of movies that I decided to use in my project!


![image](https://user-images.githubusercontent.com/111910633/193318415-1a770cec-cd19-4261-a297-9e49c54f81b3.png)

