---
title: Advanced HTML Hacks for Email Development
date: 2012-06-06T09:28:59+00:00
author: Thanos
layout: post
permalink: /advanced-html-hacks-for-email-development/
categories:
  - Email Marketing
tags:
  - advanced html hacks
  - how to html an email
---
You may have came across the post on [basic html rules for html emails](/golden-rules-of-html-email-coding/ "Golden Rules of HTML Email Coding") coding a couple of months, but this time we are going to take it alittle bit further on more advanced topics.

### Gmail line break fix

[Gmail adds a gap](/gmail-line-break-fix/ "Gmail line break fix") below all images like a line break but there is a fix for that. We add style=”display:block”on all img elements. Also, if your image is within a hyperlink, be sure to add border=”0” too, otherwise a big ugly border will appear around it.

### Outlook doesn&#8217;t like Animated gifs

Animated .gif files work in most email service providers, however they do not work in Outlook. Keep that in mind in case you are using an animated gif for a CTA. It will only show the first frame, however the link will work withour any problem.

### Use full hex color OR rgb()

3-digit hex colors (#fff) cannot be read from all ESPs so to make sure people don&#8217;t see the default ugly blue one we have to use the full 6-digit (#ffffff) or the rgb format ( rgb(255, 255, 255) )<!--more-->

### Encoding and conversion to entities for languages

Using the utf-8 encoding in our emails is not 100% effective and we can see many times that special characters are displayed as boxes or other strange characters. That&#8217;s why we should convert all non-latin characters to their perspective equivalent.

### Use cellspacing and cellpadding first and THEN margin, padding

Floating elements do not have the same behaviour in all email clients and it is better to create spaces with the cellpadding and cellspacing attributes to avoid problems. This doesn&#8217;t mean margin and padding will not work, but should be used as a last resource.

### Yahoo doesn’t accept paragraphs

Yahoo doesn’t accept paragraphs (<p>), and does not create a double line break between them, so it’s best not to use the p tag, but just separate lines by normal  
<br>’s.