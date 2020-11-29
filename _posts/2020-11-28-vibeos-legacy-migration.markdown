---
layout: post
title:  "Announcement: vibeOS Legacy Transition"
date:   2020-11-28 19:39:00 -0800
categories: announcements
---

Today we are announcing that the vibeOS Development Team is working on a new version of vibeOS that is a complete, top-to-bottom rewrite of the
vibeOS Source Code. Some may have noticed this change, as the existing repository was renamed to `vibeos-legacy` during our transition to the
new vibeOS GitHub Orginization. The new repository location will be `vibeOS/vibeos-source` and will become public when me and Divide feel that
it is ready to release, as various core components such as a readme and unified document location, in addition to existing packages not yet being
ported to this new vibeOS. When the repository becomes public, we will make an announcement here and in the Discord.

## Why rewrite in the first place?

Well, as anyone who tried vibeOS will know, it was very unstable and prone to mamy bugs. In addition, it was written such that it's performance
suffered heavily on macOS and even on Linux. Simple actions could render it unusable and require a reload. We also discovered by about Public Beta 2
that we had kinda hit a brick wall when it came to incorporating large changes, such as a virtual filesystem. As such, it just sat there with minimal
effort being put into the project. Just based on what I have seen Divide do with the new vibeOS, we have already passed legacy vibeOS by leaps and
bounds. 

## Will it be easy to make apps for new vibeOS?

Yes! Divide has been working on creating a very simple way to create basic applications & experiences through XML. Creating applications will be as easy
as writing them, compiling and opening. Thorough documentation will be available soon with how to get started. Various applications included with new
vibeOS will be written in this version of XML, including OSDV, the Operating System Document Viewer.

## Q&A

| Question                                                  | Answer                                                                                                                                                                                                                                                             |
|-----------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Will applications from legacy vibeOS  work on new vibeOS? | No. The complete rewrite means any application from legacy vibeOS (Excluding WebViews) will not work.                                                                                                                                                              |
| How will WebViews be handled in the future?               | Divide has expressed his feelings that applications really should be written in the new XML format instead of using WebViews, as they don't work as well as native applications. Rest assured, WebViews WILL exist in new vibeOS, just in a more limited capacity. |
| When & where will documentation be available?             | Some documentation has already been written, and will be available here on vibeos.github.io when new vibeOS is made public. Getting started will be easy and we can't wait to see what will be made!                                                               |

## Closing

I am looking forward to presenting new vibeOS in the near future, and seeing how we can improve it and what can be done with it. I want to thank Divide
for pouring his hard work into making this possible. We are far from done, stay tuned.

Sincerely, ctaetcsh

Want to get in touch? Contact me via Discord! Add me: `ctaetcsh#8411` or [Join my Server](https://discord.gg/ArxQsnAEjF).