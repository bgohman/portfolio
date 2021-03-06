---
layout: post
title: OpenTodoAPI
feature-img: "img/sample_feature_img.png"
thumbnail-path: "img/open_todo_api.png"
short-description: Open Todo API is an API for a to-do list application to allow users to authenticate and manage their information externally.
permalink: open_todo_api/

---

[Visit Open Todo API](https://bgohman-open-todo-api.herokuapp.com/) \| [View Source](https://github.com/bgohman/open-todo-api)

## Overview

I created Open Todo API as part of my Rails Development course at Bloc.  This project is a replica of Todo.txt which allows users to create, use and share their list on all of their devices.  The API allows users to interact with their list from the command line or a browser.  It also supports other platforms so any programmer can build on this tool in new ways.

## User Stories

* As the Open Todo API, I want to:
  * Return JSON representations of users, lists, and items.

* As a user, I want to:
  * Authenticate myself from the command line, using a username and password.
  * Create new users, lists, and items from the command line.
  * Remove users and lists from the command line.
  * Update list and item attributes from the command line.

## Conclusion

I learned a lot about using ActiveModel::Serializer to turn various objects into JSON in order to recieve and send data, and how to validate the JSON output with JSONLint.