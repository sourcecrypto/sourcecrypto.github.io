---
layout: single
title: SourceCrypto Transcripts
description: "Making the occasional audio transcription for valuable crypto content."
header:
  image: /images/source-banner.png
  teaser: /images/source-crypto-transcripts.png
  og_image: /images/source-crypto-transcripts.png
permalink: /posts/transcripts/
redirect_from: /transcripts/
classes: wide

---

I've merged the transcripts into this site, proper. Now that I know how to use Minimal Mistakes Jekyll better, I can see how it makes more sense to have them in the same site setup.

{% for post in site.categories.Transcripts %}
  {% include archive-single.html %}
{% endfor %}
