---
layout: post
title: "The Importance of Planning"
date: 2012-08-15 20:18
comments: true
categories: TECHNOLOGY  planning balsamiq trello pivotal tracker invision
author: Kshitij Sethi
published: true
---
<!--more-->
<h4>Every minute you spend planning saves 10 minutes in execution - Brian Tracy</h4>

It is often difficult to turn an idea into a project. 
Conceptually, I've been wanting to build a website for several years now; realistically, I haven't been working on it all that long. Getting from the point of conception to execution is a challenging task.


## Enter Planning ##

Planning out your project has several benefits. It helps you outline and focus on what you are trying to build.
Fleshing out an idea can also help you pitch it to prospective collaborators. Throughout this post I will discuss the planning process and also provide useful tools that might help you stay on track.

***The methods discussed within this post are heavily skewed towards the agile development methodology.***

At the planning stage, it is important to consider several factors that could heavily affect the outcome of your product.
When building my website I had to take the following 3 factors into account.

+ **Features:**
    + What should this website contain ? 
    + What features would be nice to implement ?
    + What features do I want first ?
+ **Design:** 
    + What will the website look like ?
    + How does it flow ?
    + What fonts/backgrounds should I use ?
+ **Tools:** 
    + What are some known blogging engines ? 
    + What tools allow for complete customization ?
    + Do I need Version Control ? A: YES 

In this post I will discuss the first two factors. For a detailed explanation of the development step watch out for my next post on Building a Static Site with [Octopress](http://www.octopress.org "Octopress") 

## The Feature Set ##

*** Iterate when necessary and always prioritize ***
  
Identifying the feature set was relatively easy for this project. I started out with the idea of a building a blog. Additionally I wanted a couple of pages to talk about myself and display my resume. I originally set out to create other pages to filter out specific posts which I would like to highlight (an example of this is a now defunct "TV" section). The need for these pages was made redundant by the use of tags and a generic categories page through Octopress. 

As with most projects, new features can often be added/removed. While I tried to minimize this in my first iteration, notable features that I came to consider later on were: a dedicated Twitter feed and social sharing for blog posts.

Since the feature set was relatively small and simple, I did not use any tools to track my progress throughout my project. I would however strongly recommend the use of a good feature/bug tracking tool. To date I have used [JIRA](http://www.atlassian.com/jira), [Pivotal Tracker](http://www.pivotaltracker.com) ,and [Trello](http://www.trello.com).
From these tools I would recommend Trello as a free solution, while I believe that Pivotal Tracker is a better solution. With a feature/bug tracker you will be able to monitor all the tasks you need to complete for your project. You can also provide time constraints for your tasks if you need to meet specific milestones. With an effective tracking tool, the overall organization and management of your project should improve.


## The Design Process ##

***Design is hard, specially if you can't draw ... and have limited Photoshop skills***

<img src="/images/mocks/about.png" class="right" width="300" title="About Page Mockup">
Before I started building this website, I spent some time desiging what it would look like. At this point, I was more focused on the positioning of objects on the web page. Effects and Transitions were considered during the development process. The design of the website was iterated on several times and will likely continue to evolve.

The initial design of this website was done using a tool called [Balsamiq Mockups](http://www.balsamiq.com/products/mockups).I have worked with the tool on several occasions and would highly recommend it. The application is extremely simple to use and you can generate quite detailed mocks within about 20 minutes. The drag and drop nature of the application allows users to create mocks quickly and efficiently.

<img src="/images/mocks/blog.png" class="left" width="300" title="Blog Page Mockup">

Balsamiq supports mocks for both web and mobile applications (iPhone frame). It also contains most commonly used application objects (buttons, labels, menus, images etc). The ability to mockup my website before development allowed me to spend time playing with several design possiblities. Additionally Balsamiq can generate PNG files for all the mocks within the collection or group them within one PDF file.   

While working on other projects, I've had the chance to use [InVision](http://invisionapp.com) to prototype some designs. The ability to share your mocks with others a critical feature InVision provides. Another useful feature is the ability to create 'hot spots' within specific mocks which lead the user to the other screens of the application. This helps display the flow of the application. 

Special Thanks to [cktaylor](http://www.cktaylor.ca) for helping me with some of the challenges I faced during this project.

Watch out for my next post on Octopress.

<br>
