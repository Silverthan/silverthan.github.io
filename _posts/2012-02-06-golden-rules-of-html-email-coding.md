---
id: 55
title: Golden Rules of HTML Email Coding
date: 2012-02-06T09:07:28+00:00
author: Thanos
layout: post
guid: http://www.55emails.com/?p=55
permalink: /golden-rules-of-html-email-coding/
categories:
  - Email Marketing
tags:
  - email coding
  - html emails
---
When we design or code a template for an email we have to keep in mind that it is not an advanced-skills-showoff competition like the ones we see in normal websites &#8211; and there&#8217;s nothing wrong with that by the way. Our code must be simple, compact and maintanable.

The ESP&#8217;s (Email Service Providers) have one thing in common with the browsers &#8211; they do not agree with each other and display our content in their own (unique sometimes) way. Hence, we have to be extra careful and follow the triptych of success &#8211; test, test and test!

Follow the simple rules below to make sure you keep up with the html best practises for email development<!--more-->

#### Use Tables, not divs

Most modern email clients understand how to render tables, and they don&#8217;t understand DIVs and CSS positioning, that&#8217;s why we have to use tables to make sure our elements and section do not fly around in random. We can ensure our layout works by simply breaking it down into exact rows and columns.

#### Do not shortcode

If you want to set the font size, weight, and line height you need to use font-size, font-weight, and line-height as separate style properties.

#### _Target=&#8221;_blank&#8221;_ for all links

All links should open in a new window to avoid the rare cases in which the email client web interface doesn&#8217;t do that by default.

#### Hard-code your image dimensions

This goes for images as well as table cells where you need the dimensions to work perfectly. Hard-code those dimensions in, using the _width_ and _height_ attributes. Note that when using these attributes, do not enter “px” after the pixel amount.

#### Absolute paths for images

We have to use full-path URLs for our images so that they will render in the client

#### Never delete your images

People may open email messages months after we&#8217;ve sent them, so if we delete the images, the newsletter will be broken.

#### Avoid using a WYSIWYG editor to code your HTML

Using a WYSIWYG editor in design view often creates code that is very difficult to mantain and it is rendered in different ways from the email service providers, hence we should code and then preview the result.

#### Keep your code as clean as possible

Minimal and clean code is the way to go, not only for the file size of the email but for easier rendering on behalf of the email service providers and faster maintanance

Most modern email clients understand how to render tables, and they don&#8217;t understand DIVs and CSS positioning, that&#8217;s why we have to use tables to make sure our elements and section do not fly around in random. We can ensure our layout works by simply breaking it down into exact rows and columns.

#### Total width should be 500-600px

Despite the larger screens and big resolutions we have to keep in mind that the actual email area is not wider than 600 &#8211; 650px. And if we don&#8217;t want the users to scroll horizontally to read or click on our CTA we should keep it fixed at less than 600px.

#### No JavaScript

Avoid using JavaScript. Most email software will disable it anyway.

#### No Flash

Flash and embedded movie files won&#8217;t work. Flash was built for the browser and that&#8217;s where it should be.

#### Never link to an external css file

Don’t bother using the link element to reference an external style sheet: Google Mail, Hotmail, and other email software will ignore, modify, or delete these external references to a style sheet.

#### No styles in the <head> section

Most email providers and tools cut off the _head_ and _body_ tags so it doesn&#8217;t interfere with their _head,body_ so there is no point adding anything in that section as it will be lost. Usually we use the _title_ for the subject line.

#### Inline styling

Add your styles in the old-fashioned way, right in the element itself.

#### &#8216;Alt&#8217; your images

Images are in many cases disabled by default hence not visible if we don&#8217;t actually enable them. This creates an empty / ugly / inconsistent email. We should always &#8216;alt&#8217; our images to make sure the viewer can see (and click) on a button with a specific message. For example if the image says &#8220;deposit now&#8221; we should &#8216;alt&#8217; it with &#8220;deposit now&#8221;.