---
title: Weekly Round Up - 2019Q4 Week the Second
date: '2019-10-20'
tags:
  - Weekly checkin
  - Reflection
  - Motivation
---

## How did it go?
A little less energised, a little more stressed, but it still went pretty well. I forgot to really use my timers as much as I should have, and a few things slipped a little out of prioritising some time critical projects. I want to try and work around that better this week.

## Did you do the things?
- Upskilling: Very much so. I kept a better log of it as well.
- Practice & Writing: Between writing my notes, working on these posts, and a bit of playing with Eleventy I just about his this I think.
- Music: Still no instrumental but an absolute boatload of recording. Feeling pretty confident about that "Release 3 things" 4-week target.
- Tidying, filing, email: Not quite as much of a frenzy as last week but pretty good, kept on top of things. Keeping my inbox sane is starting to feel like an actual habit now.
- Personal work: Not quite as much as I'd like to be honest, I meant to do 2 pomodoros worth of working on my personal site but work got in the way.

## What did you read/watch/listen to? What did you learn?
I kept more detailed notes this time, which are definitely not a substitute for going and checking out any of these yourself, but here's some things that stuck out to me.

- [Shoptalk Show: Jen Simmons on Browser Features](https://shoptalkshow.com/episodes/382/).
 	- Lots about how the CSS working group, well, works. One key point is if there's a killer feature you wish existed, post about it with use cases rather than your ideas for the solution: working groups need use cases more than answers. Also, we're about to get some neat aspect ratio stuff that will rely on inline images having height/width set in order to work things out, so go put those things back into your code if you habitually strip them out.
- [Andy Bell: Keeping it Simple with CSS that Scales](https://www.youtube.com/watch?v=Apm52q3xPkk).
	- I read an article version of this while I was on holiday a few weeks back but this talk is great and validated a lot of my feelings around CSS-in-JS, in that it seems like sometimes it is a case of developers trying to over-engineer their way out of just talking to people.  Like Andy says, Soft Skills are badly named, they're essential to working with other humans. Considering so many of our ethical and accessibility problems have "we didn't actually talk to people" at their core, maybe it's time we really stop entertaining these avoidant practices so much. Have conversations, have a system and document your decisions.
	- Even aside from that, we're throwing a lot of stuff down the wire that we don't need to. Developer Experience is important but it doesn't trump User Experience. CSS is not the incomprehensible mess we joke that it is, you just have to actually learn to use the things it's good at.
	- So much of what you find in CSS frameworks are unneeded now if you actually embrace progressive enhancement properly. A lot of our CSS could be so much simpler if we don't try and make everything the same everywhere. I'm not going to try and boil down [Every Layout](https://every-layout.dev/) because you should just read it, but CSS can be incredibly powerful and robust if we're willing to relinquish a little bit of control. On the flip side stuff like grid has made incredible art direction easier than it's ever been.
- [Bruce Lawson: How To Make Loveliness](https://www.youtube.com/watch?v=DWxrR3s4Krk)
	- A lot of this talk was about embracing the goodness that already exists in HTML providing we don't go in and break it by trying to recreate buttons out of divs and similar nonsense. Use the lowest powered thing that solves the task, leverage the awesome native stuff that already exists because it's often vastly more forgiving that anything we can roll ourselves in javascript.
	- A point that really stood out to me in this was the idea that when you throw loads of superfluous javascript down the pipes because of things that only improve dev experience, you are taxing poor people to save yourself time.
	- An interesting development on the horizon is that people are looking into monitized browsers. That could let us sidestep ads, which have become every more invasive and open to abuse, though it also makes the internet less free so it feels like it's a bit of an emotionally complicated idea.
- [Chris Coyier: Oops, I guess We're all full-stack developers now](https://www.youtube.com/watch?v=lFOfQsi5ye0)
	-  An interesting talk on how the skills that are traditionally seen as just front end can combine with things like serverless to make that skillset effectively 'full stack'. While a lot of my viewing this week was very pro "get good at HTML and CSS, not just frameworks", Chris points out there's a lot of people who focus more on JS frameworks and systems than fundamentals and if you wanna get employed it makes sense to have them under your belt. Front end has become is so broad it is kinda fragmented. Even [Brad Frost](https://bradfrost.com/) hates doing stuff like setting up a build pipeline and does better when you sit him next to someone who does like doing that stuff. Just because we're front end doesn't mean we do everything, just that we _could._
- [Katie Sylor-Miller: Migrating to Jamstack and OhShitGit](https://www.youtube.com/watch?v=PqlhYVqLDm0)
	- A case study on how Katie moved her great "oh god I broke it and git is terrifying" resource, [Oh Shit, Git!?!](https://ohshitgit.com/) from a couple of static files FTP'd up by hand, to using Eleventy and Netlify with proper git versioning. As someone who has often found git a bit intimidating this was really illuminating, and made me realise how much more fixable so much is.
	- I'm going to spare you the list of commands that I learnt (I'm usually a GUI person), though I think I'd like to write a bit of a 'Git for the terrified' post at some point.
	- This talk did remind me quite how ridiculously easy getting stuff up on [Netlify](https://www.netlify.com/) actually is, but also that it's even more powerful than I realised, giving you previews for pull requests out of the box. I actually find it pretty exciting how simple Netlify is, it puts the barrier to entry of getting something just _up_ somewhere as low as it's ever been and that is magical.
- [Syntax: Server Side Fundimentals](https://syntax.fm/show/188/the-fundamentals-server-side)
	- A solid but whistlestop tour of backend concepts. A lot of it was stuff I already knew but a couple of things that stuck out were the meaning of the numbers in error codes (100 informs, 200 is success, 300 is redirects, 400 is user error, 500 is system error), and that if you're not careful your log files can accidentally fill up your whole drive.

Looking at all of this as a whole, I was split pretty broadly across technical and process stuff here. Our responsibility as developers came up a lot, in making things performant, and in not impairing our users by breaking stuff for aethetics or javascript overexcitement. Also there was the diversity of knowledge across front end. Nobody really knows everything, it's ok to admit to and own your knowledge gaps (rather than just assuming the stuff you don't know isn't important). If we're going to cover all our bases, we need to work together. As much as sometimes we want to fall into a code hole and just build things undisturbed, that's only ever going to take us so far and actually talking to people and learning to work with each other's strengths and weaknesses is just as essential as our grasp of whatever our languages of choice are.

## Next week then?
Some heavy work stuff will take up a lot of this week so fitting in some of this stuff is going to be a challenge, but I'm determined. Making more detailed notes on the stuff I've been learning did seem to really help and it was pretty nice being able to come back to the for writing this so I'm adding making time for that at the end of the day to my daily habits.

Anything you want to change about how you do things this week? Or are you just getting on with what you already have on your plate? Good luck with whichever one it is.

&#9829; KT
