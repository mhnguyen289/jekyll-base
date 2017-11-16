---
layout: post
title:  "Customer Facing Problem"
date:   2017-11-13
categories: jekyll update
---

If a customer writes in saying their "site won't build", I would start from the basic top level and narrow specify my questions based on their answers. I would first direct them to find their git repository from Netlify's 'Create a new site' page. Then from there, click on the link to see if their site is deployed.

If the customer site's still doesn't deploy, then I would check if they have node package manager in order to install Netlify's cli (netfly-cli). Also, if the customer decided to use Ruby for their site generator, I would make sure to see if they added their site generator gem (ex: gem 'jekyll'). Then try to run their site by entering 'netlify deploy' in order to check if their site is authorized or also by going onto the site's Netlify page in order to check for authorization as well. 