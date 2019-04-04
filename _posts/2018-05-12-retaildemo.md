---
layout: post
current: post
cover: assets/images/frd/cover.jpg
navigation: True
title: Focals Retail Demo
date: 2019-03-25 10:00:00
tags: [Mobile Engineering, IxD]
class: post-template
subclass: 'post'
author: ghost
type: Case Study
description: A demo experience on Focals smart-glasses to showcase features of the product to potential customers.
---
{{ page.description }}

![Image](assets/images/frd/cover.jpg#full)

<span class="project-intro">
**Timeline:** Summer 2018<br />
**Organization** <a href="https://www.bynorth.com/" target="external">North Inc.</a><br />
**Team:** Software Prototyping<br />
**Type:** Interaction Design, UI/UX, Mobile Engineering<br />
**Tools and Technologies:** C++, Qt, Java, Kotlin, Android, Sketch<br />
</span>

<div class="full-width">
  <div class="wrap">Due to the confidentiality of this work, some sections are omitted and focused solely on the design and implementation process.</div>
</div>

## Motivation
### To Give a Killer Product Demo
Focals are custom-built smart glasses with a display only the wearer can see. The Retail Team members often find it challenging when running product demos as they are unable to see what is visible to the user. If the user asks a question during a demo or has trouble interacting with the device, without knowing exactly what is visible to the user, it is difficult to provide a solution. Taking the user through scenarios is imperative to demonstrate different product features.

### My Role
I led the design and implementation of the initial version of the demo feature.
I was also responsible for handling the transition of the project to the Production Engineering team once the feature was complete.

## User Centered Design Process
### Figuring out the must haves
We started our design process by talking to users and direct stakeholders of the project. In this case our **users** were Retail Team members and facilitators of product demonstrations. These discussions helped us uncover the core needs of our users. We then prioritized the requirements and identified the must have features to conduct a successful demo session.

> Generative user research helped us uncover the core needs of demo facilitators and prioritize requirements.

## Our Goal
- Provide a system to demonstrate different features of Focals by triggering custom messages, calendar events, and notifications.
- Provide demonstrators with the ability to easily start product demonstrations, stop an active session and move on to a new demo when necessary.
- Provide a solution that mirrors what the user sees on their glasses.

![Image](assets/images/frd/user_flow_00.jpg#full)

## The User Flow
After defining the problem and identifying key features, I started designing the user flow. The user flow helped us clearly identify the different screens that the user would find and the steps that the user would take, which was then later converted into development tasks.

{% include image.html url="assets/images/frd/user_flow_01.jpg" description="" %}

{% include image.html url="assets/images/frd/user_flow_02.png" description="The initial user flow design created on a whiteboard with sticky notes was then converted into a final design in Sketch." %}

## Implementation
### Mirror Mirror On The Phone
The solution was implemented using Kotlin and Java on Android and integrated to the Focals Companion App. This feature was only available to Retail Team members to support their product demonstration sessions.

A Screen Cast solution was provided to mirror the display of the glasses on the facilitator's mobile phone. A user interface was provided to trigger custom messages and notifications to assist the demo session.

> A Screen Cast solution was provided to mirror the display of the glasses on the facilitator's mobile phone.

![Image](assets/images/frd/screens.png)

## Reflection & Takeaways
Product demo **facilitators** were the **users** of this project. This feature allowed the facilitator to follow the actions of the person who was participating in the demo by seeing exactly what was supposed to be projected on the glasses. This helped the facilitator to effectively present different product features and to conduct multiple demos per day. Using this feature provided great first impressions to potential users, investors, and influencers.

Throughout this project, I worked closely with all stakeholders to ensure that a feature complete minimum viable product was delivered on schedule. Working with a multidisciplinary team encouraged me to find opportunities to empathize with my team members and develop skills to identify different thought processes to address any potential confusions. I also developed my skills on leadership and project management.

> Weekly reviews with stakeholders ensured that we were "building the right thing".

Since no primary QA resources were allocated to this project, the team tested each other's development work. This process encouraged the development team to test as they code, which was highly effective and resulted in high quality deliverables with little to no issues.

It was imperative to keep the original behavior and interactions of the product intact. Building a product demonstration feature on top of the existing platform was challenging and this was overcome by continued collaboration with Production Teams.

Prioritizing requirements and identifying the must-have-features paved the way for timely delivery of the project. We also had weekly reviews with stakeholders to ensure that we were "building the right thing".

From lessons learned, I would conduct follow-up interviews with demo facilitators to learn their experiences after using the feature for sometime. I believe having opportunities in a real-world situation attending demo sessions with potential users, will provide a better understanding of user needs during the early stages of the design process.
