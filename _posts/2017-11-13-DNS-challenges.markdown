---
layout: post
title:  "DNS challenges"
date:   2017-11-13
categories: jekyll update
---

These are the two common DNS challenges most non-technical will face:

Setting Up Custom Nameservers:
Its important that users set up their custom domain name using 'www.theirsite.com' instead of 'theirsite.com'. This is because if you have both nameservers pointing to the same IP as your domain, the user will need to make sure the server IP address has its own DNS server. And if the nameserver does not provide a DNS, it's recommended that the nameserver use separate servers. 

Learn How to Move Hosts: 
Setup the new site account and alter the local DNS settings in order for the new site to be used. This allows the user to see the new site even though the older site is launched on the web. After, set up the new server and change the nameservers after deleting the previous account. 
