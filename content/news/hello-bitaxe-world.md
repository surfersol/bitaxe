---
title: "Bitaxe - full open source ASIC bitcoin miner"
layout: default
description: "Welcome to hopefully a great extention of the bitaxe community, in this post i'll go over the long term plan for this repository and how you can contribute and make some sats in the process. This is currently still being worked out and only the content section is 95% ready, the shop still needs some extra functionality for it to work in a group."
featured: true
href: "/news/hello-bitaxe-world"
article: "Hello Bitaxe World"
imagelink: "/project/blog-img/hello-bitaxe-world.jpg"
date: "Feb 2, 2024"
datetime: "2024-02-01"
categorytitle: "Community Start"
authorname: "Sync"
authorrole: "Bitcoin Mass Adoption"
authorhref: "https://primal.net/p/npub1equrmqway3qxw3dkssymusxkwgwrqypfgeqx0lx9pgjam7gnj4ysaqhkj6"
authorimageUrl: "https://imgproxy.snort.social/2FreqBTxidEv-TqLfKLlE0YwMvnSJup_aA2pQv61r-k//aHR0cHM6Ly9wZnAubm9zdHIuYnVpbGQvNjM3MjIxYjQxZjIxZTZkNTEyNmNiNDRlNjE3MmNmODYwMGNiMWZjMTk1MzQ2MWRlMDNkODBjZTk4Mzg0NTk1My5naWY"

image:
  src: 'https://Bitaxe.com/project/blog-img/hello-bitaxe-world.jpg'
  alt: 'An image showcasing My Page.'
  width: 1200
  height: 630
head:
  meta:
    - name: 'keywords'
      content: 'bitaxe, miner, bitcoin'
    - name: 'robots'
      content: 'index, follow'
    - name: 'author'
      content: 'Bitaxe.com'
    - name: 'copyright'
      content: '© 2024 Bitaxe.com'

---

::ContainerProse 

# Bitaxe Community Website

## Introduction
Bitaxe is a fully open source hardware Bitcoin ASIC miner. Ultra is the 3rd major revision of the bitaxe that now includes the BM1366 ASIC from the S19XP. Skott's contribution to the world of Bitcoin mining with Bitaxe is not just a technological advancement but a step towards democratizing cryptocurrency mining, making it more accessible to a broader audience. 

Now a community of amazing contributors and hackers help build, educate and push forward the idea of bringing mining closer to the individual.

## Website
This repository is the first project to be build using the <a href="https://cypher.space" target="_blank"> Cypher Template </a>.
The idea to help combine content and POS in an open bitcoin community only way, contribute content and guides and recieve a donation to your LNURL, list your bitaxes for sale in the community store*. 

### How to Contribute News
Clone the file empty_news.md, fill in the front-matter with the required parameters and make sure to set draft to false , if you are not sure have a look at Initial-Setup.md as example, once you have this filled in next time you can copy 95% of this for your next guide. You will also need to add an image to the public > project > blog-img folder this is preferably a jpg, <1mb and with dimensions 1200 × 630px. You can provide your lightning address to recieve donations for your writing or leave it blank, that way if your post gets a donation it goes to the Open Source Miners Unite fund. Once you are happy with how your push your PR.
⚠️ Still in a bug in the custom donation widget <br>


### How to Contribute Guides

 <a href="/guides/initial-setup"> Example of a article with donation </a>

Clone the file empty_guide.md, fill in the front-matter with the required parameters and make sure to set draft to false , if you are not sure have a look at Initial-Setup.md as example, once you have this filled in next time you can copy 95% of this for your next guide. You will also need to add an image to the public > project > blog-img folder this is preferably a jpg, <1mb and with dimensions 1200 × 630px. You can provide your lightning address to recieve donations for your writing or leave it blank, that way if your post gets a donation it goes to the Open Source Miners Unite fund. Once you are happy with how your push your PR.
⚠️ Still in a bug in the custom donation widget <br>


### How to Translate
The project Supports Local & Global translations, for a community project global translations are easiest but horrible to maintain. You can find global site paramaters translations in the locales folder. If you want to translate an existing guide or news article that is also possible copy the file and place it in the matching languages folder under guides in the content directory. 

### How to Sell in the store *
⚠️ Still in development <br>
Currently the idea is that you can submit your products to the project.json with your LNURL and recieve the order details via webhook. The store is functional it just needs some adjustment to deal with a multi vendor setup & limitting of shipping regions.

### How to Contribute Code
TBA


::

