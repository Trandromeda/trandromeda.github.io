---
layout: post
title: "Breaking Down Code"
date: 2016-10-17
categories:
  - Learning
description: 
image: https://unsplash.it/2000/1200?image=937
image-sm: https://unsplash.it/500/300?image=937
---

The most rewarding part of my job as a coding bootcamp TA is helping ordinary people who've never seen a line of code before understand things like *loops*, *classes* and *ORMs*.

Maybe it's because I was also a bootcamp grad, but I lean towards very descriptive, visual and elementary explanations when it comes to breaking down programming concepts. For instance, my favourite way to help people understand (one of) the uses of `tux` in Sinatra is by getting them to think of it as a sandbox, while the database lives in another sort of 'black box'. It's too much of a hassle to work with the database box directly because you need to write clunky SQL queries - that's why we create models to represent the tables in the database. When you want to interact with the database, whether it's reading data, updating data or deleting data, you just type in the name of the model (that corresponds to its database table) with an upper case. Lower case names are for your local variables that exist only in that specific instance of tux. Tux is able to understand what you want and then communicates with the database box in order to return your data back to you. It's both the liaison for your data and a workbench for you to play around with.

"Boxes" are featured prominently in code: a class is defined inside a box, functions are inside boxes, files live in boxes. I encourage students to visualize these imaginary boxes in order to see how their code is organized - a huge part of coding isn't just the act of typing it out, but putting it in the right place. I find boxes easier to explain with than blocks, as they have a more physical, and thus visual, connotation to them. You'll quickly realize that the idea of a beginning of a method and the end of a method isn't intuitive to everyone, along with other daily things that working developers take for granted.

Some students benefit from a very basic sticks-and-stones explanation when it comes to code, while others who have grasped the fundamentals only need to have a few misconceptions cleared way for them. It is almost always the former group that's more challenging to teach, because many of the ideas you've gotten so used to must be re-visited and dissected in a human language-friendly way.

The reason I took up coding was to make things and solve problems. I just want to know how something works and a little bit about why it works that way, and how technology can fit into the bigger picture. This probably comes out in my style of teaching, as I try to avoid fluff as much as possible. Most of these students aren't here because they want to get into computer science. They're here with a purpose, and code is just a tool to achieve that purpose. 