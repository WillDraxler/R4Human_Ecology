---
date: "2016-04-27T00:00:00Z"
external_link: ""
image:
  caption: Photo by me
  focal_point: Smart
summary: Building an automated line break addition system with Stringr
tags:
title: Line Breaks with Stringr
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
---

This project was an addition to a personal project that I started before the start of the term. I felt as though it would be a fun technical challenge to get back into the rhythm of coding.

Purpose:
This goal developed out of work with the image_annotat() function in the magick package. When inputting strings of text to be added, the text would run off of the image if it was too long. I devised a plan to automatically generate line breaks by editing the string with the inclusion of the newline sequence "`\n`".

I wanted to specify the width of a string before a new line break, and have the function cut it up into chunks of that length, then reassemble it with the newline sequence in between. The obvious problem was that I didn't want to cut the middle of words, so came up with a plan complicated enough that I felt the need to design a flowchart.

Once I had that written out, I simply started converting that idea into R code.