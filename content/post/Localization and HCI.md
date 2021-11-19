+++
title = "Localization and Human Computer Interaction"
description = "Mind the (Human to Computer) gap."
tags = [
	"HCI",
	"Localization",
	"Human Computer Interaction",
	"Development",
	"Testing",
	"Accessibility",
]
date = 2021-11-19T12:13:00Z
categories = [
	"Development",
	"Writing",
	"Accessibility",
]
author = "Roy Jonuk"
menu = "main"
+++

## Localization and Internationalization

Ideally, any constructed software wants to be accessible to the widest range of relevant users, its difficult for clients to want to use your software if they cannot use it. That would create a pretty serious problem. A driving aspect of this accessability problem is Localization and Internationalization. We often want our available and usable in wide range of countrys, and accessible by a diverse range of clients, companies, or groups. Internationalization is design that supports this, while Localization deals with specific supporting features for different given languages regions or cultures.

Localization efforts can include:
- adapting your software to using different alphabets or symbols
- language translation of your service and documentation
- changing images to better suite a different regional or cultural audience
- adapting your date, time, and currency calculation and formatting

Like all software accessability features, it is important be thinking about Localization early in the design life cycle. You want your interfaces to be easily modifiable to support different languages or formatting. Images and symbols need to be able to change region to region, and you need to be able to test these changes for the different regions you are working with. If your software is only being tested for the features and formatting present in one specific region, you are creating a divide between your local clients and your international clients. You need to be able to understand the problems that everbody using your software will have in order to be able to fix said problems and support your broader audience. 

## Human Computer Interaction

Ideal software needs to be able to supply a effective, comfortable, and maintainable vector for interacting with its users. It is important to design software while thinking about the operating experience from the users perspective. A user would not know even a fraction of what a piece of software is designed to be able to do, and have no frame of reference on its operations or limitations unless you determine a way to present this information to them in a way that is understandable, accessible, and most importantly, enjoyable. It is shameful to admit it, but I do not embrace documentation as much as I should. I am lazy, and if a program isn't easily comprehensible given the very basic instructions and layout readily given, I have a hard time urging myself to dig deeper. The best input mechanics are able to support and guide newer users while still being efficient enough for a long-term experienced user to happily operate. 

When I first started using Audacity, I was easily able to understand some basic functionality because of the use of universal symbols and a clear visual interface. I was able to quickly and easily perform some basic audio editing without deep diving into the more powerful aspects of the program, but once I was confortable with this, I was much more interested in reading through the documentation of Audacity's features to learn the paths I could take to complete more difficult tasks. 

It is also important to consider the limitations of your users enviroment. A users enviromental limitations refers to both the literal enviroment around a user (noise, lightning, distractions) that you needs to consider when you are developin, as well as their technological enviroment. What is their internet connection like? Bandwith? How powerful is a users cpu? If you only design for users working on a NASA computer in a sterile, empty room, there is an infinite number of user considerations that you are ignoring. You need to be able to design your software in ways that reflect all of these user considerations in oder to design a system to best interact with your user.

## Communication

Communication with your users can be a tedious endeavor, and you need to be certian of your tone and voice when you are building software interactions. Consider your level of formality, and the situation that a user would use your software in. Consider your options, weigh the pros and cons of your methods of communication. Should you use audio or visual cues? Analog or visual design? Every design choice should be made with the user in mind. Most programming languages that we use have include some form of support for graphical interface elements, but the selection of fancy elements should come second to first decyphering what works best to support the ways that your user will interact with your system and what information needs to be collected or communicated.

## Humor

Humor within software development is interesting. We have all seen comments and notes from developers before our time buried deep into a pile of code. Jokes and cheeky hidden comments in code are fun, but they are generally not meant for your users. I believe that in software built for supporting a fun atmosphere it is really enjoyable to make more public facing jokes towards your users. While booting up, Discord displays a random video game themed joke to the user while its logo spins in circles. This is a great way to bridge the gap between a developer and their users and helps to create a sense of community in a place where community can be hard to cultivate. 

## Testing

Of course, everything boils down to testing. The more complex the software that you are building, the more complex your testing needs to be. Testing needs to be approached in different ways as well. There is a vast difference between testing to make sure that all of the right elements appear in the proper places, and testing to make sure that all of those elements are practical and usable for the client. Try not the be your whole development and testing team, as much as working with other may sometimes make you frown, it is important to have someone who doesn't have the knowledge and experience working with your software as you do give feedback on the look and feel of your program.

## Do what you can, because you must.

As software developers, we work hard to make sure that the work we do is the best it can be, and it is integral that we consider that we will never be able to comprehend the extent of the different ways that our software could and would be used in the hands of the people. It is of utmost importance that we do what we can to allow the greatest number of people the ability and access to use software in order to do wonderful and incredible things with the tools that we have built for them.
