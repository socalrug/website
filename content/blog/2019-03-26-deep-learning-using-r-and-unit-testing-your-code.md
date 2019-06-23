---
title: Deep Learning using R and Unit Testing Your Code
author: Ash Pahwa and John Peach
date: '2019-03-26'
slug: deep-learning-using-r-and-unit-testing-your-code
categories: []
tags: []
banner: "img/banners/Mar26_2019.png"
---

<h2 style="color: blue">These talks will be held on Tuesday, March 26th, 2019.</h2>

TensorFlow has become the defacto standard for distributed computing of deep neural networks. For over a year, R has had excellent support for this capability via a series of interrelated packages (keras, tfestimators, tensorflow, tfdatasets). Check out https://tensorflow.rstudio.com/ Then come join us for the first part of a two-part talk on using R and TensorFlow.

Hadley Wickham famously said, "it’s not that we don’t test our code, it’s that we don’t store our tests so they can be re-run automatically." So, let us learn how to do unit testing with the testthat package. Instead of manually testing your code, automate the process and increase the reliability, maintainability and actually write better code faster.

#=== Talks

<strong>Speaker: Ash Pahwa<strong>

<h3>Title: Deep Learning using R and TensorFlow (Part 1)</h3>

Abstract:
Google released TensorFlow software in 2015 targeted for the Deep Learning applications. Two primary misconceptions about TensorFlow are as follows. First, it can only be used with Python and second, it can only be used for building deep learning applications

This talk will demystify these concepts. First, TensorFlow can also be used with R and any programming language. Second, TensorFlow’s main objective is to solve the mathematical problem (including differential equations) which contains multi-dimensional arrays (or tensors). Deep Learning Neural Networks is just another application of TensorFlow.

In this first part, the fundamental architecture of TensorFlow will be covered. TensorFlow works on the concept of DAG (Directed Acyclic Graph). First, a DAG of the mathematical problem is built, and then the DAG is executed in the most efficient way using CPU, GPU or TPUs. The interface between R and TensorFlow will be discussed by building Neural Networks using R and TensorFlow.

<strong>Speaker: John Peach</strong>

<h3>Title: It’s not that we don’t test our code, it’s that we don’t store our tests</h3>

Abstract:
Software testing is important and we all do it. However, it is often not done in a principled way. It is standard practice in the software development community but is less common in analytics. testthat is a testing framework for R that is similar to other unit testing systems that you may know. It seamlessly integrates into the package development workflow so that you can test early and often.

testthat decreases code development and maintenance frustration. Unit testing will help you develop better code structure by making your code easier to test. Thus, lazy development becomes better development. It allows you to quickly debug issues by isolating the source of a bug faster so that you can get back to the ‘real’ coding. It also allows you to have confidence that your changes did not break existing code.

We will go over some basic unit testing concepts, how to set up testthat and write tests.