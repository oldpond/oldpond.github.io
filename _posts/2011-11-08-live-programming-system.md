---
layout: post
title: Live Programming System
date: 2011-11-08 08:45
author: oldpond
comments: true
categories: [Ideas, Live, Programming, Software]
---
It's been awhile.  I am pulling the strings on my little Android startup.  It was a fun experiment, but it will never be a money maker.  The <a title="SportsBoards2D" href="http://github.com/oldpond/SportsBoards2D">code</a> is now open source, so have fun with it.

Meanwhile, my little gray cells have been busy.  Awhile back I blogged about a <a title="3D IDE" href="http://mikebonar.blogspot.com/2008/12/3d-ide.html">3D IDE</a>, and now that I have nothing else to do I've decided to flesh out the design.  Idle hands, as the saying goes.  This idea could change the world of programming as we know it.

Perhaps you have heard of <a title="Network Visualization" href="http://en.wikipedia.org/wiki/Network_visualization">network visualization</a>.  A good example of this technology in action can be found at <a title="LinkedIn Maps" href="http://inmaps.linkedinlabs.com/">Linkedin Maps</a>.  Network visualization will form the heart of the live programming system.  Here's a simple context diagram showing the components of the system.

<a href="http://www.dancingwilderness.com/wp-content/uploads/2011/11/lps1.png"><img class="aligncenter size-full wp-image-132" src="http://www.dancingwilderness.com/wp-content/uploads/2011/11/lps1.png" alt="" width="348" height="191" /></a>Let's review the components.  As you can see from the diagram, the code repository is an external component.  Ideally, LPS should be able to connect to any compatible code repository.  The core function of the LPS system will be to pull data from the code repository, like Github for example, and present the network visualization of the repository.  What will that look like?

Well, each node in the visualization will represent a project in the repository.  The size of the node will reflect the size of the code base.  The more lines of code, the larger the node.  The color of the node will represent the level of activity on the project.  The color white will represent no activity, or a project that has gone dormant.  Bright red, for example, would represent a project that has a lot of activity.  The nodes will represent one more dimension of information by blinking.  Blinking will indicate that a programmer is currently coding on a module in that node and is available for live programming.  Live what, you say?!  That's right, live programming in real time.

Once the user has chosen the project they wish to browse, they will launch the programming browser system from the node.  This will open an Eclipse-like work space with a number of windows.  The main window will show the current file being edited by the live programmer.  There will be a windows showing who else is viewing the programmer, and a window for chatting.  The chat window will have the ability to do syntax highlighting so that viewers can suggest code snippets or alternative approaches to the problem being solved by the programmer.  Think of as a live webcast where the main window contains source code instead of a slide deck.

From the programmer's perspective, they will have a plugin on their normal IDE that will connect them to the LPS server.  This will make them available for viewing.  They can present themselves in a couple of different modes.  In private mode, they don't see who's connected, who's typing code samples, etc.  They become like the main attraction in a spectator sport with fans looking on from outside the glass house.  In collaborative mode they can switch perspectives and participate in a kind of paired programming context, but without all the sweaty armpits.

On a programming project, you might require all your programmers to be connected to the in house LPS.  That way architects and senior programmers can keep a watchful eye on the more junior members.  Another way it might be used is when a programmer gets stuck he could ask a coworker to "connect up" and help him with the problem.

I think this will be incredibly popular.  I mean, who wouldn't want to watch Linus Torvalds, for example, code the Linux kernel in real time?  I bet people would line up and even pay money to see that.

Anyway, that's my design.  I'm going to poke at it for awhile unless someone offers me a job.  Then it will go into the "would be cool" pile.

&nbsp;

&nbsp;
