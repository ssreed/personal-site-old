---
layout: post
title: "Easy Blogging with GitHub"
description: ""
category: 
tags: [blogging, rails, jekyll]
---
{% include JB/setup %}

I've had this 'blog' for a while now and never truly sad down to write down how this came about. I don't intend on going into the reasoning of my decision to start this blog/site but I want to walk through what it takes to build a simple site through [GitHub](pages.github.com). 

During my job hunting period I've had more time on my hands, in that time I decided to work on more improving not only my writing ability but also my programming ability. [Jekyll](http://jekyllrb.com/), along with [GitHub](pages.github.com), made that possible. [Jekyll](http://jekyllrb.com/) is, to put it simply, a parsing engine used to build website through the utilization of templates, markdown and other cool techniques. What makes [Jekyll](http://jekyllrb.com/) really interesting is the fact that posting is extremely easy, especially if you're familiar with git. First you create a post via `rake post title='My Blog Post'` and rake will automagically create a markdown file for you. Then using either VI, nano or your favorite text editor you can open up the newly generated file and post away. There are many settings that you can tweak such as title, description, category and even tags. After you are done with your post, with a simple `git push` you will have created a new post for your [GitHub](pages.github.com) hosted static website. This blogging framework couldn't be easier to use and it comes with many powerful features. As I learn them little by little I hope I can post about them in more detail.