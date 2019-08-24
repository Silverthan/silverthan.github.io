---
title: 'WordPress: Πως να απενεργοποιήσετε όλα τα σχόλια'
date: 2013-04-09T06:19:34+00:00
author: Thanos
layout: post
permalink: /wordpress-pos-na-apenergopoihsete-ola-ta-sxolia/
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

```php
<?php comments_template( '', true ); ?>;
```

No more comments!