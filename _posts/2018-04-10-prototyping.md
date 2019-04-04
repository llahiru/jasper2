---
layout: post
current: post
cover: assets/images/frd/north_pty_cover.jpg
navigation: True
title: Prototyping The Future of Smart Glasses
date: 2018-04-10 10:00:00
tags: [Smart-glasses, Mobile, UX, Prototyping]
class: post-template
subclass: 'project'
author: ghost
type: Project
description: Prototypes and early features built for Focals Smart Glasses at North Inc. Including Amazon Alexa integration, Speech to Text, and Screenshot Share.
---
{{ page.description }}

![Image](assets/images/frd/north_pty_cover.jpg#full)

<span class="project-intro">
**Timeline:** Winter 2017 to Present<br />
**Organization** <a href="https://www.bynorth.com/" target="external">North Inc.</a><br />
**Team:** Software Prototyping<br />
**Type:** Prototyping, Mobile Engineering, Interaction Design, UI/UX<br />
**Technologies:** C++, Qt, C, Swift, Kotlin, Java, iOS, Android, React<br />
</span>

<div class="full-width">
  <div class="wrap">I have worked on a number of prototypes and early concepts for smart-glasses at North. Due to confidentiality, some of the work cannot be published. Below are some examples of my work at North that are now available in the final product.</div>
</div>

## Screenshot Share
This feature allows users to share what they see on Focals with their contacts or on their social media networks. Users can add a personal touch and snap a photo with their smartphone camera as a screenshot background.

### Motivation
There was no quick and easy way for users to share what they are seeing on their glasses. We assumed that providing a quick and easy way to share screenshots would be valuable for the following reasons:

- Allows users to share their excitement about product use cases, which is fun for the user and beneficial for our marketing efforts
- Allows users to better communicate frustrations over product features that fail to live up to expectations so that we can improve the product

### Our Goals
- Allow the user to press a button in Focals Companion mobile app to take a screenshot
- Allow the user to select from multiple background images to make the screenshot more interesting
- Make the final composition sharable directly from the mobile app

### Challenges
- Limited ability to overload existing input methods to ensure fast and easy screenshot captures
- Creating an appealing screenshot with a background image
- Overlay a screenshot on any background such that the screenshot is clearly legible

![Image](assets/images/frd/user_flow_ss.jpg)

### Initial User Feedback
We conduced multiple demos for selected groups of internal users and gathered their feedback on the first iteration (a low-fidelity prototype) of the feature.

All participants preferred the ability to share what they see on Focals as a screenshot. Users mentioned that they would use screenshots to share the moments they experience on Focals. As a result of our findings this feature was graduated from a prototype to a feature in the final product.

{% include image.html url="assets/images/frd/screenshot_share.png" description="Screenshot Share feature is now available on Focals Companion App as part of the final product" %}

## Alexa
I was part of the design and implementation team of the very first integration of Alexa on Focals smart-glasses. My role was to develop the initial interaction and software to connect Focals with Amazon Alexa services.

{% include image.html url="assets/images/frd/alexa_pty.png" description="User flow and screens of the initial integration of Amazon Alexa on Focals." %}

Now, Focals come with Alexa built-in. Users can ask Alexa to play music, hear the news, see the weather, and control their smart home and more.

## Speech to Text
I designed and implemented the very first version of Speech to Text feature on Focals smart-glasses. This initial implementation helped us test transcription accuracy and audio capture capabilities on Focals by conducting experiments and user studies. Speech to Text feature is now used in the final product as one of the main user input methods.

{% include image.html url="assets/images/frd/vtt.png" description="Speech to Text is used as a method of input on Focals when composing a message." %}
