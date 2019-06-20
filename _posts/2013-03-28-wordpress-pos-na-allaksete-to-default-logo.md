---
title: 'WordPress: Πως να Αλλάξετε το default logo'
date: 2013-03-28T15:58:27+00:00
author: Thanos
layout: post
permalink: /wordpress-pos-na-allaksete-to-default-logo/
categories:
  - Web
tags:
  - code snippets
  - wordpress change login logo
---
Είναι πολύ δύσκολο και δε θα βρείτε το κώδικά πουθενά αλλού!

Αστειεύομαι βεβαίως βεβαίως, είναι πολύ απλό και χιλιοειπωμένο.

Βρείτε το functions.php και κάντε κλικ στο edit. Κάντε αντιγραφή / επικόλληση τον παρακάτω κώδικα, μόνο σιγουρευτείτε ότι έχετε ήδη ανεβάσει το λόγότυπο και το url είναι σωστό.

```php
function custom_login_logo() {
	echo '<style type="text/css">;
  h1 a { background-image: url('.get_bloginfo('template_directory')
  .'/images/custom-login-logo.png) !important; }
	</style>';
}
add_action('login_head', 'custom_login_logo');
```

Αυτό ήταν!