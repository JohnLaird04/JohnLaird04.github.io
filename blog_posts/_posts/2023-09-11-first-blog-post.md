---
layout: post
date: 2023-09-16
title: My Website Is Finally Up and Running
categories: [Weekly Blogs]
description: >
  What I learned from building my first website.
sitemap: false
hide_last_modified: true
---
Here it is, my website. I hope you like it because the project
of building a website was truly a labor of love. I thought
this would be a project that would take a while but would 
be relatively straight forward. It was anything other than
that.

# Building a Website Using Ruby on Rails
When I first began I asked my brother about how he built
[his website](http://ianclaird.com) because I loved the design of his website
and was amazed at his ability to create such a stunning
website. When we were talking he told me how I could build 
a website that looked just as good as his using Jekyll.
However, when he was explaining Jekyll, the only thing I
remembered from the conversation was hearing "it is so
easy to build a website using Ruby on Rails!" I have no
idea where I got that idea because those words never came out
of his mouth. Anyway, I looked up some tutorials, and after
watching many of them, I began to understand a little of how it worked.
I made the most basic pages with functionality to move between
them, but that was it. However, I was so proud of what I had
built so far. So I texted my brother with my progress so far, and he asked me why I am not using jekyll and my response is
"What is that?" I looked it up, downloaded the files and a 
theme I liked from github and realized that jekyll is a 
way better way to build websites.

# Discovering Jekyll
The moment I ran *bundle exec jekyll serve* in 
terminal and my eyes gazed upon the beautiful website
before me, my eyes lit up and my joy shot out of my body; 
I had truly reached website utopia. I eagerly sat down, 
read through the documentation, and began to make my 
perfect website. With every *jekyll serve* command I ran
in terminal, the website I so desired was becoming more 
and more of a reality.

Then, disaster struck. I downloaded Git and learned how 
to add my code to my new website repository on GitHub.
It was all going relatively well; there were a few bumps 
in the road, but nothing too major. However, once all my
code was in the repository, I see a big red x appear next to my
latest commit information. As I hover my cursor over the 
symbol to figure out what the problem was, I had no idea 
the struggle that awaited me. A dropdown appeared saying that 
the website failed to deploy. As I dig deeper into the code,
it alerts me with the error *Warning:  github-pages can't satisfy 
your Gemfile's dependencies.* I sat there, late at night, and 
told myself I'll deal with it tomorrow. 

Well, I did work on resolving it the next day, but to no avail.
It was only after a week and over 20 hours of debugging that my 
issue would finally be resolved. I spent 4-5 hours a day for a solid few days 
trying to figure out this seemingly common issue. The 
problem was that any solution the internet provided only made
the problem worse and ruined my files. Then, after looking
at someone else's website code, I simply changed the 
theme settings and then everything worked. This, I learned,
is the life of a Software Engineer: spend many, many hours 
debugging code only to discover that one, tiny little 
error.

### Note: How I Fixed It
If anyone is experiencing the same issue, simply go to your 
Gemfile and change *gem "jekyll", "~> 4.1"* at the top to
*gem "github-pages", group: :jekyll_plugins.*

# What I Learned
1. I learned about Git and using it to push updated to my website
to my GitHub repository. Without this project, I would not have
been exposed to using Git or creating and using GitHub
repositories. 
2. My ability to read documentation improved dramatically
as I was constantly reading the Hydejack documentation to 
learn about how the theme worked and how I could add and 
edit new pages.
3. I was forced to learn how to debug code. I was wildly 
inefficient at debugging at first, but the more I did it,
the better I learned where to look for good information.
I still have a long way to go, but this project put 
me down the right path.
4. I enjoyed the entire process. Even though it may have
seemed like I hated what I was doing, I actually loved debugging
my code. It felt like solving a 2000-piece puzzle: it may
seem impossible to figure out where all the tiny pieces go,
but once you do, all the struggle was worth the reward.

