---
layout: post
title:  "Thoughts on Secure coding training"
---
Because secure coding training is often conceived as a check-the-box compliance activity, it gets (under-)resourced accordingly and is typically implemented simply, and sometimes lazily, as videos + quizzes. While these can be high-quality, _what does the developer get out of it_? They certainly practice watching videos (often 8+ hours on average per year) and taking tests, which arguably has an unclear connection to increasing actual secure coding competency.

This is lamentable because I think a well-designed and well-implemented secure coding training program has the potential to be a real force multiplier in the context of modern DevSecOps and its platform engineering focus. _Can we figure out how to measure outcome and better position it for success_?

## The problem
So why does the technology world have a cybersecurity problem? If you believe that "software is eating the world", then perhaps much of the answer lies in how we develop software.

To the extent that an existing vulnerability is a security bug that was _unwittingly_ written into code by a developer, how many bugs can we prevent from being introduced by improving secure coding competency and awareness?

After all, if the well-meaning developer knows to (and how to) write secure code, under what circumstances would vulnerable code still be produced?

## DevSecOps
Perhaps the desired outcome is possible with some thoughtful combination of people, tooling, and process? 

At least that is the hypothesis I get to test daily as an Application Security engineer working in DevOps, where I try to help teams by implementing self-service infrastructure (i.e., platform engineering) that puts alert data into developer hands at "the right time", ideally in phase with their standard workflow and when newly written code is still fresh in mind (_bugs are cheaper to fix then_).

However, this "layer of defense" primarily leverages SAST (static application security testing) at the pull request, which is great for what it is, as a timely safety net to catch known security bugs that we can detect through static analysis of code, but are there meaningful things we can do earlier in the SDLC -- _especially to avoid writing the bug in first place_?

## Secure coding itself
Can it be learned? Can it be taught? _What happens when we place more emphasis on teaching and learning_?

After inheriting a "videos + quizzes" secure coding training program a few years ago and eventually re-designing and re-implementing it around a platform (with a seemingly agreeable way to measure secure coding competency) that provides high-quality hands-on labs and a "hack it first, then fix it" approach for developers, I have reason to be cautiously optimistic, maybe even naively excited about further possibilities.

This hypothesis is being tested in coordination with a fledgling security champions program right now. More on this later.

-- JW
