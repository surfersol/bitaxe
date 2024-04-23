# Bitaxe.com Website
## ##
![Licence](https://img.shields.io/github/license/cypher-space/V0.9-Beta) ![Issues](https://img.shields.io/github/issues/cypher-space/V0.9-Beta) 

<a href="https://demo.Bitaxe.com" target="_blank">
Live Build Preview
</a>

## Introduction
Bitaxe is a fully open source hardware Bitcoin ASIC miner. Ultra is the 3rd major revision of the bitaxe that now includes the BM1366 ASIC from the S19XP. Skott's contribution to the world of Bitcoin mining with Bitaxe is not just a technological advancement but a step towards democratizing cryptocurrency mining, making it more accessible to a broader audience. 

Now a community of amazing contributors and hackers help build, educate and push forward the idea of bringing mining closer to the individual.

## Website
This repository is the first project to be build using the <a href="https://cypher.space" target="_blank"> Cypher Template </a>.
The idea to help combine content and POS in an open bitcoin community only way, contribute content and guides and recieve a donation to your LNURL, list your bitaxes for sale in the community store*. 

### How to Contribute News
Clone the file empty_news.md, fill in the front-matter with the required parameters and make sure to set draft to false , if you are not sure have a look at Initial-Setup.md as example, once you have this filled in next time you can copy 95% of this for your next guide. You will also need to add an image to the public > project > blog-img folder this is preferably a jpg, <1mb and with dimensions 1200 × 630px. You can provide your lightning address to recieve donations for your writing or leave it blank, that way if your post gets a donation it goes to the Open Source Miners Unite fund. Once you are happy with how your push your PR.

### How to Contribute Guides
Clone the file empty_guide.md, fill in the front-matter with the required parameters and make sure to set draft to false , if you are not sure have a look at Initial-Setup.md as example, once you have this filled in next time you can copy 95% of this for your next guide. You will also need to add an image to the public > project > blog-img folder this is preferably a jpg, <1mb and with dimensions 1200 × 630px. You can provide your lightning address to recieve donations for your writing or leave it blank, that way if your post gets a donation it goes to the Open Source Miners Unite fund. Once you are happy with how your push your PR.

### How to Translate
The project Supports Local & Global translations, for a community project global translations are easiest but horrible to maintain. You can find global site paramaters translations in the locales folder. If you want to translate an existing guide or news article that is also possible copy the file and place it in the matching languages folder under guides in the content directory. 

### How to Sell in the store *
⚠️ Still in development <br>
Currently the idea is that you can submit your products to the project.json with your LNURL and recieve the order details via webhook. The store is functional it just needs some adjustment to deal with a multi vendor setup & limitting of shipping regions.

### How to Contribute Code
TBA

## Build Local Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# generate build to the /dist or .output folder
$ npm run build


```