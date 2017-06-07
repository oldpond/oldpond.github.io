---
layout: post
title: Something a little different
author: oldpond
date: 2017-05-26
category: [Methods]
---

I've been in the IT industry for nearly 30 years now.  The first half of my career I spent working with what I'll call the larger, slower enterprises.  These are the shops that run very large projects of 30 or more people costing tens, if not hundreds of millions of dollars to deliver.  They are characterized by heavy methodologies that produce a lot of deliverables.  These methods are designed to reduce risk, however they do not always succeed in delivering high customer satisfaction.

The second half I've spent watching the smaller, faster enterprises.  These are the shops that can deliver value early on in the development cycle so that stakeholders can see where their investment is heading.  These guys are winning, and one of the reasons is that they use smaller, faster methods, like the one from Andy Hunt and team called the [Grows Method](http://growsmethod.com/).  If you saw my blog about [Agility](http://oldpond.github.io/agile/agility/software/2015/09/16/experience-report-agile-is-not-dead.html), you will recall we used a method very similar to [Grows](http://growsmethod.com/) with great success.

The last thing that happens after a heavy methodology runs "off the rails" is a learning session.  You list the things you did right, the things you did wrong, and the things you could do better next time.

For the purposes of a simple learning exercise, imagine that you are going to perform the learning session at the beginning of the project instead of at the end.  An amazing thing happens when you perform this simple little test.  It provides you with a crystal ball into the future of what you do not want to happen to your project.  

I will describe a learning session with a fictional customer who chooses a heavy methodology to deliver a "Common Off The Shelf" (COTS) solution.  If you are not familiar with COTS solutions, they are packages that you install, configure, and run.  They do not require software development, but often many data moving tools will be written.  Think of personal financial management software on steroids.

Chrystal Ball: The team was really good at methodology.  They created lots of deliverables.  Everyone in the IT industry knows this list: project plans, work breakdown structures, issue logs, decision logs, requirements documents, process diagrams, business requirements documents, functional specification documents, technical specification documents, data flow diagrams, lots and lots of ETL jobs, architecture diagrams, sequence diagrams, and weekly meetings for all these deliverables plus daily stand-ups, and of course, estimates.  There are even some things from more Agile approaches like lightweight ticketing systems and backlogs.  In other words, the team added some "agile" things to their heavy methodology to make it more "agile"/heavy. The team had all these things, and they did them very well.  

Chrystal Ball: The team was really good at process.  They followed their methodology meticulously.  Unfortunately, Murphy's Law strikes, the worst case scenario happens, and the team does not have a working system.  Stakeholders are concerned.  An entire year of project time has been spent, and expectations have not been met.  

Now, let me describe something we call a critical business driver in the IT business.  Critical business drivers are the most important outcomes for the business users in any project.  They are a bit tricky to define because the list can grow rapidly and get "fuzzy" very quickly when you just start listing all the things that are critical.  They are best described as one or two things that if not done right, make all the other things you did well not matter one bit.  Critical business drivers are important to define early in the project because they really focus the team on the target.

In our case, the target is working software.  If I were to describe this in LEAN terms, working software is the one thing the customer is standing on the loading dock waiting for.  The project may give the customer a whole bunch of very nice deliverables, but if the project does not deliver working software it has failed.  What follows is a common pattern in IT: The big, long list of deliverables becomes a big, long list of excuses for why the delays are occurring.  "Oh, we're still working on XYZ deliverable" becomes the project mantra.  This sets off alarm bells with the stakeholders.

Chrystal Ball: Unfortunately, nobody at this point suspects that the methodology may be contributing to the delays.

