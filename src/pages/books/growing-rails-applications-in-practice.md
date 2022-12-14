---
layout: ../../layouts/PostLayout.astro
title: Growing Rails Applications in Practice
description: This book describes a complete toolbox that has served us well for all requirements that we have encountered.
featured: false
free: false
path: books
draft: false
buy_on_site: https://leanpub.com/growing-rails
buy_on_amazon:
cover: growing-rails-applications-in-practice
topics:
  - ruby on rails 3
authors:
  - henning koch
  - thomas eisenbarth
---

## What is "Growing Rails Applications in Practice" about?

We'd like to show you one path to write Rails apps that are a joy to understand and change, even as your team and codebase grows. This book describes a complete toolbox that has served us well for all requirements that we have encountered.

But before we do that, we need to let you in on an inconvenient secret: Large applications are large. The optimal implementation of a large application will always be more complex than the optimal representation of a smaller app. We cannot make this go away. What we can do is to organize a codebase in a way that "scales logarithmically". Twice as many models should not mean twice as many problems.

To accomplish this, you don't necessarily need to change the entire way your application is built. You don't necessarily need to introduce revolutionary architectures to your code. You can probably make it with the tools built into Rails, if you use them in a smarter way.

Compare this to sorting algorithms. When a sorting function is too slow, our first thought is not "install a Hadoop cluster". Instead we simply look for an algorithm that scales better. In a similar fashion this book is not about revolutionary design patterns or magic gems that make all your problems go away. Instead we will show how to use discipline, consistency and organization to make your application grow more gently

## Who should read "Growing Rails Applications in Practice"?
For beginner and experienced programmers

## What will you learn in "Growing Rails Applications in Practice".
Part I: New rules for Rails
In this part we unlearn bad Rails habits and introduce design conventions for controllers and user-facing models. By being consistent in our design decisions we can make it asier to navigate and understand our application even as its codebase grows.

The first part contains the following chapters:
- Beautiful controllers
- Relearning ActiveRecord
- User interactions without a database
- Part II: Creating a system for growth
- As we implement more and more requirements, all that code has to go somewhere. If all we do is add more lines to existing classes and methods, we end up with an unmaintainable mess.

In this part we show how to organize code in a way that encourages the creation of new classes which in turn enhances comprehensibility and maintainability. We also lean to contain the side effects that code can have on unrelated parts of our application.

The second part discusses the following topics:
- Dealing with fat models
- A home for interaction-specific code
- Extracting service objects
- Organizing large codebases with namespaces
- Taming stylesheets
- Part III: Building applications to last
- We show how to think about future maintenance when making decisions today. We make a case for adopting new technologies and patterns with care, and for taking full responsibility for those techniques and technologies that you do choose to adopt.

The last part contains the following chapters:

- On following fashions
- Surviving the upgrade pace of Rails
- Owning your stack
- The value of tests

