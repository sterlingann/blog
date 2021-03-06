---
title: PhoneGap, Cordova, and what’s in a name?
date: 2012-03-19 21:32:42 Z
categories:
- app
tags:
- Insight
author: Brian LeRoux
status: publish
type: post
format: html
featured: true
redirect_from:
- "/2012/03/19/phonegap-cordova-and-whate28099s-in-a-name/"
---

There has been some confusion in the PhoneGap community and to complement Simeon Bateman’s recent [blog post,](http://www.simb.net/2012/03/19/phonegap-vs-callback-vs-cordova/) I want to make sure that everyone understands the entire story behind the PhoneGap name and how it relates to Apache Cordova.

Late last year, Adobe/Nitobi donated the PhoneGap codebase to the Apache Software Foundation (ASF) for incubation. We wanted to ensure proper stewardship of the source of PhoneGap, and to maintain a transparent and open governance that was well documented and understood. We also wanted to make it easier for other large organizations to contribute. Many companies are not only comfortable with the Apache organization and license, but already have a CLA with Apache.

[![same same](/uploads/2012/03/pie.jpg)](/uploads/2012/03/pie.jpg)

As a result of the contribution, we were required to ensure that the intellectual property was unfettered by trademark ambiguity. This presented us with the hard requirement to rename PhoneGap in its open source form as a project incubating at Apache. The name we first choose was Apache Callback, which was dumb for a host of reasons and quickly the community renamed it to Cordova. While genesis stories of PhoneGap often vary with the teller, most committers can agree the project was born at Nitobi, when the office was on Cordova Street in Vancouver.

## What's the difference between Apache Cordova and PhoneGap?

PhoneGap is a distribution of Apache Cordova. You can think of Apache Cordova as the engine that powers PhoneGap, similar to how WebKit is the engine that powers Chrome or Safari. (Browser geeks, please allow me the affordance of this analogy and I’ll buy you a beer later.)

Over time, the PhoneGap distribution may contain additional tools that tie into other Adobe services, which would not be appropriate for an Apache project. For example, [PhoneGap Build](http://build.phonegap.com/) and [Adobe Shadow](http://labs.adobe.com/technologies/shadow/) together make a whole lot of strategic sense. PhoneGap will always remain free, open source software and will always be a free distribution of Apache Cordova.

Currently, the only difference is in the name of the download package and will remain so for some time.![Cordova Logo](http://incubator.apache.org/cordova/images/cordova_256.png)

## What is Apache Cordova to a PhoneGap developer? (i.e. someone who just wants to build apps)

As a developer building PhoneGap applications, nothing has changed. PhoneGap is still free, openly licensed, and the main focus of the PhoneGap team. If your goal is to build cross platform apps with HTML, JS and CSS then keep on using PhoneGap for everything you need. This isn’t to say the transition has been perfect. We messed up the last release by not correctly updating the documentation to reflect the name change which confused new users. Future releases will have checks in place to ensure our documentation has the correct references. If you happen to be reading this and nodding in frustration, I encourage you to use [http://docs.phonegap.com](http://docs.phonegap.com/) as the canonical source for edge documentation. If you want to help us keep this stuff on point, please read on.

## What is Apache Cordova to a PhoneGap contributor? (i.e. someone who wants to fix bugs, contribute code, add tests or write docs)

Apache Cordova is the destination for those interested in contributing to the open source project powering PhoneGap. This is where you go if you’re interested in improving the Apache Cordova codebase. It should be noted in today’s open source world: forking is a feature. Many distributions of Apache Cordova exist today and this is something we encourage wholeheartedly. For example, Salesforce and Facebook currently have customized versions for their SDKs and our work at Apache is focusing on enabling this use case (and beyond).

PhoneGap is an ambitious project that relies on a massive community to brute force many operating system implementations into the semblance of parity. We believe in a future of web technology unshackled from the sandbox, proprietary API’s and tooling. If you agree with our vision: then join us! [Getting started contributing](http://wiki.apache.org/cordova/ContributerWorkflow) is easy and a great way to build up your PhoneGap chops and reputation in the open web community.

Apache Cordova launched their [new home](http://incubator.apache.org/cordova) recently and you can find more information about the open source project there.
