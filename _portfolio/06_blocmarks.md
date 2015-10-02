---
layout: post
title: Blocmarks
feature-img: "img/sample_feature_img.png"
thumbnail-path: "img/blocmarks.png"
short-description: Blocmarks is a social bookmarking app that allows users to email, manage and share bookmarks and URLs.
permalink: blocmarks/

---
## Overview

I created Blocmarks as part of my Rails Development course at Bloc.  Blocmarks lets a user bookmark URLs via email, view other people's bookmarks and keep a personal collection of bookmarks grouped by topic.  While I never grasped the practicality of an app like this, it was a fun project to work on.

## Personal Objectives

Incorporating a working payment system was a very important goal for me.  Payment systems are complicated and often messy.  Inocoporating this into one of my applications would be an interesting challenge.  So much of developing for the web depends on using and understanding a myriad of APIs, and I want to continue getting more comfortable with digging into the documentation to quickly understand how things interact.

## User Stories

* As a Developer, I want to generate views using HAML, instead of ERB.
* As a User, I want to be able to sign up for a free account by providing user name, email, and password.
* As a User, I want to be able to sign in and out of Blocipedia.
* As a User with a standard account, I want to be able to Create, Read, Update, and Destroy Public Wikis.
* As a User, I want a User Profile to display and edit personal Wikis.
* As a Developer, I want to offer three user roles: Admin, Standard, or Premium.
* As a Developer, I want to seed the development database with users and wikis.
* As a User, I want to create wikis using Markdown syntax.
* As a User, I want to upgrade my account from a Standard to Premium plan.
* As a Premium User, I want to create private wikis.
* As a Premium User, I want to add and remove collaborators from my private wikis.

## Conclusion

I really liked working with Stripe, and it will be my first choice the next time I want to incorporate a payment gateway in a web application. I feel a lot more comfortable with the Stripe API and in general with approaching a new API.  The Wiki CRUD, and the user sign-up/sign-in functionality gave me another opportunity to practice the core principles of the MVC model and RESTful design.  I also enjoyed working with Embedly to show the links as thumbnail previews.