---
title: How to handle a re-created repo
layout: en
permalink: how-to-handle-recreated-repo/
---

### What This How-To Covers

This How-To explains how to handle the case when you re-create your repository. We recommend you start with the [Getting Started](/docs/user/getting-started/) and [Build Configuration](/docs/user/build-configuration/) guides before reading this one.

## The Ideal Route

The cleanest way is to disable TravisCI builds before re-creating the repo and then resync/re-enable them afterwards before you make any commits.

## When You Didnt Follow Ideal Route

You probably didn't know about the Ideal Route (like me) - so you have a re-created repo, but TravisCI won't build it. What you should do is this:

* disable the build from your Account settings page.
* click on the re-sync button to get TravisCI to refind your repos.
* enable the build from your Account settings page.
* make a commit in your repo - this will trigger TravisCI to pick up the build.
