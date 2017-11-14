---
layout: post
title:  "Customer Facing Problem"
date:   2017-11-13
categories: jekyll update
---

If a customer writes in saying their "site won't build", I would start from the basic top level and narrow specify my questions based on their answers. I would furst direct them to find their git repository from Netlify's 'Create a new site' page. Then from there, click on the link to see if their site is deployed.

If that doesn't work, I would check if they have a node package manager in order to install Netlify's cli (netfly-cli) locally or globally. Also, if the customer decided to use Ruby for their site generator, I would make sure to see if they added their site generator gem (ex: gem 'jekyll'). I would then try to run their site by entering 'netlify deploy' in order to check if their site is authorized or also by going onto the site's Netlify page to check for authorization as well. 