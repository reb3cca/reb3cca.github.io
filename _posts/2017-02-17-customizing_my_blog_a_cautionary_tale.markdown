---
layout: post
title:  "Customizing My Blog: A cautionary tale."
date:   2017-02-17 17:34:23 +0000
---


I started with the Intro to Ruby before enrolling, so I finished that track before starting with HTML and CSS. I was not looking forward to starting that section. I felt like anyone who used computers in the ‘90s knew enough HTML and CSS to function but I was afraid of losing momentum on Ruby while on a remedial detour. 

With my nerd-ego pouting in my head, I pushed on to the new track and found plenty of new information. HTML5 and some great changes that were more intuitive. I got to use Twitter Bootstrap for the first time. Best of all, I got tons of practice with Git. The lessons flew by and I enjoyed the voice keeping me company on the code-alongs. 

Still, I couldn’t wait to get back to Ruby. When I missed thinking through methods, I would look through the questions to see if I could help people with the Tic Tac Toe sections. But the rush from solving a problem brought a slight twinge of jealousy that they were going to do more Ruby while I had to go back to CSS.

Then I finished the last code along and I was back! I flew through a bunch of lessons in Ruby, but…

But I felt like I didn’t get closure. Maybe it was my nerd-ego again wanting to show off my new skills, but I learned all of this great stuff and wanted to use it right away. I decided to experiment on myself—or rather on my Learn.co blog. I wanted to see if I could make something that would 1) make a good first impression and 2) display my portfolio as I progressed in my studies. As an added bonus, I would get to write a “how to” blog post so I didn't have to think of another topic. 

Checking the [FAQ’s on Learn.co](https://help.learn.co/hc/en-us/articles/115001352508-Can-I-edit-the-CSS-of-my-blog-), I found we had a free rein as long as we avoided two files and a folder:
> You do have access to your blog's CSS on GitHub if you'd like to make changes. The only files that you should avoid modifying on your own is the `CNAME`, `_config`, and any of the blog posts files. Those are connected with Learn and the connection will break if you modify these files on Github.

I decided I wanted to use Twitter Bootstrap because it is already set up to be responsive, the grid makes it easy to think about layouts, and [GetBootstrap](http://getbootstrap.com) has so much code available for adding components. I found the free [New Age template](https://startbootstrap.com/template-overviews/new-age/) with The MIT License and decided it was a perfect jumping off point. It didn’t look anything like what I wanted but that is just cosmetic; it did offer the functionality I wanted and came with a whole file of device mockups. I downloaded it and started pulling the CSS apart, commenting out different lines of code or changing colors to neon green to see what code controlled what changes in the browser.

A few days later, my design was mostly the way I wanted it. There were some things that were placeholders to change when I have a few hours to kill in Photoshop, but this was a fantastic start. I went to my Github repository to look at the code for my blog and decide how to best integrate what I made. I opened the index.html page and… *What is this?!! *

No, no, no, no, no. It was infested with curly brackets and had a nasty outbreak of percentage symbols. *What even is this?!* Then came the realization that this must be Jekyll. I just worked for days only to get tripped up over Jekyll. 

The thought of the lost time made me nauseous. And there was still the ego component: I made a thing and I wanted to be able to show the thing. Knowing nothing about Jekyll, I jumped down the rabbit hole and started googling.

I found plenty of articles about Jekyll but all I really wanted was a single “this is how you convert it” post. That doesn’t exist, but I did find a [Jekyll version](https://jekynewage.github.io) of the template I used for my original base. I combed through the files, comparing how the Jekyll Bootstrap differed from the plain Bootstrap files. When I saw how they were organized, I could start pulling it apart, deleting what I didn’t need, putting my changes into the `.sass`, adding to the `_includes` and `_templates`. To preview it in the browser, I found out that I needed to install the[ Jekyll gems](https://jekyllrb.com/docs/quickstart/) and run `jekyll build` and `jekyll serve` from my terminal.

At this point, I feel like I need to reiterate that this is a cautionary tale. I don’t recommend this process. It was a valuable learning experience; learned a ridiculous amount by taking everything apart and trying to figure out how to get it all back together. But there were several times I almost threw it out and started over with simpler design in a simpler template. I spent days clawing my way back out of the rabbit hole.

If you are just starting or just want something you can upload and make a few cosmetic changes, find a [Jekyll Bootstrap theme](http://xdesigns.net/2016/04/jekyll-themes/) that’s most like what you want. If you want to understand Jekyll, if you want to know how it works, then maybe you can do what I did and find a template that has a non-Jekyll version you understand to compare to the new Jekyll version. Just know that it will be a really deep dive.

Right now, [my site](http://reb3cca.com) is at the “good enough to make live” stage. There are still a few things I didn’t perfect, but I have passed the point of diminishing returns. The biggest issue is that I am having trouble changing the header size on the blog side to be smaller without effecting the full cover of the header on the front page. I’ll mess with it more when I have spare time. I also want to make an image to overlay the header on the blog side, but that’s something I’ll make when I have an evening I want to kill in Photoshop. The last thing on my list is to make some more changes to the copy in the About section, but this is good enough for now.

My kids watched The Magic School Bus when they were smaller. The teacher on the show always tossed the class into situations to see what observations and solutions they found on their own. Her catchphrase is a motto in our house: *Take chances! Make mistakes! Get messy!* For the braver souls reading this, I hope my cautionary tale inspires you to jump into things you don’t know and trust you will learn enough to find your way back. But even if it just saves you a few missteps, then I’m glad to share this. 

Now if you haven’t already, click around and check out the thing I made! 


