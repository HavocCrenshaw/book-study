# The Mythical Man Month by Fredrick Brooks Jr.

## PREFACE
Fred worked on one of the first operating systems, OS/360 and one of the first\
high level programming languages. The 60s and early 70s were also a very sparse\
era for software engineering and programming, being a niche field of science,\
and only really having a handful of resources.

## CHAPTER 1 - The Tar Pit
Programming becomes more costly and more complex very quickly, exponentially so.\
It's easy to build a program but it's hard to build a programming project, hard\
to build a programming system, and hardest to build a programming system pro-\
ject. A project being a fully fledged app, dependable, general, usable for many\
sets of data, many machines, for many users. A system being exceptionally ro-\
bust, and dense program. Creating a program project is generally 3 times more\
costly as creating a program. Creating a program system is generally 3 times\
more costly as creating a program. Creating a program system project, therefore,\
is 9 times as costly, but the only truly usable product, and the product that\
should be desired in the undertaking of programming.

Fred is likely a Christian.

Programming is fun for people to do because it is an intellectually invigora-\
ting and is by nature an immensly creative medium, for anything can be calcula-\
ted. Fred also considers programming to be tractable, e.g. obedient to the pro-\
grammer. This is, by programming's very nature, an extremely fitting descrip-\
tion.

But, it is not always fun. Programmers woes, consist of time consuming, tedious\
tasks particularly in debugging, as with every productive hobby or profession.\
You also must be perfect, the computer listens to your program and does ex-\
actly as it is told, and if the programmer makes a mistake, so will the compu-\
ter. And the most dastardly thing, programming requires other people. You do not\
have full control because full control would take all the time of everything\
ever. You need to rely on other people's code to write code, and software is no-\
toriously awful. Poor documentation, incomplete delivery, poor design, now your\
trouble to figure out and fix. And in the other hand, the lack of say about the\
nature of your programming, being told what to make, and the tools you can use\
to make it. However, this view Brooks holds is clearly warped by his strictly\
professional experience in the programming field. Yes, in any professional cap-\
acity this is objectively true, but in hobby this is not. Obvious, but I make\
mention of it anyways.

## CHAPTER 2 - The Mythical Man Month
The problem that most software engineering projects have is that humans can't\
estimate the amount of work required to properly do one, and we're a mess and\
can barely keep ourselves and our projects together. Which is true. This is of\
course a reflection of the chaotic world of 60s and 70s software engineering,\
but still rings true today, albeit less severely.

Programmers are far too optimistic, ending up with these ideas that "all will go\
well", e.g. thoughts that you've fixed the last bug and programmers think that\
"it'll only take as long as it should take," which Fred clocks as nonsense,\
which it is.

Fred suggests that the man-month, a unit of measurement at the time for software\
engineering projects, is a fallacious unit of measurement, built on the idea\
that because it worked for partitionable tasks (i.e. farming of sorts) it will\
also work with software engineering, which is an extremely complex field in the\
sense of tasks, some partitionable, some not, and all requiring a lot of com-\
munication, and he suggests that instead of always becoming faster with more\
men, it's true for a moment, but starts to become more timely at a certain\
point. This is because of the cost to communicate.

Fred suggests that a project schedule should be 1/3 planning, 1/6 coding, 1/4\
component and early system tests, 1/4 system tests, all components ready.

He says that software projects need to stop being estimated on a hunch, and at\
the time of his writing, there is no real quantifiable method for estimation in\
professional use. He says, a chef's food is going to take however long it's\ go-\
ing to take, and if the customer gets upset he can eat it raw, and if the chef\
rushes he will create an unjustifiable horror of food. Programmers are similar,\
and this is true with all engineering. Which is why it disturbs him, that pro-\
grammers are not treated in this way, unlike other engineering fields.

The chapter basically boils down to this. Don't be an idiot when estimating, and\
"adding manpower to a late software project makes it later." Men are hard to\
deal with in a software project, they must be trained, briefed, everyone must\
communicate, tasks must be specially partitioned in a specific and sequential\
way.

All of this is very true and I agree in totality.

## CHAPTER 3 - The Surgical Team
Blame H. Sackman, W. J. Erikson, E. E. Grant for the mythical 10x developer.\
Maybe I should write a book, "The Mythical 10x Developer." They made a paper,\
"Exploratory Experimental Studies Comparing Online and Offline Programming Perf-\
ormance" which went on to suggest that a good developer is much better than a\
bad one, "by an order of magnitude." And so begins the 10x developer. Fred goes\
on to use the data from this paper, to say a "good developer may be 10 times as\
productive as a bad one." Is this the true origin of the 10x developer myth, in\
a book about productivity myths? Irony. Fred only suggests it, he doesn't chal-\
lenge it. Well, he does without doing it. He acknowledges that the data shows no\
coorelation and chooses to say it anyways. Hilarious.

