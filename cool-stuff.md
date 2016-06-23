---
layout: post
title: Cool stuff
date: 2010-07-09 11:12:22.000000000 +02:00
type: page
published: true
status: publish
categories: []
tags: [amazon, book]
author: Brice Dutheil
---
# Le mouvement anti-if

_Pour que le design de notre code soit un peu plus orienté objet!_

[![I have joined Anti-IF Campaign](http://antiifcampaign.com/assets/banner_ive-joined.gif)](http://www.antiifcampaign.com)


# Quelques livres à posséder

{% comment %}
Idea from gist https://gist.github.com/ioddly/5589077
{% endcomment %}

{% comment %}
# size argument can be S, M, or L
{% endcomment %}
{% assign amazon_product_image_link = "[![book](http://ws.assoc-amazon.com/widgets/q?_encoding=UTF8&ASIN=$asin$&Format=_$size$L110_&ID=AsinImage&MarketPlace=US&ServiceVersion=20070822&WS=1)](http://amazon.com/exec/obidos/ASIN/$asin$/)" %}
{% assign img_size = "S" %}

<div class="table-wrapper" markdown="block">

| {{ amazon_product_image_link | replace:'$asin$','0321503627' | replace:'$size$',img_size }} | **Growing Object Oriented Software,<br /> Guided by Tests** <br /> by **Steve Freeman** and **Nat Pryce** |
| {{ amazon_product_image_link | replace:'$asin$','0132350882' | replace:'$size$',img_size }} | **Clean Code** <br /> by **Rober C. Martin** |
| {{ amazon_product_image_link | replace:'$asin$','0321125215' | replace:'$size$',img_size }} | **Domain Driven Design** <br /> by **Eric Evans** |
| {{ amazon_product_image_link | replace:'$asin$','0596809484' | replace:'$size$',img_size }} | **97 Things Every Programmer Should Know** <br /> Collective Wisdom |
| {{ amazon_product_image_link | replace:'$asin$','0321349601' | replace:'$size$',img_size }} | **Java Concurrency in Practice** <br /> by **Brian Goetz** |
| {{ amazon_product_image_link | replace:'$asin$','0321356683' | replace:'$size$',img_size }} | **Effective Java (2nd Edition)** <br /> by **Joshua Bloch** |
| {{ amazon_product_image_link | replace:'$asin$','0557078326' | replace:'$size$',img_size }} | **Real World Java EE Patterns** <br /> by **Adam Bien** |
| {{ amazon_product_image_link | replace:'$asin$','1934356050' | replace:'$size$',img_size }} | **Pragmatic Thinking & Learning** <br /> by **Andy Hunt** |
| {{ amazon_product_image_link | replace:'$asin$','0321200683' | replace:'$size$',img_size }} | **Enterprise Integration Patterns** <br /> by **Gregor Hohpe** and **Bobby Woolf** |
| {{ amazon_product_image_link | replace:'$asin$','143022889X' | replace:'$size$',img_size }} | **Java EE 6** <br /> by **Antonio Goncalves** |
| {{ amazon_product_image_link | replace:'$asin$','0321127420' | replace:'$size$',img_size }} | **Patterns of Enterprise Application Architecture** <br /> by **Martin Fowler** |
| {{ amazon_product_image_link | replace:'$asin$','0470876417' | replace:'$size$',img_size }} | **Business Model Generation** <br /> by **Alexander Osterwalter** and **Yves Pigneur** |
| {{ amazon_product_image_link | replace:'$asin$','0201633612' | replace:'$size$',img_size }} | **Design Patterns** <br /> by **John Vlissides**, **Richard Helm**, **Ralph Johnson** and **Erich Gamma** |
| {{ amazon_product_image_link | replace:'$asin$','1617291803' | replace:'$size$',img_size }} | **Reactive Design Patterns** <br /> by **Dr. Roland Kuhn**, **Brian Hanafee** and **Jamie Allen** |

</div>