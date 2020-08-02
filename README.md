## Welcome to Whirlpool-of-Events


Introduction



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

### The Blue Sticky - Commanads

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














