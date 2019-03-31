---
id: 165
title: Youtube time feature
date: 2010-08-14T13:39:21+00:00
author: Thanos
layout: post
guid: http://blog.silverthan.gr/?p=165
permalink: /youtube-time-feature/
categories:
  - Web
tags:
  - specific time
  - youtube
---
Δεν ξέρω πόσα βιντεάκια υπάρχουν στο youtube, ξέρω όμως ότι είναι πάρα πολλά. Η διάρκεια αυξήθηκε πρόσφατα από 10 σε 15 λεπτά για ακόμα περισσότερο περιεχόμενο. Τι γίνεται όμως όταν μοιραζόμαστε στο web ένα βιντεάκι και θέλουμε να δείξουμε μια συγκεκριμένη σκηνή που κρατάει 20&#8243;? Βάζαμε σχόλιο &#8220;δείτε από το 2&#8217;36&#8221; και μετά&#8230;&#8221;. Well, not anymore&#8230;

Με το time feature μπορούμε να ενσωματώσουμε στο link από που θέλουμε να ξεκινήσει! Χρήσιμο όταν θέλουμε να παρακάμψουμε την εισαγωγή / διαφημίσεις / whatever&#8230;

Ακολουθεί παράδειγμα:

<a title="Youtube time feature, html5 etc" href="http://www.youtube.com/watch?v=EdDc7sWjCL4#t=6m15s" target="_blank">http://www.youtube.com/watch?v=EdDc7sWjCL4<span style="color: #ff0000;"><strong>#t=6m15s</strong></span></a>

Το μόνο που χρειάζεται να προσθέσουμε στο τέλος του url είναι το #t=XmYs όπου Χ και Υ ο αριθμός των λεπτών <span style="text-decoration: line-through;">και των χοντρών</span> και των δευτερολέπτων αντίστοιχα.