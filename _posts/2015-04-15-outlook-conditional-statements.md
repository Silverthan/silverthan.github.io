---
id: 217
title: Outlook Conditional Statements
date: 2015-04-15T07:00:04+00:00
author: Thanos
layout: post
guid: http://www.55emails.com/?p=217
permalink: /outlook-conditional-statements/
categories:
  - Email Marketing
tags:
  - conditional statements
  - if mso
  - mso
  - outlook
  - target outlook
---
It&#8217;s not a big surprise when we need to write some specific CSS for our html email templates, in order to target Microsoft&#8217;s offline email client, our beloved **Outlook**.

We can do that by using a simple <if> statement in the <head> of our document, known as a conditional statement:

<pre class="brush: css; title: ; notranslate" title="">&lt;!--[if mso]&gt;
 // Only for Outlook (all versions)
&lt;![endif]--&gt;
</pre>

We can take it even further from there and target specific versions of Outlook.

### Specific Outlook Conditional Statements

First of all, take a note / screenshot of the numbers below, they are the versions of Outlook.

  * Outlook 2000 &#8211; Version 9
  * Outlook 2002 &#8211; Version 10
  * Outlook 2003 &#8211; Version 11
  * Outlook 2007 &#8211; Version 12
  * Outlook 2010 &#8211; Version 14
  * Outlook 2013 &#8211; Version 15

If we want to target Outlook 2007 and later

<pre class="brush: css; title: ; notranslate" title="">&lt;!--[if gte mso 12]&gt;
 // Outlook 2007 and later
&lt;![endif]--&gt;
</pre>

If we want to target only Outlook 2010

<pre class="brush: css; title: ; notranslate" title="">&lt;!--[if mso 14]&gt;
 // Only Outlook 2010
&lt;![endif]--&gt;
</pre>

Happy targeting!