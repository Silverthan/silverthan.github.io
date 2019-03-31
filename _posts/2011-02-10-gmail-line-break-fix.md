---
id: 773
title: Gmail line break fix
date: 2011-02-10T08:52:23+00:00
author: Thanos
layout: post
guid: http://www.55emails.com/?p=3
permalink: /gmail-line-break-fix/
categories:
  - Email Marketing
tags:
  - gmail line break
  - white line under images
---
We see many times in gmail a small break right after an image. This looks really bad when we also have a different background colour, black for example, and we will see a very disturbing white line across our template.

There is a fix for that and it is quite simple. We need to define the image as a block element.

See the code below:

<pre class="brush: xml; title: ; notranslate" title="">&lt;img style="display: block;" src="http://www.mysite.com/cat.jpg" /&gt;

</pre>