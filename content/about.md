---
title: About mynock
---

# Mynock

## About This Site

Mynock is a [nanoc3](http://nanoc.stoneship.org) blog starter kit, branched from 
mgutz's lovely [nanoc3_blog](http://github.com/mgutz/nanoc3_blog), mostly with
routing preferences that I enjoy.  Feel free to fork and abuse.

The blog compiles into HTML, and copies static assets into the proper places.  It
produces a fast, light, and clean site hostable anywhere you have access to the filesystem.

Source is available from the [mynock](http://github.com/bvandgrift/mynock) github repository.

Features: 

- Minimalist CSS site, with sass support baked in
- Uses file extension to determine filter:
  `{'.erb' => :erb, '.md' => :rdiscount, '.markdown' => :rdiscount,'.haml' => :haml, '.sass' => :sass}`
- Configurable 0..n full articles on the front page
- Configurable 0..n excerpted links on the front page
- Tagging / generation of tag pages
- Generates tags list
- Generates archives list
- Generates navigation links to articles by date
- [DISQUS](http://www.disqus.com) commenting integration (optional)
- RSS/atom feed
- Generates sitemap.xml for SEO

## Thanks

My thanks to Mario L Gutierrez for a nice starting place, Jon Distad for sanity checking,
and [Denis Defreyne](http://stoneship.org/about/), author of nanoc.
