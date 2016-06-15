---
title: "App Design Documents"
slug: app-design-documents
---

A _App Design Document_ (ADD) is meant to detail the objective, mechanics, level design, technical requirements, and development milestones for your app. It is a _living document_. You should be consistently updating your design document throughout development. If you are not updating your design document at least twice a week, then you are falling behind!

Having a completed design document makes it much easier to visualize your progress throughout development and keep track of what you have accomplished. It will help you make the correct decisions if you need to cut features because you are behind schedule or add features because you are ahead of schedule. Whenever you decide to change some aspect of your app's design or development schedule, make sure to update your design document!

# Your first App Design Document

To get started, we will be writing a App Design Document for one of the tutorial apps!

> [action]
> Choose one of the tutorial apps you have completed -- as a reminder, they are:
>
1. Tip Calculator
1. Notes
1. Makestagram
>
Try and choose a app similar to the one you want to make yourself! If you want to make a utility app, choose Tip Calculator. If you want to make offline app that stores data, choose Notes. If your app will leverage Parse or other APIs, choose Makestagram.
>
> Log into [GitHub](http://github.com) and create a new repository titled after the demo app. You can use your completed app repository if you have been using git/SourceTree/GitHub already!
>
> When viewing the new repository, there will be a link in the top bar that says "Wiki". Click on that and create a new page titled "App Design Document"
>
> Copy and paste this into the new page:
>
```
## Table of Contents
  * [App Design](#app-design)
    * [Objective](#objective)
    * [Audience](#audience)
    * [Experience](#experience)
  * [Technical](#technical)
    * [Screens](#Screens)
    * [External services](#external-services)
    * [Views, View Controllers, and other Classes](#Views-View-Controllers-and-other-Classes)
  * [MVP Milestones](#mvp-milestones)
    * [Week 1](#week-1)
    * [Week 2](#week-2)
    * [Week 3](#week-3)
    * [Week 4](#week-4)
    * [Week 5](#week-5)
    * [Week 6](#week-6)
>
---
>
### App Design
>
#### Objective
[explain the goal of the app]
>
#### Audience
[who is this app targeting?]
>
#### Experience
[how will your users interact with this app?]
>
[Back to top ^](#)
>
---
>
### Technical
>
#### Screens
* [list the different screens used in the app]
>
#### External services
* [list which APIs or external services will your app use?]
>
#### Views, View Controllers, and other Classes
* Views
  * [list all views you will need]
* View Controllers
  * [list all view controllers you will need]
* Other Classes
  * [list any other classes you will need]
>
#### Data models
* [list all Parse data models your app will need]
>
[Back to top ^](#)
>
---
>
### MVP Milestones
[The overall milestones of first usable build, core features, and polish are just suggestions, plan to finish earlier if possible. The last 20% of work tends to take about as much time as the first 80% so do not slack off on your milestones!]
>
#### Week 1
_planing your app_
* [goals for the week]
>
#### Week 2
_finishing a usable build_
* [goals for the week, should be finishing a usable app]
>
#### Week 3
* [goals for the week]
>
#### Week 4
* [goals for the week, should be finishing all core features]
>
#### Week 5
_starting the polish_
* [goals for the week]
>
#### Week 6
_submitting to the App Store_
* [goals for the week, should be finishing the polish -- demo day on Saturday!]
>
[Back to top ^](#)
```

Time to start writing your app design document!

# App Design

## Objective

Explain your app in 2-3 sentences.

## Audience

This is where you explain what kind of people your app is targeting. What age range, interests, background, etc... characterize the users you expect? How much time and disposable income does this audience have? In what circumstances during the day will they use your app?

## Experience

Start by describing, almost like you are telling a story, how a typical user will interact with your app. Why will they choose to open it, what will they do when it is open, what is the benefit or outcome of using it, and what should they feel when using it?

Next list apps you think have a similar look and feel to what you want for your app. Refer back to them for inspiration on how to make interacting with your app consistent and rewarding.

# Technical

## Screens

Describe each screen in your app and how you get from one to the other. Are there any screens you could remove from your MVP?

As you paper prototype your app and progress through iterations, be sure to add pictures and screenshots here!

## External Services

What APIs or external services will you use when making your app? List them and any alternatives you may need to check out here.

## Views, View Controllers, and other Classes

List all Views, View Controllers, and other Swift classes you will need to make you app. Describe the flow through them and purpose of each

## Data models

List all Parse data models your app will require.

# Minimum Viable Product Milestones

This is the section that should get updated the most often. You will be keeping track of what tasks you plan on completing each week. If you're new to projects this long, you will have to make best guesses as to how long things will take.

Before ordering your tasks on a week by week basis, first list every task on your plate. This should include everything you've listed in your app design document that will be in your MVP and all the non-technical work your app requires.

For every task, estimate how many days it will take. If you think it will take less than a day, round up to a day.

Add all the days together. Multiply by 1.2 to give yourself buffer time for unexpected delays. If you end up with more than 25 days of estimated tasks, do not change your estimates. Unless you have significant experience with large projects you should almost never change your estimates to be more optimistic. It is a big red flag if your gut tells you a task will take N days but after thinking about it you decide it won't take as long. You're almost always wrong.

If you have more than 25 days of work left, cut features. If it doesn't hurt, you aren't cutting enough features.

Revise your design document if necessary if you end up making significant changes to your app's design.

Only once you have a list of tasks that fit in 25 days should you start dividing them up week by week.

# Wrapping Up

Read your design document over to make sure everything makes sense. Check dependencies -- tasks should be in order of completion!

Edit as necessary. Ready to create one for your actual app?