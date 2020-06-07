---
layout: single
title: "A growing assortment of knowledge related to the history of Bitcoin."
header: 
  image: "/images/bitcoin-history/pre-history.jpeg"
  caption: "[credits to @btcmrkts and @AnselLindner IIRC](https://twitter.com/weedcoder/status/1154808916792020992?s=20)"
share: true


intro:
  - image_path: "https://sourcecrypto.pub/images/thecryptoconomy-podcast_guy-swann.png"
    alt: "Down the @TheCryptoconomy Rabbithole"
    title: "Guy Swan - @TheCryptoconomy Essential Episods"
    excerpt: "Audio for Hundreds of Essential Bitcoin Articles. @TheCryptoconomy - Guy Swan..... These Podcasts are essential. So I made an index of them, organized by topic."
    url: "https://sourcecrypto.pub/blog/thecryptoconomy-podcast-deep-dive/"
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row:
  - image_path: "https://decentralized-id.com/images/history-user-centric-data-identity.png"
    alt: "napsterization.org - Who Stewards the Personal Data Question? Org Chart"
    title: "History Surrounding Self-Sovereign, Decentralized, Identity."
    excerpt: "Starting with David Chaum in the 80s, PGP, the International Planetwork Conference, Agenda for Sustainable Development, GDPR, and Bitcoin to the Present."
    url: "http://decentralized-id.com/identity-github/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: "https://web-work.tools/images/pgp-og.png"
    alt: "cypherpunk essentials"
    title: "Using PGP, Escrow, and Cryptocurrency Keysignatures"
    excerpt: "Asymmetric Encryption: Phil Zimmerman, PGP, Bitcoin and Ethereum key-signatures, Escrow, SSL, Various Apps and Resourses."
    url: "https://web-work.tools/practical-public-key-crypto/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: "https://learncryptotrading.co/assets/img/pinescript-thumb.png"
    alt: "learn pinescript tradingview"
    title: "Learn Pinescript-Tradingview."
    excerpt: "Resources for learning to trade with Tradingview's Pine Script."
    url: "/pinescript/"
    btn_label: "Read More"
    btn_class: "btn--primary"
classes: wide
toc: false
permalink: '/posts/history/'
redirect_from:
  - "/history/"
  - /bitcoin-history/
canonical_url: "https://sourcecrypto.pub/categories/#history"
---
<!--
  image: "https://sourcecrypto.pub/images/bitcoin-history/satoshi.gif"
  image_description: No one knows who Satoshi really is, but these words speak for themselves. This decentralized portrait creates an image and type portrait out of abstract section from the Bitcoin whitepaper. This is a one-of-a-kind variant that was created while making the offical video portrait that is part of the [*Decentral Eyes portrait series*](https://superrare.co/artwork/satoshi-nakamoto---decentral-eyes---variant-02-1410).
  caption: "[Satoshi Nakamoto - Decentral Eyes - Variant 02](https://superrare.co/artwork/satoshi-nakamoto---decentral-eyes---variant-02-1410), by [coldie3d](http://www.coldie3d.com/)"
-->

This is all getting some serious re-vamping in the coming months.

<img src="https://sourcecrypto.pub/images/bitcoin-history/BitcoinHistory.png"/>

{% include feature_row id="intro" type="center" %}

<h2>History related to Bitcoin</h2>

{% for post in site.categories.History %}
  {% include archive-single.html %}
{% endfor %}

<h2>Featured Content</h2>

{% include feature_row id="feature_row" %}


