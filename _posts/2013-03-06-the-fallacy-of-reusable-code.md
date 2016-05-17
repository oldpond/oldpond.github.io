---
layout: post
title: The fallacy of reusable code
date: 2013-03-06 08:21
author: oldpond
comments: true
categories: [Software]
---
Reusable code is often a goal of software development.  Why is that?  The thinking is that if I can reuse the code I wrote I will be able to write more software in the future in less time than it took to write the original, reusable piece.  And, if I write more software quicker, it'll be less expensive.  Huh?

I wonder who thought this up.  I've seen what happens when developers try to write reusable code.  Most of the time they end up with a maintenance nightmare.

The first problem I've seen is the "framework" problem.  The customer needs to write 5 enterprise web applications, so the architect talks them into building their applications on a "framework".  By framework, I mean an underlying, shared services layer like a printing services layer or a communication services layer.  The problem with this approach is that your 5 applications become welded to the underlying services layer, and now instead of being able to maintain each application at its own pace, <strong>you have to maintain them all together</strong>.  If you make a change to one corner of the environment you have to test and potentially upgrade the entire set.

The second problem I've seen is the classic big ball of mud.  The architect states that copying code is a lazy hack, and therefore we will write code once and reuse it everywhere.  They write a simple little java batch job, but because of their policy, the project now has 15 external dependencies.  And, if you look at each of those external dependencies, they each have multiple external dependencies of their own.  Now, when you try to load the the project in Eclipse you have to load half the enterprise in order to get the code to compile.

This is a surprisingly common problem in legacy code, and it's the reason you hear a lot about loose coupling these days.  But, do we really want <em>reusable code</em>?  I don't think so.  I think what we are after is the ability to create <strong>replaceable code in a way that is repeatable.</strong>

Let's explore the first concept.  Replaceable code is by nature reusable.  If I were going to write a communications service I should be able to swap it out for another communication service and still be able to use the one I have on another system.  Web services tries to solve this problem by hiding implementations behind a clearly defined interface.  What does it look like at the function, class or package level?  log4j is a good example of a library that should be easily replaceable but is often surprisingly difficult.  SLF4J is an improved logging framework that facilitates better replace-ability.  The key difference here is that log4j was created to provide easy logging whereas SLF4J was created to provide easy logging <strong>and</strong> replace-ability.  In other words, replace-ability was a <strong>design goal</strong> for SLF4J, whereas re-usability was probably the key driver behind log4j.

So, if reusable code can get you into trouble in ways you don't expect, can replaceable code do the same thing?  Sure it can.  Imagine a world where machinists all made their own screws.  Of course, this was the case in the early days of replaceable parts, and it was only when screws and drills became standardized that the situation improved.

Do customers care about replace-ability?  Customers don't care about a lot of the things we do as software designers and developers; they just want working software.  But, we should care about it.  It's easy to stand up in front of your development team and say code reuse will be one of your design goals.  It's another thing entirely to say code replace-ability will be one too.  Think about it.
