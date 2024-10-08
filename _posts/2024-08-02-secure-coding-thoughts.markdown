---
layout: post
title:  "Thoughts on secure coding training"
---
"_We don’t have a cybersecurity problem. We have a software quality problem_" -- Jen Easterly

UPDATE: After BlackHat last week, Chris Hughes blogged beautifully about [Software's Iron Triangle](https://www.resilientcyber.io/p/softwares-iron-triangle-cheap-fast). I purposefully write more narrowly about secure coding training in this post, but would be remiss not to point out Mr. Hughes' excellent and related work.

[![software transparency book cover](https://www.wiley.com/storefront-pdp-assets/_next/image?url=https%3A%2F%2Fmedia.wiley.com%2Fproduct_data%2FcoverImage300%2F83%2F13941584%2F1394158483.jpg&w=640&q=75){: width="220"}](https://www.wiley.com/en-us/Software+Transparency%3A+Supply+Chain+Security+in+an+Era+of+a+Software-Driven+Society-p-9781394158485)

Original post below.

## Video and quizzes only
Because secure coding training is often conceived as a check-the-box compliance activity, it gets resourced accordingly and lightly implemented. _So what can a developer realistically get out of a videos & quizzes-only approach_? 

They certainly practice watching videos and taking tests, but it is unclear how well this activity corresponds to increased secure coding competency. Arguably, developers are practicing the wrong thing.

Perhaps we should consider whether a more thoughtfully designed secure coding training program has some untapped potential, especially in the context of modern DevSecOps with its platform engineering focus.

## The problem in a nutshell
So why does the technology world have a cybersecurity problem? If you believe that "software is eating the world", then perhaps much of the answer lies in how we develop software.

To the extent that an existing vulnerability is a security bug that was _unwittingly_ written into code by a developer, how many bugs can we prevent from being introduced by improving secure coding competency and awareness?

After all, if the well-meaning developer knows to (and how to) write secure code, under what circumstances would vulnerable code still be produced?

## Relative positioning in the SDLC
As an Application Security engineer working in DevOps, I try to help teams by implementing self-service infrastructure (i.e., platform engineering) that puts alert data into developer hands at "the right time", ideally in phase with their standard workflow and when newly written code is still fresh in mind (_bugs are cheaper to fix then_).

This "layer of defense" primarily leverages SAST (static application security testing) at the pull request, which is great for what it is, as a timely safety net to catch known security bugs that we can detect through static analysis of code, but are there meaningful things we can do earlier in the SDLC -- _especially to avoid writing the bug in first place_?

## The experiment
Can secure coding be learned? Can it be taught? _What happens when we appropriately resource and incentivize developer training_?

Some gentle readers may know that I inherited a "videos + quizzes" secure coding training program (a good one for what it was) a few years ago and re-designed and re-implemented it this past year around an innovative new platform called SecureFlag, which provides high-quality hands-on labs, a "hack it first, then fix it" approach for developers, and a way to measure and score secure coding competency.

Based on pilot results so far, I have reason to be cautiously optimistic, maybe even naively excited about further possibilities and better positioning our developers for success.

-- JW
