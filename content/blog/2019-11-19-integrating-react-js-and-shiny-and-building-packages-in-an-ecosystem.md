---
title: Integrating React.js and Shiny and, Building Packages in an Ecosystem
author: ''
date: '2019-11-19'
slug: integrating-react-js-and-shiny-and-building-packages-in-an-ecosystem
categories: []
tags: []
---


Details
**Note, this month our meetup will be a week earlier to accommodate the Thanksgiving week**

# Introduction

This month we are lucky to have two of our seasoned speakers presenting. Alan, from RStudio, will give his much-anticipated talk on integrating React.js with Shiny. The reactR package has been updated to allow you to integrate with htmlwidgets and access all the React components. Emil will talk about his experience integrating the textrecipes into an ecosystem of packages and the lessons that he has learnt. This is becoming increasingly more important as the number of packages grows and so does the complexity of the analysis pipeline.

Come early, network, enjoy the food and talks.

# Schedule
6:30 - 6:50 Networking
6:50 - 7:00 Welcome & general announcement
7:00 - 7:30 Integrating React.js and Shiny
7:30 - 8:00 Building a package that fits into an evolving ecosystem
8:00 - 8:30 Networking and Clean-up

# Talk 1

## Title: Integrating React.js and Shiny
## Speaker: Alan Dipert
## Abstract
React.js is a thriving JavaScript library that eases encapsulating and sharing sophisticated component libraries. The React.js ecosystem is filled with components for doing everything from color selection (react-color) to animation (react-spring). While it's always been technically possible to integrate React.js components with Shiny applications, it hasn't always been particularly obvious how. To make it easier, we augmented the excellent reactR package with functions specifically designed to make it easier to create new htmlwidgets, inputs, and outputs based on React.js components. In this talk, I will further motivate and demonstrate these new tools and do my best to empower the audience to try them out.

# Talk 2

## Title: Building a package that fits into an evolving ecosystem
## Speaker: Emil Hvitfeldt
## Abstract
With an ever-increasing amount of textual data is available to us, having a well-thought-out toolchain for modelling is crucial. tidymodels is a recent effort to create a modelling framework that shares the underlying design philosophy, grammar, and data structures of the tidyverse. textrecipes joined the roster a year ago and provided an exciting bridge to text preprocessing. This talk tells the tale of the package textrecipes; starting with the Github issue that sparked the idea for the package, go over the trials and challenges associated with building a package that heavily integrates with other packages all the way to the release on CRAN.