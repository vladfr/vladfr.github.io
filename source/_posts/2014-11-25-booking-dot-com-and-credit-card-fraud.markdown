---
layout: post
title: "Booking.com and Credit Card Fraud"
subtitle: "give away my card data, and you might as well just "
date: 2014-11-25 19:29:55 +0200
comments: false
categories: blog
image: amsterdam.png
image-credit: mauro
image-credit-link: https://www.flickr.com/photos/mauro9/5068223866
---

<p class=small><em>Update 10 dec:</em> I've contacted Booking.com back in November but I've yet to hear from them. No funny transactions on my credit card so far, so at least that's good.</p>

We took a weekend trip to Sighisoara recently - a small medieval town in the heart of Romania. While it was a nice stay, there's one little thing that bothered me greatly.

I used [Booking.com](http://booking.com) to rent a hotel room, and I had to guarantee my reservation to the hotel with a credit card. Upon arrival at said hotel, I was baffled to see my full credit card details, including my <abbr>CVV/CVC</abbr>, printed on a piece of paper.

Yes, you read it right: _my full credit card data_. Once home, I went through the purchase process again, went through email receipts and Booking.com's Privacy and Terms pages - there is no mention of this what-so-ever. Also of interest: there's no mention of PCI-DSS on their website, which should have ticked me off, were I not overjoyed at the thought of our upcoming getaway.

> Booking.com has over 500.000 listings as of mid-2014.

Booking.com is one of the leading travel sites, with over 200M monthly visits as of June this year. While the bulk of its traffic comes from Europe, the web site is rapidly growing in the United States (source: [skift.com](http://skift.com/2014/06/17/the-most-popular-online-booking-sites-in-travel-2014-edition/)). In July 2014, booking.com [announced](http://news.booking.com/one-in-half-a-million/) they passed 500.000 listings.

Acquired in 2006 by the US-based [Priceline group](http://quotes.morningstar.com/stock/s?t=PCLN), Booking.com is the group's highest earner, making over 2/3 of the total revenue (source: [bloomberg.com](http://www.bloomberg.com/news/2013-01-22/booking-com-challenging-parent-priceline-in-u-s-travel.html)). Priceline's share price continues to grow steadily since the Booking.com acquisition, which analysts consider the most profitable travel acquisition of the past decade, [as cited by tnooz.com](http://www.tnooz.com/article/why-pricelines-purchase-of-booking-com-was-the-most-profitable-travel-deal-of-the-2000s/).

> Booking.com is based in Amsterdam - the host of the "PCI Europe" event.

Booking.com is based in Amsterdam, Netherlands - a city hosting the 8th edition of the [PCI Europe](http://www.pci-portal.com/event/pcieurope14) conference in just a few days. The irony won't escape anyone.

I don't understand how this is possible, so I'll keep looking into the issue. My first action will be to contact Booking.com themselves and see what they have to say. I found many posts on the web with similar issues, some dating as far as [2010](http://www.complaintsboard.com/complaints/bookingcom-c238032.html). Any thoughts are appreciated.

Comment on [HackerNews](https://news.ycombinator.com/item?id=8660105)!
