Scotland JS 2014: Revisiting Imposter Syndrome
===============

Repo for Scotland JS 2014 keynote. Seeking feedback and contributions from People Who Are Funnier Than Me, which is basically everyone else in the world. If you've edited, provided feedback, or added stuff - add your name below so I can hype your awesomeness at the end! Don't be shy. :)

The goal of this talk is to explore the biases and behaviors of 'pure' programmers toward designers and 'designer-developer' hybrids. Other roles (devops, for example) are also touched upon lightly. 

Example biases:

- designers and/or designer-developers can't program as well as pure devs
- design is just fluff and pictures
- if one doesn't see a lot of code commits on a designers' github, it must be because they don't code a lot - as opposed to coding on private, proprietary repos which a lot of people do for jobs - addresses the fallacy of assuming that if someone doesn't have a lot of open source, they are somehow inferior as a programmer.. a weird one
- devops just set up servers, they don't ACTUALLY program
- anybody who knows how to make something look good is not to be trusted
- everyone in programming is a dude, so I mean, clearly even Angelina is not a real developer
- add bias here! there are many. I can't think of them all right now

The talk should be delivered in a deadpan, super serious fashion, with the content being obvious juxtaposition with its ridiculousness. Notes and slide suggestions in the rough script are inside square brackets.

By the end, the talk should address the content with something like 'if you think I sound ridiculous, well, this isn't far off from how ridiculous and arrogant you sound like when you say these things'. Something like that, perhaps. Still figuring out how to land this just right.

People who deserve mad credit for helping or bein' inspiring or both, or both and MORE:

- Curtis Lassam
- Jenn Schiffer

Rough Script and SLIDE PLANNIN'
===============================

Hello, my name is Angelina Fabbro. I work on the developer wrench team at Mozzarella. You're probably familiar with our browser, Mozzarella Foxfire, 

[would love a slide of the Firefox logo made out of pizza, with the Firefox being mozzarella]

..as well as Foxfire OS, the first mobile phone to target exclusively the red panda population. Despite dwindling numbers and endangered status with the World Wildlife Federation, red pandas use social media 210% more than all other animals, including humans. It was natural for us to tap that market and it's going quite well.

