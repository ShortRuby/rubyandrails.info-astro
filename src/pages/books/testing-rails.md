---
layout: ../../layouts/PostLayout.astro
title: Testing Rails
description: Learn to test Ruby on Rails web applications from the ground up in this comprehensive guide to modern testing practices.
featured: false
free: true
path: books
draft: false
buy_on_site: https://books.thoughtbot.com/books/testing-rails.html
buy_on_amazon:
cover: testing-rails
topics:
  - testing
  - design patterns
  - TDD (Test Driven Development)
authors:
  - thoughbot
---

Learn to test Ruby on Rails web applications from the ground up in this comprehensive guide to modern testing practices.

As software developers, we are hired to write code that works. If our code doesn’t work, we have failed.

So how do we ensure correctness?

One way is to manually run your program after writing it. You write a new fea- ture, open a browser, click around to see that it works, then continue adding more features. This works while your application is small, but at some point your pro- gram has too many features to keep track of. You write some new code, but it unexpectedly breaks old features and you might not even know it. This is called a regression. At one point your code worked, but you later introduced new code which broke the old functionality.

A better way is to have the computer check our work. We write software to auto- mate our lives, so why not write programs to test our code as well? Automated tests are scripts that output whether or not your code works as intended. They verify that our program works now, and will continue to work in the future, with- out humans having to test it by hand. Once you write a test, you should be able to reuse it for the lifetime of the code it tests, although your tests can change as expectations of your application change.

Any large scale and long lasting Rails application should have a comprehensive test suite. A test suite is the collection of tests that ensure that your system works. Before marking any task as “complete” (i.e. merging into the master branch of your Git repository), it is imperative to run your entire test suite to catch regressions.

If you have written an effective test suite, and the test suite passes, you can be
confident that your entire application behaves as expected.

A test suite will be comprised of many different kinds of tests, varying in scope and subject matter. Some tests will be high level, testing an entire feature and walking through your application as if they were a real user. Others may be specific to a single line of code. We’ll discuss the varying flavors of tests in detail throughout this book.