This is a cultural issue in many shops.  They will not question methodology midstream.  This is why a smaller, faster methods like [Grows](http://growsmethod.com/) stress the ability to adapt.  One of the characteristics of the heavy method, is that it takes time to produce all those deliverables.  There are dependencies between deliverables that guarantee that the customer will always have to wait for working software no matter how good the team gets at producing deliverables.  It is not unusual in my experience for this first round of deliverables to take up to 9 months to complete.  Larger, slower enterprises are often willing to wait this long to see results, but that doesn't stop them from getting anxious about their investment.

Failure to adapt after 9 months of work will likely lead the team to set off down the same path with the same heavy methodology that got them this far. The team might end up producing new versions of the exact same deliverables.  They might produce the deliverables a little faster the second time because there's a lot to copy and paste.  This might lead the team to think they are getting better at processes and lead to a false sense of momentum, when, in fact, all the team might succeed in doing is producing more of what the customer is NOT asking for, deliverables, and LESS of what the customer IS asking for: working software.  

At this point the learning session would carry on describing all the things the team did poorly. I think we can all fill in this list from our own experiences. These things are best left to quiet contemplation.  

Now, the fun part.  Let's imagine the same situation if we had applied a smaller, faster method that had one deliverable: working software.  What might that method look like?  Just to make the math easy, let's imagine the heavy method took one year, but did not produce working software.  If our new method turns out working software at least once before the year is over, we will have succeeded in delivering 100% more results that our heavy methodology.  Sounds like an easy target.

These big, enterprise systems, as we all know, are not like installing your personal financial software on your desktop.  They are complex systems with a lot of moving parts. Im my experience, it takes about 3 weeks to install, configure, and get running your typical enterprise COTS solution.  This includes getting the hardware up, the software installed and configured, and users logging in and performing some sort of business scenario.  We'll take a page from more agile approaches and say that our new method will begin with one 3-week sprint to "get something working".

Chrystal Ball: Murphy's Law strikes! The smaller, faster team finds it can't get the old data into the new system.  After 3 weeks they manage to install, configure and run the COTS solution, but without data they have no working software.

In other words, the team found out about the problem after only 3 weeks, not 12 months as in the case of the heavy methodology. Waiting 12 months to discover a big problem can be pretty painful in large enterprises.

Now, there are a couple of ways to go when a team has a data problem.  The team can put a lot of people to work on complex data moving tools, and this is often the first choice because we're computer people, and it's data, right?  It even sounds smaller and faster because the team can throw away the old data moving tools after they get a good set of data in the new system.  It's an easy choice and if it works the team gets a prize.  But, what if it doesn't work?  What if they struggle for a year trying to build complex data moving tools, and it still doesn't work?

The other way to go is with manual data entry.  It's not hard to estimate how much a team of data entry specialists can produce.  At one record per minute with 5 hours of productive time per day, that's 300 records per day.  A team of ten could produce 3000 records per day or 30000 records in two weeks.  That means if we want to adjust our sprints with manual data entry, we would have, assuming no overlap, 5-week sprints comprised of 3 weeks of install, configure, and run, followed by 2 weeks of data entry.  Since we already burned up one sprint, we would have about 10 5-week sprints left in our one year target.  

A good math exercise here would be to see if there's a change in probability of success between the two iterations of our smaller, faster methods.  We had 17 random tries in the first iteration followed by 11 random tries in the second.  I like to make math easy, so I'll skip that part.  The good news is the new manual data entry team's probability of success is still 11 time higher than the heavy methodology team.

I think at this point you can see where I'm going with this.  But, let's do one more adaptation of our method.  We know that one of the characteristics of smaller, faster methods is their emphasis on velocity.  A modern, software development shop, using lightweight continuous integration and build automation tools, the DEVOPS world, can show the customer working software multiple times per day.  

The reason why sprint one is always "get something working" is it brings you to a decision point very early in the cycle.  This provides the team with very valuable opportunities to adapt before a lot of effort is built up.  It provides an opportunity to say, if we didn't get it right last time, what are we doing differently this time that makes us think we're going to get a different result?  This is what "velocity" is all about in smaller, faster methods.  The faster we can get this "positive feedback loop" of "working software to customer" going, the faster we can adapt our solution to the customer's needs.

Our heavy method provided no opportunities for our team to adapt for an entire year.  Our second method would have given us 12 3-week opportunities to adapt, and our final method gave us 10 5-week opportunities. It's easy to see how adapting our method can drastically improve our chances of success.

Let's take it one step further. Imagine say we decided to write our COTS solution from scratch using a modern language and platform of our choice, and we used 3-week sprints with daily build cycles. This means with a daily "customer to working software feedback loop" we would have at least 365 chances to get it right with our even newer, smaller, faster method compared to our heavy method.  In other words, we could go from 0 to 11 chances to 365 chances to get it right by simply adapting the method.

Here's the secret of these smaller, faster methods: their high velocity allows them to build a working solution after one sprint, and then simply "grow" functionality onto your working software at a very high rate.  High velocity means high probability of success.  Who doesn't want that?

By the way, I am not affiliated with the [Grows Method](http://growsmethod.com/).  But, they're pretty cool. :)
