---
layout: post
title: Blocipedia
feature-img: "img/sample_feature_img.png"
thumbnail-path: "img/blocipedia.png"
short-description: Blocipedia is a production quality SaaS application that allows users to create their own wikis.
permalink: blocipedia/

---
[Visit Blocipedia](https://bgohman-blocipedia.herokuapp.com/) \| [View Source](https://github.com/bgohman/blocipedia)

## Overview

I created Blocipedia as part of my Rails Development course at Bloc.  Wikis are a great way to access and contribute to crowd-sourced content.  As a learning exercise, I wanted to create my own wiki application in which you can create, edit and view wikis.  User-created wikis are viewable by everyone, unless the user purchases a premium membership through Stripe that allows them the option of creating private wikis.  Premium members can add and remove collaborators to their private wikis.  A user can downgrade back to a standard account, at which time any of their private wikis become public.

## Personal Objectives

Incorporating a working payment system was a very important goal for me.  Payment systems are complicated and often messy.  Implementing this into one of my applications would be an interesting challenge.  So much of developing for the web depends on using and understanding a myriad of APIs, and I want to continue getting more comfortable with digging into the documentation to quickly understand how things interact.

## User Stories

* As a Developer, I want to:
  * Generate views using HAML, instead of ERB.
  * Offer three user roles: Admin, Standard, or Premium.
  * Seed the development database with users and wikis.
* As a User, I want to:
  * Sign up for a free account by providing user name, email, and password.
  * Sign in and out of Blocipedia.
  * Create, Read, Update, and Destroy Public Wikis.
  * Display and edit personal Wikis in my user profile.
  * Create wikis using Markdown syntax.
  * Upgrade my account from a Standard to Premium plan.
* As a Premium User, I want to:
  * Create private wikis.
  * Add and remove collaborators from my private wikis.

## Conclusion

I really liked working with Stripe, and it will be my first choice the next time I want to incorporate a payment gateway in a web application. I feel a lot more comfortable with the Stripe API and in general with approaching a new API.  The Wiki CRUD, and the user sign-up/sign-in functionality gave me another opportunity to practice the core principles of the MVC model and RESTful design.
