---
layout: post
title: "Conceptual origin of programming languages (my take on it)"
date: 2014-09-30 15:08:55 -0700
comments: true
categories: [Programming Languages]
---

As a software engineer every time I start a project I have the traditional dillema: "What programming language should I use?".
There a lot of them out there, and some might be better than other for certain tasks.
And this made me thinking, is there a broader classification, an etymology that these programming languages share?
While reading John Backus' Turing Award Paper [1], I was inspired to come with a classification of my own, based on the "origin" of the language:

1. from the machine (what John Backus refers to as _von-Neumann languages_);
2. from mathematical formalism (refered to as _Applicative models_), and;
3. from the business model.

<!-- more -->

1. Languages that stem from the machine
---------------------------------------

C is programming language that best describes this category.
It is designed to be easily and efficiently translated into machine code.
It's very closely modeled on the computing platform it runs on.

This family of languages is the most widely taught and most widely used.

2. Languages that stem from mathematical formalisms
---------------------------------------------------

Here, I include LISP and derivates. 
They are designed to better incorporate certain mathematical formalism. 


3. Languages that stem from the business model
----------------------------------------------

The expoenent languages here are Object Oriented Languages.

Combination languages?
----------------------

References
==========

[1] Backus, John. "Can programming be liberated from the von Neumann style?: a functional style and its algebra of programs." _Communications of the ACM_ 21.8 (1978): 613-641.
