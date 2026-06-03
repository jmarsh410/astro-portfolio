---
layout: "../../layouts/WorkLayout.astro"
title: "Spacecraft"
tags: ["js", "css", "html", "dev", "cms", "animation"]
image:
  url: "/projects/spacecraft/spacecraft-hero.jpg"
  alt: "The Spacecraft Design Panel where users edit design settings"
thumb:
  url: "/projects/spacecraft/spacecraft-thumb.jpg"
  alt: "Thumbnail displaying Spacecraft logo. A serif S surrounded by circling rockets"
date: "1/1/2017"
---

Update: Spacecraft is now [Marketing 360](https://www.madwire.com/blog-news-updates/madwire-acquires-spacecraft-to-bring-powerful-website-building-technology-to-their-smb-platform)

## Background

Spacecraft is a robust CMS that helps small to medium sized businesses easily create a maintain their websites. At the time of writing, you can throw a rock anywhere in downtown Austin, and it'll hit a business that uses it.

## Responsibilities

The team was small, so my responsibilities were wide-ranging in terms of Front End Development. My main duty was Product Developer, adding to and refining the web app's WYSIWYG UI. I took part in spec-ing out and implementing new features, renovating the mobile navigation system (updating it with new options and adding lots of animations), creating a system for unit testing client side controls using Mocha, Chai, Karma, etc. I was also the point-of-contact for spec-ing out custom features for clients, where I worked closely with designers to quote and create what the client requested.

## Tech Stack

Vanilla JS, jQuery, Handlebar, SCSS, Github, Mocha, Chai, BrowserStack, Browserify, Babel

## Process

The beginning of any project usually starts with a conversation between either the CEO or CTO and myself. However I was also given a lot of freedom to investigate and advocate for important new features that should be added to the platform. From there I'd work in a local dev environment, hammer away at the UI, commit it to a staging evironment, and submit it for review.

## Accomplishments

- Add FE tests to entire component system using Mocha and Chai
- Refactored marketing email template with heavy emphasis on cross browser/device consistency. As we all know, emails have always been a beast to make consistent and this was no different. Email testing software can in handy here, allowing us to visually inspect dozens of different browsers and devices to ensure that things looked consistent.
- Refactor the entire mobile nav component to be performant and have a suite of animation options, all hardware accelerated for performance
- adding parallax option for background images in WYSIWYG editor
- adding skeleton loader animations to image galleries and card layouts
- Individial client feature: hero image one-offs
- Individual Client feature: interactive skyscraper map
