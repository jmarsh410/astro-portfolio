---
layout: "../../Layouts/WorkLayout.astro"
title: "The Zebra"
tags: ["javascript", "dev", "html", "css"]
image:
  url: "/projects/the-zebra/zebra-homepage-small.jpeg"
  alt: "The Zebra homepage"
# note: "Note: I worked on a LOT of projects at The Zebra over 8 years, so I've broken the larger ones out to their own pages. This page serves as a more general overview."
---

## Background

The Zebra helps users find and compare car insurance quotes. Users go through a series of questions required by car insurance companies, and then are shown a list of results for different companies. Depending on the experience, the users can also potentially bind their policy through an agent or entirely online.

## Responsibilities

My time at The Zebra was split between feature development for the suite of web apps, all isomorphic and performing SSR, and working on improving the front end tech stack and developer experience as a whole.

## Tech Stack

React, Next, Typescript, Node, Storybook, SCSS, MockServer, Optimizely, Eppo, Gitlab

## Process

Teams at The Zebra consisted of a PM, EM, FE devs, BE devs, Designer, and a QA. Once a feature was decided on, I'd work together with the PM and Designer to identify any red flags or callouts, resolve those if they existed, and then locally develop the feature. Once in a ready state, I'd commit the feature branch to an ephemeral environment, heavily test it along with the QA, and then merge and deploy the feature once the QA gave the signoff and all the automated tests passed for the branch.
Outside of individual feature development, I helped run the Frontend Guild, driving architecture, performance, and accessibility discussions for the company. Once an initiative was decided on, I'd create docs and a project plan for the initiative, assigning work to myself and others to help complete it.

## Important Features

- Made the Results page responsive, reducing need for mobile specific web app. Halved feature development time, improved devX, made experience more consistent for users.
- Refactored rate request logic for results page, leading to 75% reduction of cost for vendors and faster page load speed.
- Saved Front end devs hours per week by removing reliance on local BE apps for local development
- Swapped out unneeded A/B client side script with server side coin flipper. Reduced client side bundle size by 10% and sped up initial request timing by 33%
- Implemented performance strategy and monitoring to entirety of company's suite of web apps. Establishing base line metrics for the company.
- Revamped Front End Interview Process to be more equitable and inclusive
