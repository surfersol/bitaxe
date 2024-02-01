---
title: "Bitaxe - full open source ASIC bitcoin miner"
layout: default
description: "We'll go over the basics around this website how it works and how you can contribute, let's build a decentralised commerce and documentation platform build around bitcoin only and value for value content."
featured: true
href: "/guides/initial-setup"
article: "Initial Website Setup"
imagelink: "/project/blog-img/first-setup.jpg"
date: "Feb 01, 2024"
datetime: "2024-02-01"
categorytitle: "Web Dev"
authorname: "Sync"
authorrole: "Bitcoin Mass Adoption"
authorhref: "https://primal.net/p/npub1equrmqway3qxw3dkssymusxkwgwrqypfgeqx0lx9pgjam7gnj4ysaqhkj6"
authorimageUrl: "https://imgproxy.snort.social/2FreqBTxidEv-TqLfKLlE0YwMvnSJup_aA2pQv61r-k//aHR0cHM6Ly9wZnAubm9zdHIuYnVpbGQvNjM3MjIxYjQxZjIxZTZkNTEyNmNiNDRlNjE3MmNmODYwMGNiMWZjMTk1MzQ2MWRlMDNkODBjZTk4Mzg0NTk1My5naWY"

image:
  src: 'https://Bitaxe.com/project/blog-img/first-setup.jpg'
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


::ContainerCustomlight{lnurl=cypherspace@getalby.com image="https://imgproxy.snort.social/2FreqBTxidEv-TqLfKLlE0YwMvnSJup_aA2pQv61r-k//aHR0cHM6Ly9wZnAubm9zdHIuYnVpbGQvNjM3MjIxYjQxZjIxZTZkNTEyNmNiNDRlNjE3MmNmODYwMGNiMWZjMTk1MzQ2MWRlMDNkODBjZTk4Mzg0NTk1My5naWY" }

# Website Guide

This guide helps you setup the website locally and hopes to answer questions on how the website opperates, grab a cup of coffee and sorry for spelling mistakes or weird phrasings, these drafts should get better with itteration. Let's Go ! 🚀<br>

The webtemplate is build on Nuxt3 an open source JavaScript framework that can be compared to React, Angular, Svelte,... you can find the repository on github.<br><br>

<a href="https://github.com/cypher-space/bitaxe" target="_blank"> Bitaxe.com Github Repo </a><br><br>

More detailed instructions of how to run a Nuxt Template on your pc:
<a href="https://cypher.space/setup" target="_blank"> Setup Instructions </a>

The repository builds to Cloud Flare Pages for the bitaxe.com domain, but can also be used on AWS, Google Cloud, Vercel, Github pages,... or self-hosted.

::

::ContainerProsefull

## Development

### Community content & products
The simpel idea behind it is the site does not take commision, community content contributions can be equiped with a donation button to the writer, there is also a credits page to just in generally thank contributors. Listing products also happens trough a pull request to the repo. If you feel like you want to be an admin over the repo shoot me a message on discord.
<br>

### Cypher Template
At the heart of the cypher template is the config folder, this is more ment to be a solo template aka you configure it with your LNURL, Bitcoinadress, alby (read only token if you want ) and you are ready to start selling. For the community build these setting will point to the OSMU LNURL and bcaddress. you can find this file here :

<a href="https://github.com/cypher-space/bitaxe/tree/main/config" target="_blank">Setup.json </a>


### Custodial Painpoints.
Normally like mentioned this template is for individual usage, for listing products in this bitaxe community build a unique vendor ID and LNURL are added to a product. I was hoping to setup a way to wrap invoices or prism so sales from the shop donate a percentage to skott or OSMU for creating and fostering this project in the first place.
<br><br>
In search of finding a way to have a transparant single sales point the only non-custodial implementation in the project is the invoicing, i haven't found a way that reliably works just yet, but the hunt is still on !

::