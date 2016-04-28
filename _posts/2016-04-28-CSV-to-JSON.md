---
layout: post
title:  "Converting a CSV file to JSON"
date:   2016-04-28 18:34:55
categories: tablereader
authour: Brian Edmond
image: 
---

Lately I've been experimenting with a method for converting a CSV file to JSON so that I can display the CSV information in a client browser. I have a friend that would like to be able track inventory, checked in and out, that is currently shared via an emailed Excel file. Ugh. The development name is tablereader and you can check out the github repository here: [tablereader][tablereader].

My concept covers something like a CSV file uploaded to Amazon S3. On upload click the file is also parsed to JSON and displayed, or refreshed, in the client's browser. The task exceeds my current knowledge base, but like all things development, it's just another opportunity to learn. I've also considered storing the parsed JSON to a Firebase account to allow the client to make updates of their own rather than the potentially confusing CSV parse to S3. That's closer to familiar territory though I'm still wrapping my brain around the CSV parse to JSON and into a form the Firebase will digest.

Onward!

[tablereader]: https://github.com/bedmond/tablereader