---
title: Hotmail and Line Height
date: 2012-08-09T12:34:17+00:00
author: Thanos
layout: post
permalink: /hotmail-and-line-height/
categories:
  - Email Marketing
tags:
  - fix hotmail line height problem
---
Hotmail and line-height are not friends to the html email coder.

Apparently Hotmail adds a class and keeps line-height to default, even if you tried to define it in your style, in your _table_ or your _td._

To solve this problem which can drive you crazy, the only thing you have to do is insert the snippet below in the head of your html email template.

```css
.ExternalClass * {  
Line-height: 100%;  
}  
```

You can then define the line-height without fear of breaking in the popular ESP.

If you have any other simpler hack for this, please share in the comments.