---
layout: post
title: Simple websites need simple CMS
---

This is just an early stage idea. If the concept will prove useful, we in creator5 will release it as an open source to help everyone, not just us.

Currently most used and beloved CMS solutions, such as WordPress, Drupal and Joomla are great, if you're building a big website for a tech-savvy customer, that is not afraid of using complex administration systems. But if you want to make just a simple few-page website, those systems are huge **overkill**.

I don't know, if it's just our experience, but currently used content management systems are really hard to use for a basic user. Too many options doesn't make users just confused, it enables them to screw things up and that makes them afraid to use system at all.

We believe, that we can do better.

> Perfection is achieved, not when there is nothing more to add, but when there is nothing left to take away - Antoine de Saint-Exupery


## What if...

- What if there was a micro CMS, that you could use for simple websites
- What if it was really simple to setup and also as easy to extend?
- What if it wasn’t build from a scratch, but stood on shoulders of giants and took advantage of a well tested and proven framework, so you wouldn’t have to learn new concepts?
- What if it was fully tested?
- What if the user interface was so simple and beautiful, that users would enjoy working with it?

We believe it’s possible. And if nothing else, we need it.


## Little technical specs

- PHP backend based on Silex micro framework and tested with PHPUnit. I didn't choose PHP because I would think, that it's the best thing out there. There are really strong arguments on side of Ruby or Node.js, but my argument for PHP on this project, is that majority of current internet runs on PHP, many customers now PHP and most hosting companies support PHP.
- SQLite, so you don’t even have to have MySQL server
- HTML5 and CSS3 using SASS + Compass
- JavaScript, jQuery, [medium editor with insert plugin](https://github.com/orthes/medium-editor-insert-plugin), tested with QUnit
- Grunt, Bower
- Distributed via Composer
- Open Source

I’m not saying, that there is no micro CMS out there. There certainly are, but I wasn’t able to find any, that meets the requirements above (if you know about some, please let me know).

Another thing, I’m not saying is, that we want to compete with Wordpress or Drupal. Not at all. They are great in what they do. Our niche is simple websites. **Because simple websites need simple CMS.**