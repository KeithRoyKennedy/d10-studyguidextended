# Drupal Certification Study Guide

Notes based on the [Acquia Certified Drupal Specialist Developer Study Guide]([https://acquia-academy.gitbooks.io/study-guide-acquia-certified-drupal-8-developer/content/study-guide.html](https://docs.acquia.com/acquia-academy/study-guides/d10-backend-specialist)) and other resources. a Fork of [WidgetsBurritos D8 Study Guide](https://github.com/WidgetsBurritos/d8-studyguide) this fork aims to Update the info to Latest Drupal Standards and remove menstions of Depreciations. To prepare you for the most recent Drupal Certification exams;


**Update: May 31, 2023:**
I passed my https://dev.acquia.com/person/community/keith-kennedy drupal 10 Backend Certification using this guide.

# From the Original Creator 
For the record, I officially passed my exam on 4/24/2017 at DrupalCon Baltimore.

Feel free to open PRs, adding new info and correcting any mistakes you may find.

It is highly recommended that you also read the [Drupal 8 User Guide](https://www.drupal.org/docs/user_guide/en/index.html) as much of the site building section (including the missing notes in this repo) covers what is in the user guide. * Note the Link will direct to the latest Drupal User Guide at the time of this Writing its version 11

**Update: 4/2/2018:**
I'm presently studying for both the *Front End Specialist* and *Back End Specialist* exams and have started updating the documentation to go a bit more in depth on certain topics. The material is all still relevant for the general developer exam, but may be a little more detailed than you need. Either way, I feel like it's important information to know regardless of whether or not it is asked on the certification exam.

**Update: 4/9/2018:**
I've successfully completed both the front end and back end exams. As to avoid giving anything specific away, I will say this study guide does have pretty decent coverage for both, but there are a few things missing. 

On the front end, it's a bit important to familiarize yourself with some of the newer aspects of HTML5 if you came from a XHTML background. I'll also say just knowing about the breakpoint module isn't enough from a performance perspective. Also, it helps to know some of the more advanced features in Twig, even if you don't use them every day. I highly recommend reading [The Drupal 8 Theming Guide](https://www.drupal.org/docs/develop/theming-drupal). It is a rather helpful resource and definitely proved to be beneficial to me. 

On the backend, the best thing you can do is just build a module or two. We could add all kinds of things to the study guide, but nothing beats actual experience here. I'd also emphasize knowing the differences between plugins and services, and different ways you might validate and sanitize user input in a variety of contexts.

---
**PRs Welcome!**

*Disclaimer: This is not officially related to the Acquia certification process. These notes are just based on what I thought was important while I studied. Your results may vary.*

### Study Guide Success Stories
- [David Porter](https://certification.acquia.com/user/1978) - Passed exam 2017-04-21
- [David Stinemetze](https://certification.acquia.com/user/4414) - Passed exam 2017-04-24, Backend + Frontend exams 2018-04-09
- [Jonathon Thompson](https://certification.acquia.com/user/2580) - Passed exam 2017-04-27
- [Tyler Fahey](https://certification.acquia.com/user/4647) - Passed exam 2017-07-03
- [Adrianna Flores](https://certification.acquia.com/user/4694) - Passed exam 2017-08-12
- [Kimberly Kubali](https://certification.acquia.com/user/1306) - Passed exam 2017-09-26
- [Francesco Tuzzolino (Boes)](https://certification.acquia.com/user/5647) - Passed exam 2018-03-31
- [Keith Bremner](https://certification.acquia.com/user/2268) - Passed exam 2018-03-31
- [Bill Renk](https://certification.acquia.com/user/6073) - Passed exam 2018-07-13
- [Mehul Shah](https://certification.acquia.com/user/6342) - Passed exam 2018-10-01
- [Tom Metcalfe](https://certification.acquia.com/user/5954) - Grand Master 2018-12-09
- [Mouhammed Diop](https://certification.acquia.com/user/375) - Passed exam 2018-12-20
- [David Disch](https://certification.acquia.com/user/5923) - Passed exam 2018-12-21
- [Bruce Yuen](https://certification.acquia.com/user/5375) - Passed exam 2018-12-26
- [Sushil kumar](https://certification.acquia.com/user/6724) - Passed exam 2019-01-21
- [Avi Schwab](https://certification.acquia.com/user/6900) - Passed exam 2019-04-11
- [Nishant kumar](https://certification.acquia.com/user/4349) Passed exam 2019-08-03
- [Suraj Kumar paul](https://certification.acquia.com/user/261) - Passed exam 2019-08-07
- [Ravi Kumawat](https://certification.acquia.com/user/7453) - Passed exam 2019-08-21
- [Kristiyan Nikolov](https://certification.acquia.com/user/7273) - Passed exam 2019-08-30
- [Hemant Joshi](https://certification.acquia.com/user/7759) - Passed exam 2019-09-29
- [Brian Gallagher](https://certification.acquia.com/user/4543) - Passed exam 2019-10-01
- [Sandeep Kumar Gupta](https://certification.acquia.com/user/7159) - Passed exam 2019-10-13
- [Amol Bhandari](https://certification.acquia.com/user/3264) - Passed exam 2019-11-24
- [Vicky Nandode](https://certification.acquia.com/user/7955) - Passed exam 2019-11-30
- [Mohammed Abdullah Bamlhes](https://certification.acquia.com/user/5223) - Passed exam 2020-04-22
- [Abdulaziz Abbas](https://certification.acquia.com/user/5185) - Passed exam 2020-05-30
- [Keith Kennedy](https://dev.acquia.com/person/community/keith-kennedy) - Passed exam 2023-08-31

---

[1. Fundamental Web Development Concepts](1-fundamentals)
  - [1.1 - HTML/CSS](1-fundamentals/1.1-html-css.md)
  - [1.2 - Javascript/jQuery](1-fundamentals/1.2-javascript-jquery.md)
  - [1.3 - git](1-fundamentals/1.3-git.md)

[2. Site Building](2-site-building)
  - [2.1 - Content Types](2-site-building/2.1-content-types.md)
  - [2.2 - Display Modes](2-site-building/2.2-display-modes.md)
  - [2.3 - Taxonomies](2-site-building/2.3-taxonomies.md)
  - [2.4 - Blocks](2-site-building/2.4-blocks.md)
  - [2.5 - Menus](2-site-building/2.5-menus.md)
  - [2.6 - Views](2-site-building/2.6-views.md)
  - [2.7 - Configuration Management](2-site-building/2.7-configuration-management.md)
  - [2.8 - Multilingual](2-site-building/2.8-multilingual.md)
  - [2.9 - Web Services](2-site-building/2.9-web-services.md)

[3. Front End Development (Theming)](3-front-end-development)
  - [3.1 - Creating Themes and Subthemes](3-front-end-development/3.1-creating-themes.md)
  - [3.2 - Theming Concepts](3-front-end-development/3.2-theming-concepts.md)
  - [3.3 - Twig Syntax](3-front-end-development/3.3-twig-syntax.md)
  - [3.4 - Overriding Twig Templates](3-front-end-development/3.4-twig-templates.md)
  - [3.5 - Preprocessors](3-front-end-development/3.5-preprocessors.md)

[4. Back End Development (Coding)](4-back-end-development)
  - [4.1 - Object-Oriented Programming](4-back-end-development/4.1-oop.md)
  - [4.2 - Custom Modules](4-back-end-development/4.2-custom-modules.md)
  - [4.3 - Data Storage](4-back-end-development/4.3-data-storage.md)
  - [4.4 - Essential APIs](4-back-end-development/4.4-essential-apis.md)
  - [4.5 - Coding Standards](4-back-end-development/4.5-coding-standards.md)
  - [4.6 - Performance](4-back-end-development/4.6-performance.md)
  - [4.7 - Security](4-back-end-development/4.7-security.md)

---

##### [Next Page >>](1-fundamentals/README.md)
