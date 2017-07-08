---
layout: post
title: Introduction to Single Page Applications
date: {}
tags: '-Angular4 -SPA -Singlepageapplication'
categories:
  - World Of Angular
published: true
author: Deepak
description: Understanding what a single page application is.
---


Lets start of with what Angular is: 

**Angular is a leading JavaScript framework for building Single Page Applications.** 

### So now what is a Single Page Application or SPA?

In a standard web application, when you click on a link, the entire page is reloaded. So, a request is sent to the server and we get the response with the current page replaced by another. Therefore, these kind of applications are called **Multiple Page Applications.**

> In a SPA, instead of loading the whole page we replace the content part of the page with another, ie instead of hitting the server for link click, we replace the page using JS within the browser.


### OK so now what difference does a SPA make?

Lets have a look at some of its advantages over conventional MPAs.

**1. SPA is fast! :** Most resources(HTML+CSS+JS) are only loaded once throughout the life span of the application, meaning only the data is transmitted back and forth.
**2. Caching :** SPA can cache local storage effectively and works even offline. This is a core feature of a Progressive Web App.

### Now lets look at its advantages in a developer's prespective :

1. There is no need to write code to render pages on the server (Eg: JSP,Servlet, ASP,etc)

2. Debugging is easy using Devtools available in Chrome.

3. Easy to build multi device apps as backend takes care of only data.(using APIs).

4. Frontend and Backend are loosely coupled resulting in separation of concerns and making development easy.

### Some of its drawbacks:

1. SEO optimization can get pretty tricky.

2. Initial download can be slow as the framework can be heavy on the client. But this is changing as the newer 
versions of these frameworks are giving high importance on reducing the bundle size.

3. Memory leaks in JS can cause systems to slow down. But hey! TypeScript has this issue sorted.

Here is a list of few webapps that are infact Single page applications :

1. Twitter
2. FaceBook
3. Gmail

Have a look at the sites listed [here](https://www.awwwards.com/websites/single-page/) and get inspired!


       

### Summary

1. We have learned the reason why the SPA came into existence.

2. We got to know the pros and cons of a SPA application.

### Whats coming Up?

In the next article we kick start the journey of learning Angular 2+. Its going to fun I promise.
Have Fun!