Actually, he is challenging it without challenging it. Whether or not this is\
intentional is up for debate, I'd like to say it is. He suggests the idea of a\
"small team of sharp developers" is a foolish idea due to the fact that on a\
system like OS/360, he reported from 1963-66, over 1000 people were working on\
it, and probably 5000 man-years went into the project.

So it appears he agrees with the idea of the 10x developer, because in this seg-\
ment he uses this 10x comparison to try and justify the small team, which he\
promptly goes on to say that even if we were to assume that everyone working on\
OS/360 were medicore (something he said was far from true), dividing the work\
amongst these ten 10x developers just simply is not enough for a large project.

This almost sort of contradicts Chapter 2, maybe intentionally, however. Is the\
5000 man-years mostly put into the absurdity of handling 1000 people on a soft-\
ware project? Training, communication, managerial tedium? I thought this was the\
case, this is what Fred said, at least. We will find out.

He brings up the Mills' Proposal, a solution to this mess. This is the circle\
around I was looking for. Chapter 2 says "adding manpower to a late software\
project makes it later", Chapter 3 to this point has said "even the 10x develop-\
er cannot keep up with 5000 man-years," now here is the true answer.

The Mills' Proposal suggests that you should have a large amount of people,\
teams working on components. These teams should be like a surgical team. We have\
the surgeon, or chief programmer, who defines the specification, writes the\
code, runs the tests. This is your 10x developer. Then, the copilot, the right-\
hand man of the surgeon, capable but less experienced. He functions as mainly as\
a thinker, evaluator, and discussant, representing the rest of the team and\
helping the surgeon where needed. The administrator, who handles all the admin-\
istrative parts of the project in place of the surgeon. The administrator may\
however lack work if the project does not have substantial requirements, and can\
serve two teams if necessary. The editor takes documentation that the surgeon\
has drafted, critiques and refines it, adds references, just like an editor of a\
manuscript. Two secretaries, one for the administrator and one for the editor.\
The administrator having a secretary makes sense, the editor does not and Fred\
does not clarify. The program clerk maintains all the technical records, storing\
the inputs and outputs of the system. The tool-smith, responsible for the main-\
tainance of tools, creating them, upgrading them, fixing them as necessary. The\
tester, who comes up with test cases and data for debugging, and setup the scaf-\
folding necessary for testing. The language lawyer, a master of the language(s)\
used in the project, and who can come up with efficient and clever ways to do\
difficult and obscure things. This is your dream team of 10 people, including\
the Mythical 10x Developer as your primary developer. It in a way shows the im-\
pact of this model Mills' proposed, as notably 80s/90s dev was not very unlike\
this in most teams (to my knowledge), but may have had different ways of doing\
things, but the main idea applies. That being, don't put 5 surgeons on one guy,\
have 4 support 1.

This maximizes the 10 person team by specializing each member to a role that\
supports the surgeon, and one does not get in the way of another. However, this\
is still only one team, and one team is not enough for a 5000 man-year project.\
So, you must scale, more of these teams. But this surgical team scales, instead\
of having 200 people or more all conflicting on the main design of the app in a\
at the time conventional team, you now might only have 20 with 10 teams of 10,\
the surgeon and the copilot of each team working together. Alas, comes the issue\
of communication once more, but we have significantly improved the effectiveness\
of large amounts of manpower.

## CHAPTER 4 - Aristocracy, Democracy, and System Design

Freds brings to mind the idea of the Reims Cathedral, a great building no doubt\
but also a conceputally flawed one. The norman transepts, and the Gothic nave,\
it's a conceptually impure building. He believes systems are the same, that the\
conceptual integrity of the system is THE most important part in system design.

Conceptual integrity is important, because it brings about ease of use. This is\
because, at it's core, software is supposed to make lives easier, not harder.

In a world where time didn't matter, one person would be the source of the con-\
cept, providing full conceptual integrity. However, time exists, and therefore\
must need more than one person. This is handled in two ways, and the first way\
is the division of labor between architecture and implementation, and the second\
way is the type of team described in the last chapter.

Fred suggests that architecture is the idea of what happens, and implementation\
is how it happens. Architecture as defined here, fundementally differs from my\
understanding of architecture because I previously understood the idea of arch-\
itecture to be a description of how things happen, to educate the programmer in\
their endeavour to create the implementation, which is the realization of archi-\
tecture. My understanding was close, but fundementally different, whereas this\
definition of architecture is more about the use of the software. (He says, for\
example, user manuals are architectual documents.)

He brings to mind his history with OS/360, where he allowed 150 implementors to\
design the architecture with the coordination of the architects, which caused\
something forewarned by the architect administrator, that the architecture would\
take just as long to make as his team of 10 could to it alone, with a worse pro-\
duct. He was right.
