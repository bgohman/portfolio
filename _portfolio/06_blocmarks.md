---
layout: post
title: Blocmarks
feature-img: "img/sample_feature_img_2.png"
thumbnail-path: "img/blocmarks.png"
short-description: Blocmarks is a bookmarking app that allows users to email, manage and share bookmarks and URLs.
permalink: blocmarks/

---
[Visit Blocmarks](https://bgohman-blocmarks.herokuapp.com/) \| [View Source](https://github.com/bgohman/blocmarks)

## Overview

I created Blocmarks as part of my Rails Development course at Bloc.  Blocmarks lets a user bookmark URLs via email, view other people's bookmarks and keep a personal collection of bookmarks grouped by topic.  While I never grasped the practicality of an app like this, it was a fun project to work on.  This project would be another opportunity to practice creating a user authentication, and and to make good design decisions.  The exercise of receiving incoming emails will be another exposure to a third party API, in this case Mailgun.


## User Stories

* As a user, I want to:
  * Sign up for a free account by providing a username, password and email
  * Sign in and out of Blocmarks
  * Email a URL to Blockarks and have it saved in the Blocmarks database
  * See an index of all topics and their bookmarks
  * Create, read, update, and delete bookmarks
  * Be the only one allowed to delete and update my bookmarks
  * Like and unlike bookmarks created by others
  * See a list of bookmarks on my personal profile that I've added or liked
  * See URL previews for each bookmark
* As a developer, I want to:
  * Write views using HAML instead of ERB
  * Make readable URLs

## Conclusion

As a web developer, it is important to be comfortable learning new technologies.  This project provided me the opportunity to work with Mailgun for the first time, and also to explore the Embed.ly API.  I enjoyed working on this project, especially working on the URL previews and using the friendly_id gem to add readable URLs.

