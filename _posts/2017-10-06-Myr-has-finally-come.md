---
layout: post
title: myr version 1.0.0 has finally come.
---

It is done. I have been working on a command line tool for the last couple of weeks. It
allows me to run a command or multiple commands against unix/linux servers. The release version
is very crude, but I will add on to it, if need be to suit my needs. It is mostly because we lack
a suitable automation tool at work. I would prefer to use Ansible, but I don't get to make those
decisions so it was necessary to make a tool to hold our team over until the automation team finishes
their project. During the week we can build anywhere between 50/60 servers. For the windows team
it's not really to difficult of a task as they have scripts that take care of most of the items. Unix and
Linux are different stories. I won't go into details about the things that come up, but we got some
automation going, but we don't have access to a lot of tools that would help us when build servers.
plus the automation has gaps that need to be filled in and when you have to run a command on 60
server logging into each box is no longer feasible. I think the biggest thing that myr is missing right 
now is the ability to tunnel through a bastion host and run commands from a jump box or even multiple
jump boxes on a group of machine that you could potentially reach from that jump box. We run into those
situations a lot at work when building in different environment. So that is the next item on the list.
Not sure how long it will take, but since I have created a great deal of reusable method hopefully it
will go quicker than the creation of the original program. I am shooting for version 1.1.0 to have this function.
since it is not a major feature. If I can stick with this project 2.0.0 may even have a gui, but we'll see.
