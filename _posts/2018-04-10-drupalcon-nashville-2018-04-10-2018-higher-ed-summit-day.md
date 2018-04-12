---
title: DrupalCon Nashville 2018 -- 04-10-2018 Tuesday
comments: true
date: 2018-04-10 08:57 -0500
toc: true
toc_label: "Session quick links"
toc_icon: "cog"
---

## Dries Keynote

### Back to roots
* User facing changes addressing poor experience for new users installing Drupal
* CMI changes, composer changes, removing it as a requirement, but make it a best practice, longer period between updates
* Improving non-technical perception of Drupal

## Vendor visits

* **Pantheon** 
    * After several failed starts, I met with a chief-something or other, which led to a discussion with Josh Koenig, Co-founder, and John Sepassi, Platform Sales Rep. We discussed our multi-site workflow and some advantages with the Pantheon workflow. This includes full use of a CDN and performance analysis tools.
* **Kanopi Studios** -- an agency that helps with website builds
* **Kwall** -- an agency that helps with website builds

## [Horizontal DevOps ~ Scale your team and tools across projects.](https://events.drupal.org/nashville2018/sessions/horizontal-devops)

* We often think of DevOps in a super siloed context (eg one project at a time), but having an organizational DevOps plan/strategy and some cross project standardization is really how you benefit. This talk is about the business value of horizontal DevOps across people and projects.
  * This makes sense for groups with varying hosting and stack configuration requirements
  * Circle CI dependency

### I like these guidances 
* Use Semantic versioning
* Package managers for distros
* Keep documentation current
* Define or share your release workflow for every tool


## [Getting closer to your customer: Using Drupal in the last mile](https://events.drupal.org/node/20838)

* How to better align the back and front end of development
* Using the tour module to provide user tips to sites
* Low value for us, given our distribution and support model, but smart for bespoke site design

## [Integration of Drupal Coding standards with Git hooks](Integration of Drupal Coding standards with Git hooks)

* Using for running standard checks when committing code 
* Client and Server side hooks
  * Client
    * pre-commit
    * Prepare-commit-msg
    * commit-msg
    * post-commit
    * post-checkout
    * Pre-rebase
    * post-merge
  * Server
    * Pre-receive
    * Update
    * Post-receive
  * Demo shows a simple PHP code linting before committing 

## [Power up Drupal 8 with integrations: Cornell University showcase](https://events.drupal.org/nashville2018/sessions/power-drupal-8-integrations-cornell-university-showcase)

* With ambitious goals and an aggressive timeline, IT@Cornell architected and built a centralized repository for discovering and applying to educational and extra-curricular opportunities. By leveraging the strongest traits of each platform, we delivered a multifaceted solution that uses Drupal 8 as the front end, Salesforce as a backend, and other technologies as data feeds for the information displayed to the end users.
