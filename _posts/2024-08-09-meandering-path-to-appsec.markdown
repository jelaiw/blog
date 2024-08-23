---
layout: post
title: "A short origin story"
---
How did I get into security? Certainly not the direct route, if there is such a thing.

## Getting a college degree
I tried to become a medical doctor first. It took two years before I figured out that I wouldn't be a good one. By then, all of my pre-med requirements were completed, but a sunk cost is a sunk cost. A bit more thoughtfully, I changed my major to Computer Science.

At the time CS students were required to choose a concentration, so I chose Computer Networking, where I discovered the unexpected joy of really digging into IETF RFCs [^1]. _Yes, joy or something close to it_, so naturally I implemented my own Internet Relay Chat client [^2] for fun, moderated a couple of IRC channels on EFnet [^3] in my spare time, and hung out with others there at the edge of a new and wild digital frontier. Then the internet became important, so it seems to have worked out.

When I wasn't tinkering with network protocols, I also worked part-time for a gruff, no-nonsense system administrator named Bruce Williams, who ran IT for the Computer Science department. I got to build Windows NT servers, make CAT5 cables, and tinker with real life computer networks. There was no doubt that I would be a network admin or sysadmin after graduating. 

Whups!

## Going pro
Instead, I spent the first decade of my career as a software developer, starting with the roller coaster ride that was Y2K and the dot com boom. Back then, Java was James Gosling and Sun Microsystems (now defunct) and object-oriented programming (OOP) was the thing to learn, so I wrote mostly Java, learned how to refactor [^4], and tried to program pragmatically [^5]. I was even an early adopter of continuous integration [^6], presaging my later stint in DevOps.

Fittingly, I learned to care about design and the careful craftsmanship that went into good software engineering -- and to wonder about secure coding, planting seeds of curiousity that I would try to sow later.

I also started (and stopped) a one-person LLC. This was a side quest that ultimately turned out to be a sort of failed experiment, but I did learn about sales, business administration, and especially the power of the minimum viable product [^7].

Future me was now much better equipped to imagine what "security as a product" might look like, so when I became a card-carrying DevOps engineer, my eyes opened to how a platform (the product) designed to empower developers (the customers) could solve security problems.

_After a friendly shove forward from COVID_, I now get to work on security engineering full-time.

## Growing up
Looking back on my childhood, I suppose there were some clues and foreshadowing. As a Gen Xer, I grew up at a time when most households did not own a personal computer (PC). Then, somewhere in the middle, it seemed like everyone had one [^8].

Like many teenagers, I played video games. My early PC favorites were adventure-based, like [Space Quest](https://en.wikipedia.org/wiki/Space_Quest_I), [King's Quest](https://en.wikipedia.org/wiki/King%27s_Quest_I), [Police Quest](https://en.wikipedia.org/wiki/Police_Quest:_In_Pursuit_of_the_Death_Angel), and pretty much anything else from Sierra On-Line. Unlike most, I enjoyed defeating copy protection and spending time in a hex editor. 

![representative screenshot of buck rogers gameplay](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjdadxBWh2PA64UWy05e-utPX-p_nef0Baauf57rYfoA5xC0bqwiqawtfdKDXSsInp3JhsSmhtIir9uBaIN-j7Fq550-G97HYNwGx4zyWukJ5_ukCjAo6-QG6qdhKx1d_yLIe277QpBGGQ/s1600/start_129.png)

_Correspondingly, my characters in Buck Rogers (an early role-playing game) had conspicuously powerful items and unusually high character attributes. Credit for the screenshot (and the nostalgia) goes to [CRPG Addict](http://crpgaddict.blogspot.com/2020/08/buck-rogers-matrix-cubed-fourth-power.html)._

I remember visiting Waldenbooks (also now defunct) or the public library and heading straight for those treasured shelves to inhale the contents of every operating system book I could get my hands on. I was particularly obsessed with how passwords worked and how secrets were kept secret.

It would be twenty years before I really tried again to grok [^9] cryptography.

 -- JW

## Footnotes
[^1]: These [requests for comment](https://www.ietf.org/process/rfcs/) by the Internet Engineering Task Force can be daunting to read, but worthwhile if you want to really understand how the protocols work.
[^2]: Implementing IRC was a kind of nerdy rite of passage at that time. I have fond memories of diving into [the RFC for this protocol](https://www.rfc-editor.org/rfc/rfc1459).
[^3]: Cutting through some jargon here. IRC channel operators have the power to set topics, kick out unruly members, and otherwise moderate a channel. Spent the most time in `#linux` and `#java` on [EFnet](https://en.wikipedia.org/wiki/EFnet). Those were special days.
[^4]: Thanks to Martin Fowler and his _Refactoring_ book.
[^5]: With much owed to Josh Bloch for writing _Effective Java_ and to Andy Hunt and Dave Thomas for _The Pragmatic Programmer_.
[^6]: Implemented Hudson (now Jenkins) while contemplating the proper placement of red/green lava lamps for indicating build status. [https://www.artima.com/weblogs/viewpost.jsp?thread=67492](https://www.artima.com/weblogs/viewpost.jsp?thread=67492).
[^7]: [https://en.wikipedia.org/wiki/Minimum_viable_product](https://en.wikipedia.org/wiki/Minimum_viable_product).
[^8]: Ours was an [IBM PS/2](https://en.wikipedia.org/wiki/IBM_PS/2).
[^9]: Yes, [grok is a real word](https://en.wikipedia.org/wiki/Grok). Amusingly, I find myself explaining this a few times every year.

[bruce-staff-page]: https://web.archive.org/web/19980111100717/http://www.cis.uab.edu/info/staff/gbw/will.html
