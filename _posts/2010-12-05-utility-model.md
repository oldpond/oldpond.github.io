---
layout: post
title: Utility Model
date: 2010-12-05 13:27
author: oldpond
comments: true
categories: [Ideas, Software]
---
I recently read an article by Richard Stallman on the dangers of Software as a Service (SaaS).  You can read it <a href="http://www.gnu.org/philosophy/who-does-that-server-really-serve.html">here</a>.  In it he warns about how SaaS takes away your freedom in much the same way as closed source, proprietary software does.  He makes some good arguments, but I believe he misses where the real danger lies.

First a little background on SaaS.  With SaaS, you don't own the software or the hardware it runs on.  A good example of SaaS is on-line tax software.  With on-line tax software you use it once to create your tax file and you pay a flat rate for that service.  You get a tax file returned to you and perhaps they will do the submission to the government on your behalf.  You don't buy the tax software, you don't install it, and you don't have to worry about it again until next year.

The utility model is a little bit different but follows the same principles.  With the utility model you don't own the hardware or even the software; you simply pay for computing cycles as you need them the same way you pay for electricity from the electrical utility.  Unlike the tax software example, instead of paying a flat rate you pay for how many computing cycles you use.

Now, think back to how the electrical utilities were born.  In the early days of electricity, each city or factory would have its own electrical generator.  They would build it big enough to support future growth, but eventually they would grow out of their current generator.  They could either build another generator and hook it up the the old generator, in the form of a grid, or they could buy a neighboring generator to hook into.  The idea here is that you sell us your generator, we'll manage it for you, and you get the benefit of selling your excess capacity to us and that will help keep the cost of your electricity down for years to come.

The same idea can be applied to computers.  Companies would sell their computer power to the vendors who would in turn sell computing cycles back to them on a pay per use basis.  Now, companies don't need to buy computers anymore.  No need to worry about capacity; no need to worry about upgrading hardware and software.  Just install your applications on the utility, and pay for whatever cycles you use to run them.

Now, here's the problem.  <strong>Computing technology is a strategic resource</strong>, just like oil, refined uranium, spaceflight, etc.  Countries that have computers have an advantage over countries that don't have computers.  Depending on where you live, there are countries to whom you cannot give computing technology.

Let's say that all the major businesses in Canada decide to go with the utility model.  One of the side effects of this move is that all their old computer hardware would eventually disappear.  Remember, they don't have to worry about replacing old hardware, and it doesn't matter where the computing cycles come from as long as they can run their applications.  Eventually, the vendor would get rid of all the old junk sitting on the floors of the computer rooms and replace it would shiny new computing cycles.  These new cycles might be coming from inside the company's own computer room, or they could be coming from halfway around the world.  It doesn't matter, as long as the applications run smooth and the response time is acceptable.

Let's also say that suppose Canada decides they're not going to sell the US any more of our good Canadian beer because, well, they just drink too much of it, and there may be a shortage if we're not careful.  Then the US says, okay, then we're not going to sell you anymore computing cycles.  Oops.  We just transferred control of our ability to run our applications to another entity, and once that happens the entity can willingly or unwillingly take that control away from us.

As a software quality specialist, I am looking forward to working with software as a service and cloud technology.  I think it will provide some interesting challenges and there's nothing I like more than wrapping my little gray cells around a tough problem.  The danger with SaaS is not in the technology itself.  The danger is in not being in control of it, and not knowing where your computing cycles are coming from.  Open source software solves that problem by putting control into the hands of the user.  I'm not saying SaaS should all be open source.  But if SaaS offers advantages over the way we've been doing software till now, then let's explore it.  Let's kick the tires and see what SaaS can do, but let's make sure we have some tires to kick.

Companies should be building their own clouds.  They would provide huge advantages for development teams.  Think about how quickly you could turn up and down test machines.  Or think about how it would solve the problem of availability.  Instead of buy big iron boxes to eliminate single points of failure, design for the cloud and who cares if one node goes down.

There are projects out there now where you can get under the covers of clouds and software as a service.  Look into <a title="KVM" href="http://www.linux-kvm.org/page/Main_Page">qemu-kvm</a> which is the heart of virtualization.  Or check out <a title="Silver Lining" href="http://cloudsilverlining.org/">Silver Lining</a>, an open source cloud controller project.  These are just a couple, but if you dig you will find more.  And if you don't find them, get out there and start building them.
