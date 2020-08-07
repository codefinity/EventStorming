# Welcome to Whirlpool-of-Events


### Introduction



## Big Picture Event Storming



### The Orange Sticky - Domain Events

Used to identify Domain Events

Domain Event represents a change in the system.

Events must have a subject (noun) and a predicate (verb).

Verb must be past tense indicating somethiing has alredy happened.

External systems can also produce domain events.

Domain evnts must follow a timeline.

Example: 

User Registered

User Group Changed


### The Bright Pink Sticky - Hotspots

If you see an ambiguity during the identification of Domain Events, mark the spot with the Pink Stiker.

The decision on correct or correct order of domain event can be postponed to later.

### The Pastel Pink Sticky - External Systems

These are the third party systems that your Domain Events can go to.

## Design Level Event Storming

### The Blue Sticky - Commands

Commands are the intents of users

Commands are something that changes the state of the system.

### The Green Sticky - Read Models

Something that our users look at before asking the system to do something or send a command.

These are the screens of our application.

### The Yellow Sticky - Users/Roles

They Execute the commands

We need to understand which role is the system is running the command

Example:

-Administratir
-Reviewer
-Editor

### The Violet Sticky - Policies

The Policies subscribe to domain events.

When it receives a domain event, it sents another command to complement the work.

Example:

When a user accepts the invitation to join, the invitee gets a mail notification.

## Miro Template

[Event Storming Template](https://miro.com/app/board/o9J_knjMlGU=/)


## Articles

- [Modelling Reactive Systems with Event Storming and Domain-Driven Design](https://blog.redelastic.com/corporate-arts-crafts-modelling-reactive-systems-with-event-storming-73c6236f5dd7)
- [Event Storming and Spring with a Splash of DDD](https://spring.io/blog/2018/04/11/event-storming-and-spring-with-a-splash-of-ddd)
- [Design Level EventStorming](https://buildplease.com/pages/fpc-6/)
- [A facilitators recipe for Event Storming](https://medium.com/@springdo/a-facilitators-recipe-for-event-storming-941dcb38db0d)
- [A step by step guide to Event Storming – our experience](https://www.boldare.com/blog/event-storming-guide/)
- [Event Storming and Modeling](https://github.com/ylorph/RandomThoughts/blob/master/2019.08.16_StormingWithStickies.md)
- [Misadventures with Big Design Up Front](https://philippe.bourgau.net/misadventures-with-big-design-up-front/)
- [Remote Team Flow EventStorming for Retrospectives](https://medium.com/nick-tune-tech-strategy-blog/remote-team-flow-eventstorming-for-retrospectives-a8ea33cdb277)
- [EventStorming; Core concepts, glossary and legend](https://baasie.com/2020/07/16/eventstorming-core-concepts-glossary-and-legend/)

## Slides

- [Event storming recipes](https://www.slideshare.net/ziobrando/event-storming-recipes)
- [Model storming ](https://www.slideshare.net/ziobrando/model-storming)
- [50.000 orange stickies later](https://www.slideshare.net/ziobrando/50000-orange-stickies-later)
- [EVENT STORMING - COLLABORATIVE LEARNING FOR COMPLEX DOMAINS](https://slides.yowconference.com/yowwest2016/Rayner-EventStorming.pdf)
- [Transactions redefined](https://www.slideshare.net/ziobrando/transactions-redefined)

## Videos

- [Alberto Brandolini - 50,000 Orange Stickies Later](https://www.youtube.com/watch?v=1i6QYvYhlYQ)
- [YOW! 2016 Paul Rayner - EventStorming - Collaborative Learning for Complex Domains](https://www.youtube.com/watch?v=04tGbixfGEY)
- [Trying out online EventStorming](https://www.youtube.com/watch?v=CbPEibNUe0s)

## Books

- [Hands-On Domain-Driven Design with .NET Core, Chapter 3: Event Stroming, Alexey Zimarev](https://www.packtpub.com/in/application-development/hands-domain-driven-design-net-core) 
- [Introducing EventStorming, Alberto Brandolini](http://eventstorming.com)
- [Domain-Driven Design Distilled, Chapter 7: Acceleration and Management Tools, Vaughn Vernon](https://www.pearson.com/us/higher-education/program/Vernon-Domain-Driven-Design-Distilled/PGM332632.html)
- [The EventStorming Handbook, Paul Rayner](https://leanpub.com/eventstorming_handbook)
- [What is Domain-Driven Design?, Chapter 8: Event Storming, Vladik Khononov](https://learning.oreilly.com/library/view/what-is-domain-driven/9781492057802/)

## Tools

- [Miro](https://miro.com/)

## Code Examples

- [ddd-by-examples ](https://github.com/ddd-by-examples)

## Github

- [EventStorming Glossary & Cheat sheet](https://github.com/ddd-crew/eventstorming-glossary-cheat-sheet)
- [mariuszgil
/
awesome-eventstorming](https://github.com/mariuszgil/awesome-eventstorming)

## Markdown References

- [Mastering Markdown](https://guides.github.com/features/mastering-markdown/)
- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)


## Special Thanks To

[mariuszgil
/
awesome-eventstorming](https://github.com/mariuszgil/awesome-eventstorming) for providing the information to start this repository. 


















