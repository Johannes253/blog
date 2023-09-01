---
layout: post
title: "Introduction Post"
author: Johannes Mayrhofer
---

I pretty much followed the instructions on the [Database-Websystems-Website](https://hendrix-cs.github.io/csci340/labs/jekyll.html), i have forked and cloned a repository before, so that went smoothly aswell. Since my notebook runs Windows 11 i just used the installer, which went through find, but the first hickup came when i haid to check the version with "ruby --version" which didn't work. If i searched for ruby in the search bar it showed up so i knew it was installed. To fix this error i had to go to the directory it was installed (in the Shell) and write ./ruby --version. This is a reacurring theme, whenever i need to type a command, i need to type ./ infront of it. Again with "./gem install bundler" it installed it correctly, but i still could not start it, so i found a helpfull article on [Stackoverflow](https://stackoverflow.com/questions/72424191/installing-and-running-jekyll-on-windows-10)  where it mentioned i needed to do it the following way:
1. ./bundle init
2. ./bundle add jekyll
3. ./bundle install
4. ./gem install jekyll bundler
5. ./bundle exec ./jekyll serve
After this sequence it finally worked. 

After i pushed my changes of step 5, my github site wouldn't correctly display the changes i have made, but i figured it out through an email github sent me, that there was a problem building the site. I tried linking to hendrix.edu site. 

Right now i am in step 6 and i am trying to write this blog which is hard, because i am not much of a writer.

In conclusion i really enjoyed this exercise because it revived my knowledge of the windows operating system and the inner workings of github. 
