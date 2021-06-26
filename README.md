# intro-to-nodejs
Learning the basics of Node.js to be able to move forward and create Javascript applications outside the browser.

# 1- What is Node.js?
* Server-Side Javascript
* Built	on Chrome's V8 Javascript Engine
* Open Source Runtime
* Created by Ryan Dhal in 2009
* Evolved since creation to allow developers to build almost anything

Note:
What is Chrome's V8?
So most every browser have their own Javascript Engine, on how they actually parse and 
run your own Javascript. Chrome's one is called V8 and it's just their compiler that they
use to compile your Javascript down to machine code so the actual machine can read it.
Chrome's V8 has been one of the best out there. So the creator of Node decided to take 
that out of Chrome, rip it out and put it somewhere else. And that's what this is built off on.
So that's why you can write Nodejs in Javascript because it's built on the same  engine, It's V8.
There's other Javascript engines and browsers like Spidermonkey, which what is that a Firefox.

What is runtime?
-Runtime describes software/instructions that are executed while your program is running,
especially those instructions that you did not write explicitly, but are necessary for 
the proper execution of your code.
-Low-level languages like C have very small (if any) runtime. More complex languages like
Objective-C, which allows for dynamic message passing, have a much more extensive runtime.
-You are correct that runtime code is library code, but library code is a more general term,
describing the code produced by any library. Runtime code is specifically the code required 
to implement the features of the language itself.
Resume: I'm thinking of an executable. So if you're writing code in bash you're in a bash runtime.
		
Example, so if you're writing code in Bash you're in a bash runtime. If you're writing
code in Ruby, you're in the Ruby runtime. So this is like it's own runtime, it's its own 
environment that's self-encapsulated, you don't have to do anything.

# 2- What can I create with Nodejs?
Pretty much anything a scripting and server language like python or ruby can, but with Javascript.
* Tooling (build, automation, etc)
* API's (REST, Realtime, etc)
* CDNs
* Shareable libraries
* Desktop Applications
* IOT (Internet of Things, or IoT, is a system of interrelated computing devices)
* Pretty much anything because node is on everything now.

Note:
What is a CDN?
This is like a network of computers. Around some space, whether it's the world or a nation, or a consonant 
whatever, it's a network of computers, and you host your assets on that network. So there for those assets
are delivered to your customers as fast as possible.
So if i'm making a request from Minnesota and there's a server in Minnesota, I will get my image from this server
in Minnesota versus going to all the way to Oregon and Virginia.