[slide of a red panda, FxOS phone photo-shopped poorly into it's paws]

Last year at JSConf US, I gave a talk on how to be a better programmer. 

[screencap of JSConf US talk]

I didn't expect it to be as popular as it has been - in fact, Peter, who invited me to speak at Scotland JS asked me to do a talk somewhat like it. He wanted something 'aspirational' in nature, the kind of talk that gets at the truth of things. Around the same time, I published an article on The Pastry Box about something called 'Impostor Syndrome', often referred to as 'Impostor Phenomenon'. I called for anyone who writes code to stop discounting their practice as invalid for any reason. If you write code, you're a developer.

... or so I thought. Well, I'm here to apologize and tell you that I was wrong. There are impostors in our industry, and I'm positive some of them are here around you in this very room.

[callout slide with 'I'M SORRY, EH' on it]

The imposters in our field go by many names, the most common one being: DESIGNERS

[and each of these terms should be on its own 'callout' style slide as Angelina walks through them]

Sometimes, in attempts to impart their relevance, they may also refer to themselves as DESIGNER-DEVELOPERS, DESIGN-GINEERS, DEV-SIGNERS, or [would like a most ridiculous, never heard of term that gets a laugh here as the final one, drawing a blank right now]

Obviously, the sole purpose of writing software is to trick some VC into giving you money so that you can make something that's kinda okay and then get bought out by a larger company who for some reason or another feel mildly threatened by your tiny but present market position, netting everyone who did very little a lot of money.

On your quest to acquire large sacks with dollar signs on them, you're going to want to be careful who you hire. You don't want to waste any time or money on employees that aren't breaking their backs with real, hardcore skills to make you, the boss they should be grateful for, as much money and credibility as possible. How else are you going to sell your product for even more cash?

[definitely need some clipart of money bags with dollar signs on them, omg]

I'm here today because I've made it easy for you. It's the least I could do after spreading such egregious misinformation. I've figured out the easiest ways to find imposters in our field to make it easy for you to make money without wasting time on these code-less cretins. Although designers are the real culprits to watch out for, I've also spotted some other impostors along the way that we'll discuss as the need arises.

They Make Things Look Good
--------------------------

The first clue that lets you know that you're dealing with someone who has design skills is that they make things look appealing to others. What we know from marketing psychology though, that things don't need to look good in order for users to click on things and participate in the web economy.

[Show some really ugly sales funnel sites, the kinds used to sell 'self help ebooks']

If you hear someone utter any of the words on this slide,

[slide with design related terms - typography, visual contrast, composition, art direction, etc.]

.. you can be almost certain that you're dealing with a designer at best, or an art director at worst.

Since we know that we don't need websites to look good, it's easy to see what a sham designers can be. Frankly, they're just plain inefficient. Take a look at this website! Sure, a few people might say it looks good, but they're almost certainly designers too. White space? More like _wasted space_.

[show a beautiful site with lovely use of white space, transition to slide with big red arrows pointing at 'wasted space']

Now just think of what we could accomplish if we weren't wasting all of that space?

[show same website cramped and plastered with ads]

They Know CSS
---------------

Obviously, if you encounter someone who knows CSS, also known as California Style Sheets, they're a designer, not a developer. True developers work exclusively in the land of abstract bits. CSS is mainly used to make things look good on the web, which as we've already established is unnecessary. In fact, industry expert [Dr. Jenn Schiffer published a whole article](https://medium.com/cool-code-pal/1f6430781393) on how to deprecate your CSS so that we have one less language in our stack to worry about.

They Don't Know CSS
---------------------
I'm going to be frank with you. If you're using a framework or a toolkit that provides style for you, but you don't understand the underlying CSS, you can't possibly be a real developer. That's right - you shouldn't know CSS very well, otherwise then you are in the dangerous position of accidentally learning how to design. Still, CSS is everywhere, and you need to know how to deal with it and deprecate it as Dr. Jenn Schiffer has recommended.

In order to build programs, you need to see through every abstraction and be able to work comfortably
at the lowest possible layer. This means, if you're building Javascript applications, you simply _must_
be completely comfortable building them with nothing but ECMAScript. That's right, you should be programming not with JavaScript, but with the _standard it's based on_. 

You're Concerned about User-Experience
-----------------------------------------

There's these other imposters who like to tell Real Developers what to do a lot of the time, and they're called 'user experience designers', interaction designers', and other fluffy terms like that. Basically these people are designers but _worse_. 

Not only do these jerks like to pretend they know how something should look, which is already terrible, they pretend to know how things should behave or act so that users are not frustrated with your software.

Mostly they just end up being annoying as they talk about things like use cases, user testing, and design patterns. You know as soon as the words 'design patterns' come up that you're dealing with another fraud from the world of design.

By telling you how the software should behave, they're telling you how you should write code.

It's safe to ignore their arrogant suggestions, because nobody know how to code better than you do.

If your boss tells you to listen to them, only implement parts of what they explain to you to make it abundantly clear that _you_ control the domain of programming at the company, and that you're only going to take their 'advice' when you feel like it. 

Your users aren't going to notice a difference. We've already established you don't need great design to acquire users and clicks.

They Write jQuery
-----------------

Sometimes designers will figure out how to download code off the internet and get it into their websites. jQuery is a programming language that is even more popular than JavaScript because it was basically made so that designers could pretend to know how to code. It's really easy, you just have to put the jQuery code in your page and then copy and paste some lines verbatim from the jQuery website and everyone will think you know how to code. Most of the time these jQuery 'plugins' don't add anything useful to websites, and are just used to make the designer feel better about themselves.

[show some jQuery slideshow]

A slideshow? Really? Nobody wants to watch a movie on the web, they just want to click on stuff. I know YouTube is really popular, but that's only for cat videos as cat media is the sole exception to most Rules of the Internet.

[show jQuery datepicker]

Designers will argue that a calendar datepicker is 'easier' for users to get information, but we don't need to care about that. If we leave things confusing, the user will accidentally click on some ads and make us money. Even if we don't have ads, we can just use an HTML input field and leave the handling of all that up to a _real_ programmer.

Anything Front-End is Not Real Programming
------------------------------------------

By now it should be clear that anything that pertains to what the users sees and interacts with is barely relevant to actual programming. The Real Developers all work server side, probably in PHP, and sometimes Nodes JavaScript although we all know deep down that the Nodes are just a trend that will die soon. Long live PHP! PHP stands for Pretty Hardcore Programming, so you don't ever have to question its legitimacy.

You just need to focus on your back-end, server-side code and do the bare minimum on the front-end because it doesn't really matter.

They Don't Know Exactly The Things That You Know
------------------------------------------------
I've decided to draw a line in the sand. A Venn Diagram. 

[a diagram that is basically not a venn diagram in the slightest]

If I know a thing, it's a thing that you need to know in order to be a Real Developer. Put your hand up if you know what a B-Tree is. Okay, all of you are real developers. Okay, who knows how a Bloom Filter works. Hands up.  Everybody who just put your hands down? You're not Real Developers anymore. 

Now, on the other hand, if I *don't* know a thing, it's little more than a needless abstraction that you don't need to know about to be an effective developer. Hey, do you know about how Java handles thread pooling, you might ask? Of course not, I'm a node.js developer. All of MY eventing is handled with an event loop, like GOD INTENDED. 

[picture of node.js logo with a halo; more controversial / maybe not appropriate.. a picture of jesus holding up node.js logo]

If someone says they are a developer and they don't know all the things you know, chances are they are a sham too. 

It may be difficult for you to admit that a lot of your friends and co-workers are frauds.

They may not be beyond hope though, all you need to do is explain to them that they need to have the same opinions and knowledge as you. 

Be willing to talk to them, or rather, _at_ them at length about these things without interruption or break. Who wouldn't love that? Make sure you don't let them interject with any questions, those would just get in the way of the learning that needs to happen.


They're Not a 24-Year Old White Guy
-------------------------------------
Seriously? Why would you even want to be a software developer if you're not a 24-year-old white guy? 

The whole reason we named our company "Mozzarella" is because we wanted it to be nothing but a uniform pasty white expanse of dudes named Matt or Dave.

Sometimes, people who are not white and people who are not men and sometimes both will contest this, but since there's so few of them, you don't really need to pay attention to them. I mean, who are they kidding? It's not like our industry isn't a complete meritocracy. All you have to do is work hard; the door is open. There's absolutely no reason to believe that this industry is hostile to people other than 24-year old white guys.

[during previous paragraph narration, clip through several slides of NOT OKAY exclusionary behavior, be sure to pick stuff offensive but not overtly triggering to be sensitive to the audience]

In particular, women whine a lot about our industry. If only they would just apply themselves and work as hard as the men, then they wouldn't have any problems. If a woman ever criticizes our industry for this, it's basically misandry, which is a very serious and growing problem. It might even be _systemic_ one day, and although it's not now, whenever a woman suggests that there may be inequality or addresses problems with men, be sure to interrupt them and make sure she knows NOT ALL MEN are the way she's described, and also that as a man, since the industry is filled with men, you must know best for the industry about all things, including other genders and races too, so tell them to just to be quiet so that you can tell them how it is.

[feels like a punchy ironic slide could go here, no idea what yet. ideas?]

This may lead you to wonder why someone who looks like a woman is giving this talk. Well, you see, I convinced myself I was a developer for a long time and tried to do serious, full time developer jobs writing Real Code with The Right Languages. But now that I'm in a role that is something like 'developer relations', which is basically 100% marketing all the time, everyone knows I must not write any code. In fact, after most technical talks I try and give (which would be better given by a man), someone always knows I'm an impostor. Yes, that's right, almost every time someone needs to ask me 'if I write any code' or assert to me 'that I must not write any code'. How right they are, and thank you for reminding me!

Do they work with Servers, People, or Art Assets?
--------------------------------------------------
If you work with a server in any capacity, you're devops, and shouldn't be taken seriously as a developer. 

I know, I know, you're going to tell me that someone needs to write the Nodes.js to get that user data that you need to accumulate and sell, and maybe those are kind of developers, but if you do anything else at all then you can't be a Real Developer. Sure, we can say that a Real Developer wrote The Linuxes once upon a time, but since then operating systems have basically been solved forever, and setting up a server and backing stuff up sometimes is not a real job, and it definitely does not make you a Real Developer.

If you work with people, you're either a manager or a community interaction specialist of some kind. Either way you obviously you shouldn't be taken seriously as a developer. You might have learned to code as a hobby to try and get Real Developers to listen to what you're selling, and maybe some of them will be dumb enough to do that. Managers are basically babysitters to make sure the company only hires Real Developers and that they are meeting their minimum quota of lines of code per week to earn their salary. 

Community managers and developer relations types are just glorified feel-good nannies for the users of your product, whether they be end users or end developers (the latter being relevant if you're shipping code for other Real Developers to use)

And if you work with art assets, well, you should just leave right now. There is no help for you. Get out.

Empty Github Account? Get out.
------------------------------
Do you know what separates REAL Developers from fake ones? Real developers have dozens and dozens of projects in their GitHub account at any given time.

Now, in order to accomplish this, you're going to have to give up a lot of your free time. If you're out hiking or having beers with your friends, you should be asking yourself: could I be coding right now? Am I a REAL developer? Also, you might have to slack off at work a little bit - there's nothing that kills your coding buzz like having to do work on copyrighted code on a private repository during normal work hours. 

You might have other obligations like a family and kids, but nobody cares about that in the industry because you're supposed to be a 24 year old white guy willing to work long hours to the good of the company, and if you can't do that, you might as well give up now.

Here's a game you could be playing: count all of your active github repositories, then include the number of open-source repositories you've forked. Finally, multiply this by the number of "favourites" that you have. This number is a measure of your value as a person and worth as a Real Developer.

If your profile on Github is scant of influential open source contributions, nobody is going to take you seriously. Remember, proprietary code is as good as invisible and doesn't count. If you are hiring for a Real Developer, you'll be able to tell if they're serious by looking at their Github track record. Throw out their resume, resumes are obsolete now and won't tell you anything you need to know about a candidate's experience.

You Can't Be Wrong, Ever
---------------------
There is nothing, nothing in the world, more poisonous to your reputation as a real developer than admitting that you don't know something - or, worse, admitting that you might at some point have been wrong about something. 

You cannot be a code 'rock star', 'ninja', or expert of any kind if you are ever to admit being wrong. You have to be so perfect that you attain a kind of programmer god-hood amongst your peers. Often, you can measure this by the number of Twitter followers you have, so as you begin to have serious arguments with other developers on Twitter you will have a number of people willing to back you up at all costs, thus reinforcing that you are never wrong. Because if a lot of people on The Internet say you're right, then you can sleep well at night knowing that you are right in the most absolute of terms.

My recommendation is simple: if you think you're right about something, really dig in your heels. Argue about the issue at hand until you're red in the face, no matter how inconsequential. It doesn't matter what you accomplish - what really matters is that everybody around you acknowledges that you are right.

You're Actually an Impostor
-------------------------------
Okay, so, let's imagine you've done everything that you can to become a Real Developer, and you still don't feel like one. 

That's because you're not. All of your coworkers are, but you're just a moron. Everybody talks about you behind your back all of the time. They know that you're not a Real Developer.

You have no idea what you're doing. And the worst possible thing would be for someone around you to discover that you've been an impostor this whole time. 

[http://www.librarified.net/wp-content/uploads/2013/03/i-have-no-idea-what-im-doing-dog.jpg]


THE FINAL WORD
--------------
Remember, everybody. The whole reason we're here is to keep other people out. Software development is serious and exclusive, and if we start letting suits and designers and anybody else pretend to be developers, it's just going to get worse for all of us - so stay on the watch, and remember - if you see someone who's not a REAL developer, report it to the nearest authority. They'll know what to do. 

