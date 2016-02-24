---
layout: post
title: "Arrays Vs Hashes"
date: 2016-02-18 16:42:24
comments: true
description: ""
keywords: ""
categories:
- welcome
tags:
- welcome
---

Blog Post Day 2.  Today, we will be discussing the difference between hashes and arrays.  

	Arrays:  You can think if an array as a list of some sort.  It is simply a collection of data.  Although the order of said data is arbitrary, it must be known in order to reference it later.  For example, if I had an array for different color options that looked something like this: color_array = [“red”, “blue”, “green”], and I wanted to reference the color red, I would need to know where it lies in the array.  I would have to reference it by typing “color_array[0]”, because red is the first option in the array.  If you wanted green, all you would have to do is enter “color_array[2]”, and there you go.  But remember, the first value in an array is 0, not one.  So although red is technically the first color in the array, it’s reference value is 0.

	A hash, on the other hand, is a bit different.  Instead of being a simple collection of data, a hash is a collection of pairs of information.  Each pair contains a name and a value.  The “name” is also known as they key, and said key must not be the same as others, it has to be unique.  A typical hash for colors could look like “color_hash: { “red => “light”, “blue” => “navy”, “green” => “dark” }.  So when I do “color_hash [“blue”], I get the word “navy”, so that I know what specific shade of blew I want.  However, the most important part of a hash isn’t necessarily the order of the information given, instead it is what each thing is paired with.  For example, if “red” was paired with “navy”, instead of “light”, you wouldn’t know the specifications of the color red because it would be wrong.  




https://www.codecademy.com/forum_questions/52a69117282ae3085d000d63
http://www.linuxtopia.org/online_books/programming_books/ruby_tutorial/Ruby.new_Arrays_and_Hashes.html
https://launchschool.com/books/ruby/read/hashes
http://www.xyzpub.com/en/ruby-on-rails/3.2/ruby-array-und-hash.html

