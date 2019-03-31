---
id: 508
title: 'WordPress: Πως να Αλλάξετε το default logo'
date: 2013-03-28T15:58:27+00:00
author: Thanos
layout: post
guid: http://blog.silverthan.gr/?p=508
permalink: /wordpress-pos-na-allaksete-to-default-logo/
wpzoom_post_title:
  - 'Yes'
wpzoom_post_readmore:
  - 'Yes'
wpzoom_post_url:
  - ""
categories:
  - Web
tags:
  - change logo
  - snippet
  - wordpress
  - ςορδπρεσσ
---
Είναι πολύ δύσκολο και δε θα βρείτε το κώδικά πουθενά αλλού!

Αστειεύομαι βεβαίως βεβαίως, είναι πολύ απλό και χιλιοειπωμένο.

Βρείτε το functions.php και κάντε κλικ στο edit. Κάντε αντιγραφή / επικόλληση τον παρακάτω κώδικα, μόνο σιγουρευτείτε ότι έχετε ήδη ανεβάσει το λόγότυπο και το url είναι σωστό.

<pre class="brush: php; title: ; notranslate" title="">function custom_login_logo() {
	echo '&lt;style type="text/css"&gt;
	h1 a { background-image: url('.get_bloginfo('template_directory').'/images/custom-login-logo.png) !important; }
	&lt;/style&gt;';
}
add_action('login_head', 'custom_login_logo');
</pre>

Αυτό ήταν!