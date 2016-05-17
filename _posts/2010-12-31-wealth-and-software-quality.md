---
layout: post
title: Wealth and Software Quality
date: 2010-12-31 09:26
author: oldpond
comments: true
categories: [Software, Software Testing]
---
I was reading (and re-reading) <a title="How to Make Wealth" href="http://www.paulgraham.com/wealth.html">Paul Graham's essay</a> on wealth creation, and it made me think in a new way about software testing.  It's a fascinating article that provides valuable insight no matter what field you are in.  First, let me provide a little context.

At the last <a title="WOPR" href="http://www.performance-workshop.org">WOPR</a>, Goranka Bjedov was relating some thoughts from her presentation at StarWest where she questioned the future of testing.  Basically, she was saying companies are picking speed and price, not quality, and that testers are going to disappear.  That got me thinking about what exactly I do when it comes to software testing, and I blogged about it <a title="Software Quality Specialist" href="http://mikebonar.blogspot.com/2010/11/software-quality-specialist.html">here</a>.  The way I see it, software quality as a goal will never disappear, but our roles in the software process need to evolve to stay current.

Paul's essay got me thinking even more about our roles as software quality specialists. Basically, he says don't confuse wealth with money.  Wealth is what people want.  Money is just the medium for moving wealth around.  When you create software, you create wealth.  What kinds of wealth do software testers create?  Who are we creating wealth for?   Do they really want what we create? Interesting questions.

Testing creates wealth in the form of a service.  Nobody is going to say, "Here's a buck.  I'll take one of those yummy tests you are making."  If fact, the things that testers create are often discarded, tossed out at the end of the project.  We're a bit like waiters; we don't actually make the software -- we just help bring it to the customer.  We're also a bit like the annoying violin guy in that the customer could be completely satisfied if we weren't there.

Our customers, the people we create wealth for, are the development teams.  Do they want what we create?  Most of the time they don't.  We are like auditors, in a way, a necessary evil.  We're there because there's something wrong with the way they create wealth.  We're like a safety net. We're also a bit like leeches.  We confiscate their code  and say, "You can't have it back until we are  done testing it."  In the  end, when the software is sold, we benefit from the wealth the development team creates. It's no surprise that development teams sometime look down at us, or see us as a roadblock or bottleneck.

One might argue that the customer wants our wealth indirectly because our wealth contributes to the overall wealth in the software.  I think that is a pretty weak argument.  If the software came out perfect and did exactly what the user wanted, would anyone care if it was never tested?  Does the end user say, "I only want software that is tested?"   They just want software that works.

As Paul indicated, money is the medium of exchange for wealth; its a means for moving wealth around.  What is the medium for exchange for testing? In other words, what is the medium by which we move the wealth of testing around?  If your team is following a methodology like the Rational Unified Process (RUP), then you will be familiar with project artifacts like test strategies, test plans, test cases, and test results.  These artifacts are the medium of exchange.  They are the means by which we move our testing wealth into the software.  But, how effective are they?

The test strategy lays out the connection between requirements and testing.  Given a set of requirements, the team comes to agreement on a plan of attack.  Very little testing wealth is transferred through the test strategy.  In fact, one could argue that no wealth is transferred.  If the goal of the project is to produce quality software, then all we are really doing in the test strategy is saying, "Yes, we will take steps to create better quality software."  Once the software is complete, the strategy gets discarded or tossed into the archives, never to be seen again.

Given an agreed upon plan of attack, the test plan lays out the details on how the team will execute.  It says we need these people in these roles using these tools following a high level schedule to produce a set of results.  Again, it's hard to find any wealth being transferred by this artifact.  Like the strategy, the test plan gets discarded and the software has not gotten any better.

Test cases are a curious artifact.  Some projects spend hundreds of hours laboriously listing all possible test cases and mapping them back to the requirements.  Sometimes that is a useful exercise, especially when the teams are inexperienced, but can you test without first documenting all possible test cases?  Of course you can, but again, let's ask the question, "Have we transferred any wealth to the software?"  Not yet.

Software testing transfers wealth to the customer through finding and fixing bugs.  That's where the real wealth is found.  Every bug that is found and fixed makes the software a little better, a little less likely to break.  This is what the user wants.

Where does that leave us?  We often find ourselves in a situation where we are forced on the software development   teams, where we leech off their wealth, and where our customers couldn't care   less about us.  If we are following a process like RUP we may not be creating wealth at all but merely creating money with the hope that we might somehow, magically transfer wealth to the software we are creating.  Not a good place to be.  How do we get ourselves out of this   rabbit hole?

We need to shift our thinking.  What we do is part of software development, and our wealth is built into the software we create.  We need to stop thinking of our roles as separate from the software development process.  We need to focus on the tools and technology that help drive quality into software.  Things like Test Driven Development, build automation, code quality analysis, continuous integration and version control.  Being able to monitor software as it runs in production, creating ways for software to notify us when it behaves badly, ensuring software can be updated seamlessly without interrupting the customer, and being able to design software that facilitates all that.  We have to start thinking like software developers who specialize in quality.

That means we are not writing test strategies, test plans and test cases all the time.  We're not gatekeepers who get in the way of wealth creation.  We're part of the software development process.  We focus on creating the continuous integration systems.  We install and configure the code quality analysis tools.  We create the coding standards and API documentation.  We implement the version control systems.  We do everything we can to make sure code quality is <strong>built into</strong> the team, the processes, and the tools on a software project.

So, take a look at what you are doing when you get back to work, and ask yourself the question: am I creating wealth, or am I just creating money?  I think you'll find the answer quite enlightening.
