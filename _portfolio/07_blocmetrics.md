---
layout: post
title: Blocmetrics
feature-img: "img/sample_feature_img_3.png"
thumbnail-path: "img/blocmetrics.png"
short-description: Blocmetrics is an analytics and reporting service for tracking and reporting user activity on your web sites.
permalink: blocmetrics/

---
[Visit Blocmetrics](https://bgohman-blocmetrics.herokuapp.com/) \| [View Source](https://github.com/bgohman/blocmetrics)

## Overview

I created Blocmetrics as part of my Rails Development course at Bloc.  The key features include client-side JavaScript that tracks events on a users' website, a server-side API that captures and saves the events to a database, and a Rails application that displays the event data.

## User Stories

* As a user, I want to:
  * Sign up for a free account by providing a name, password, and email.
  * Sign in and out of Blocmetrics.
  * Register an application with Blocmetrics for tracking.
  * Associate events with registered applications.
  * Use JavaScript to capture client-side events in my application.
  * See a graph of events for each registered application.

* As a developer, I want to:
  * Receive incoming events in an API controller.

## Conclusion

The biggest challenge of this project turned out to be dealing with security concerns when passing information between different web applications.  I learned how to use cross-origin resource sharing (CORS) to control this communication without opening up security vulnerabilities.  I really enjoyed using Chartkick and the Groupdate gem to build the charts and graphs for displaying the data in a visually inviting way.