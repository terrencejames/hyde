---
layout: post
title: Obligatory First Post
permalink: /s/firstpost
category: cs
---
What's up friends,

The site should finally now be live! A little bit of info about how the site is run:

* It's hosted on [GitHub Pages](https://pages.github.com/), s/o to their free hosting and repository integration
* The domain name is hosted from [Namecheap](http://www.namecheap.com). Also s/o to them for my free domain name for one year (you can probably notice a pattern going on here).
* The site and its pages are generated using [Jekyll](https://jekyllrb.com/), which (surprise surprise) is also free. It was the first time I had to set up a Ruby environment, and I got to say everything's pretty slick. Definitely will need to add more exploration onto my to-do list.

Although everything was relatively easy to set up, I also ran into a lot of troubles, particularly pertaining to that snazzy "/s/" in my URL name (because terrenceja.me would pretty much be lame and make no sense):

* Finding and installing a theme outside of the GitHub Pages supported ones was difficult; a lot of compatibility issues definitely needed to be resolved especially since some of these themes are built using Jekyll 2.0 instead of Jekyll 3.0.
* I probably spent a couple days trying to make that "/s" redirect correctly, playing with everything from the config.yml file to the directory locations of my files. A common issue would be that the CSS wouldn't be referenced correctly, and I ended up making a really hacky but terrible practice solution by hardcoding "/s" onto the HTML file references. This was before I realized/forgot I could check the Chrome Developer Console to check the error messages (oops). I definitely was way too excited to get this junk live so I settled for the fix, but I probably should fix it properly in the future.

Anyway, I hope you enjoy my extraordinarly basic site. Thanks and let me know if you have any questions or concerns!