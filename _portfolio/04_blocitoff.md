---
layout: post
title: Blocitoff
feature-img: "img/sample_feature_img.png"
thumbnail-path: "img/blocitoff.png"
short-description: Blocitoff is a self-destructing to-do list application designed to keep your to-do lists managable.
permalink: /blocitoff/

---
## Overview

I created Bloccit as part of my Rails Development course at Bloc.  This was the first project that I completed without following a step by step guide.  The challenge was to apply what I had learned in the foundational phase of the course to a new project.

## Problem

It seems that to-do lists frequently become bloated after being used for even a short period of time.  Low priority items repeatedly get put off, and before long your list is cluttered with them.  Blocitoff will address this issue of to-do list clutter!

## Solution

As with any traditional to-do list, a user can create new items, and then mark them as completed.  The key feature of Blocitoff is that to-do items are automatically deleted seven days after their creation date.  Using Bloccitoff helps develop good productivity habits.  You are more likely to consider whether a task is truly important before adding it to your list, and when items approach their deadline you have a second chance to decide if it is a priority.  This is an improvement over passively adding a task to a to-do list that remains there for a very long period of time.

## Results

The key feature of Bloccitoff is that tasks older than seven days be deleted.  This was accomplished by using a cusotom rake task:
{%highlight ruby%}
namespace :todo do
  desc "TODO"
  desc "Delete items older than seven days"
  task delete_items: :environment do
    Item.where("created_at <= ?", Time.now - 7.days).destroy_all
  end
end
{%endhighlight%}


## Conclusion

Blocitoff was a straightforward and simple application.  It gave me a chance to practice implementing user authentication from scratch as well as using Ajax for marking items as complete.  It was also my first introduction to custom rake tasks.


