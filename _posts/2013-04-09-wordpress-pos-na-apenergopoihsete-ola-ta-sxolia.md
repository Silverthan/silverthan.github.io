---
id: 509
title: 'WordPress: Πως να απενεργοποιήσετε όλα τα σχόλια'
date: 2013-04-09T06:19:34+00:00
author: Thanos
layout: post
guid: http://blog.silverthan.gr/?p=509
permalink: /wordpress-pos-na-apenergopoihsete-ola-ta-sxolia/
wpzoom_post_title:
  - 'Yes'
wpzoom_post_readmore:
  - 'Yes'
wpzoom_post_url:
  - ""
categories:
  - Web
tags:
  - snippet
  - wordpress
  - απενεργοποίηση
  - ςορδπρεσσ
  - σχόλια
---
Αλλο ένα quick tip για την απενεργοποίηση όλων των σχολίων στο wordpress site μας / σας / τους&#8230;

Πάμε στον αγαπημένο μας editor και βρίσκουμε το page.php

Βρίσκουμε την παρακάτω γραμμή κώδικα και την αφαιρούμε.

<pre class="brush: php; title: ; notranslate" title="">&lt;!--?php comments_template( '', true ); ?--&gt;</pre>

No more comments!