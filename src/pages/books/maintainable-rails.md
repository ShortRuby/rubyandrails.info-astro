---
layout: ../../layouts/PostLayout.astro
title: Maintainable Rails
description: Learn how to build a maintainable Rails application by using the rom-rb and dry-rb set of gems to your advantage. 
featured: false
free: false
path: books
draft: false
buy_on_site: https://leanpub.com/maintain-rails
buy_on_amazon:
cover: maintainable-rails
topics:
  - ruby
  - ruby on rails
authors:
  - ryan bigg
---

Learn how to build a maintainable Rails application by using the rom-rb and dry-rb set of gems to your advantage. Move away from messy, traditional Rails code and move towards crisp, clean code.

The default structure of Rails applications hasn't changed all that much in over a decade. And with good reason: this directory structure makes it easy to jump into building a Rails application.

While I agree that this way is still extremely simple and great for getting started within a Rails application, I do not agree that this is the best way to organise a Rails application in 2018 with long-term maintenance in mind. A decade of Ruby development has produced some great alternatives to Rails' MVC directory structure that are definitely worthwhile to consider.

One alternative can be found in the combination of the rom-rb and dry-rb set of gems.

The `rom-rb` gems allow us to interact with a database with just as much ease as Active Record, but with the added benefit that persistence and business logic aren't bundled together in the same class.

The `dry-rb` gems allow for splitting the validation logic away from the business logic's class (dry-validation) and also provides a sensible alternative to the community-wide pattern of service objects (dry-transaction).

This book covers how you would go about integrating these gems into a brand new Rails application, building features in an iterative fashion, resulting in a maintainable structure for the whole application.