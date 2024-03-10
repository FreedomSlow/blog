---
layout: post
title:  Do you really want to be a Data Scientist? 
date: 2024-03-09 22:25:00
description:
tags: mics, career
categories: mics, career
tikzjax: true
---

With all the recent hype around LLM-s like ChatGPT and Gemini, it seems that now every company feels an obligation 
to add **magical AI** to every product they launch, announce it in the ad campaign and this will guarantee the imminent
success. Look at [this fridge](https://news.samsung.com/us/new-food-ai-looks-inside-fridge-help-find-perfect-things-cook-already/), 
for example.

And as you well know, when there's an increasing demand on the market, there should also be an increasing supply. 
Thus, more than ever I see people trying to get into the field, thinking they will change the world with some sort of
SkyNet. 

The unfortunate truth is that no, most likely you will not work on the state of the art (SOTA) systems, that can 
paint, look for information and code better that these puni humans. And even if you will - this will be only 20% of 
your work. Is this that sad? - I hope here, in what can be perhaps called a letter to the past self,
you will find your answer.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/wanna_be_ds/despair.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>

</div>

---

### D for Data
What makes any Data Scientist happy and full of excitement? Data. Lots of it. The more, the better. 

But Data is very shy, and she always takes her best friend Data Errors with her, and let me tell you, this friend is 
pretty annoying: unique ID-s become not that unique, timestamps jump as if they are in the new Doctor Who season,
the same user can be a man, woman or a bear, and competitor
prices lose their value quicker than [Zimbabwean dollar](https://en.wikipedia.org/wiki/Zimbabwean_dollar).

And somebody has to find all of these errors and decide how to deal with them. Because sometimes, during a casual 
conversation over the lunch with the friendly backend engineer, you'll discover that "Oh yeah, ID-s could be not unique
if the platforms are different. But we've changed this two and a half years ago, why do you ask?". And he will never 
know how many hours you spent chasing this...

Sorry, I digressed a bit. This is the kind of work you'll have to deal with most of the time - find the data, 
start looking at it, find more and more issues, and then try to collect little dusts of information in order to 
resolve them. And this is actually quite an optimistic scenario, when you have the data, and you can easily 
find and/or access it. Quite often you'll have to collect it yourself: either try to find some open datasets, which will
rarely fit your specific case, or write everything yourself, or, even worse, ask help from software and data engineers,
but you know, they have their [own shit to deal with](https://www.youtube.com/watch?v=DYvhC_RdIwQ).

Many people can't withstand this, so they quit or go insane.

### First rule of Machine Learning: start without Machine Learning
People give problems for Data Scientists to get a result - probably some uplift in product metric. 
And more often than not, nobody really cares how exactly you've done this, 
except for maybe a couple of your colleagues and friends. I think here lies the main difference
between mature specialist and the one who only started one's journey.

Rational and tired of the life, the universe and everything senior will extract and manipulate the data
in every imaginable way, read couple papers and articles (if they even exist), talk to business to
understand what exactly is needed; and in 90% of the cases will solve a problem without ever using these
famous neural networks, that would have probably eaten up entire yearly budget with AWS GPU instances. 

The solution itself most likely won't be sophisticated and could be understood and implemented by every other
deep learning 101 graduate. 
But as one of the best programmers [once said](https://www.goodreads.com/quotes/10480697-an-idiot-admires-complexity-a-genius-admires-simplicity-a-physicist):
"Idiot admires complexity, a genius admires simplicity", and if you want to be a data scientist - always
remember that, the value is almost never in the use of some SOTA architecture. 
In one of the companies that I've worked with the whole ad bidding optimisation consisted of four `if` 
statements, and that haven't stopped them from successfully scaling for 4 years.  

Btw, did you spend countless hours learning different machine learning techniques? 
Yeah, half of the time you won't need them too... Many problems that regular business driven data scientists
work with can be solved by using heuristics, linear optimisation, simple statistics methods and so on.
And more importantly, you've probably interacted with them for many years and didn't even know about it:
for example I bet you've listened to Spotify recommendations, and one of the
[core algorithms](https://erikbern.com/2015/10/01/nearest-neighbors-and-vector-models-part-2-how-to-search-in-high-dimensional-spaces.html)
there has no **magical AI**, just simple math and programming that could be understood by most of the 
high-schoolers.   

Many people want to create "the next big thing" that everybody on Twitter will talk about, and when they don't,
they get disappointed and leave.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/wanna_be_ds/fight_club.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>

</div>

### Math and professional growth
No matter what some people say (including me in the previous section), but DS without math is like a database 
without indices. Only the fact that the whole area has just separated from probability theory 
and statistics can already tell you a lot. Every sophisticated and impressive system that you see out there:
ChatGPT, StableDiffusion, AlphaZero etc. - is just a large probability machine, that consists of ten-ish basic
math operations and concepts. And the sad truth is the more math you know, the less impressive the whole AI
thing is to you, but I guess it's like that with everything else.

Machine and especially deep learning is a relatively young and now highly competitive area. For that reason
things move quickly here, and if you want to be demanded on the market, you'll have to follow recent developments,
even if you'll never apply them in your work. That's just an unfortunate reality of the interview process 
that we have here: software engineers have, IMHO useless, Leetcode, and we have this. And I think it's not
that different from, lets say, medicine. I'm also not saying that other guys in other areas don't have to
develop, but I'd say that significant changes to the C++ standard are made not that frequently.

Professional growth is a very tricky thing, I think. I can't really give you a list what does mid-level
DS have to have in order not to be a junior, and the same thing goes for senior vs middle. Looking at how people
torment candidates during interviews with all the technical and theoretical questions, I just convince
myself even more. Moreover, sometimes it happens that some undergrad, who has never seen a production 
codebase, knows theory better that interviewers :)

The only thing that I can think of is the same that guys in game-dev have - number of projects (models)
that have been launched to production. And maybe the pragmatism while solving problems - that includes
understanding of the exact problem business is trying to address and how you can simplify the problem 
without damaging the result.

Here I was talking mostly about regular "product based" DS. There is, of course, an alternative path: you
can become an established expert in some area e.g. generative model in NLP and/or CV. But then sooner or later
you'll have to work either in research, or in enormous corporations. We'll talk about this later.

### How to enter the field?
So you've got to this section even after all my grumbling, huh? I guess nothing can stop you now, so it's time
to talk how you can get a job.

What can I say, even for people from adjacent areas, that are not connected to data, it will be difficult. 
Of course, there are some notable exceptions, like always: I personally know couple very strong and cool 
data scientists who started as developers, but they started when neural networks were shallow
and dinosaurs were still alive. For many roles the domain knowledge is crucial - after all, you wouldn't trust
an autopilot design to some random bloke, who has never seen data from cameras, would you? In that case
we would have had much more situations like [this one](https://www.youtube.com/shorts/vQG2ikUeh_c).

Juniors. It will be really tough, especially in this economy. You probably have already noticed that small companies
and startups rarely have any openings. That's pretty understandable: they have to develop business and
there's sadly no tasks, time and/or money to support junior lvl specialists. Large companies, like FAANG or
consultancy agencies can afford themselves to invest into DS beginners. But there is a catch - ~~catch 22~~
the competition is fierce, and these companies often prefer people with PhD-s and 
that's especially noticeable in US. I attribute this, if you want to call it elitism, to the fact that the field
was built on shoulders of giants - quite often famous mathematicians, statisticians and other researchers.  

If you want to become an independent specialist and strong individual contributor, my advice is to go to work
in some data consultancy (not shitshow like mckinsey & co.) - you'll work with various tech stacks and business domains,
the work-life balance is almost never good in these types of companies, but you'll grow quickly, 
if you'll survive, of course. 

### You will never build SkyNet
I vividly remember the moment I understood that I want to become a data scientist. It was right after
DeepMind's [AlphaGo](https://www.youtube.com/watch?v=WXuK6gekU1Y&t=4585s) made a breakthrough by winning the match
against world Go champion. If in the case of chess, humanity pretty much lost all the chances of winning in mid 00s,
the game of Go, on the other hand had so many possible moves that cold-blooded machine simply got lost
during its computation.
Some people predicted, that we will have the necessary computational power only in 2040-s at best. And then, out
of nowhere this bunch of scientist comes out of nowhere with their neural networks and crushes the competition.
Incredible, isn't it?

Nowadays, the next big thing are large language models (LLM) - users mesmerisingly look at their screens and
see the companion that is more intelligent as most of them (well, [almost](https://www.youtube.com/watch?v=e_HSA1lUd04))
and all the hype and advertising only adds to this. 

But the sobering truth is that most of us will never create models that will be mentioned during the debates
in EU parliament, or even on hacker news. Most of us will use our experience and knowledge to solve very particular
business problems: starting from optimal packing to save money on the carton boxes, and ending on the click-through
rate improvements for mobile ads that we all hate.

But if you are really determined and want to change this world for the best, you should go work in a research team,
likely in some enormous corporation, that can afford to have teams and computational power to develop things 
that don't yield any immediate profit, just so they can have a chance to dominate the field and humanity
at some point in the future. Look at OpenAI with their investments from Microsoft, no profit and 
still evaluation of 29B. Yes, these companies are on the cutting edge of the field, and they release models that
are exciting to write and read about, but then you will most likely have to have a very strong academical 
background, study a lot and focus on some specific area just so you can be a part of these teams and be a 
co-author on one of the papers (if management allows to publish one).

Very simple analogy comes to mind: the vast majority of developers don't create new programming languages or
sophisticated highly-optimised libraries, they implement product features and solve whichever business task
they have on their Jira board. Is it bad? - I don't think so, everybody chooses their own path that yields 
most satisfaction.

### Tech stack
Python has been a standard for many years now, and I'd reckon it'll never go anywhere. I know, all the "hardcore"
systems languages fans will say that's not even a proper programming language, but for most of the data scientists
language is just a tool that helps to solve a problem, and Python is perfect for that. I know very few people in 
out field that write code just for the sake of juggling memory addresses around, even being one of them :)
And even if they do like this kind of stuff, they probably do this at their spare time and with something more
suitable and enjoyable, like Rust.

I also think, that now there are almost no positions where DS just sits quietly in the corner and trains
isolated models in our favourite [Jupyter](https://jupyter.org/). Because how vast modern models are,
even the most hard-core researches have to write and deploy some type of production code.

In case you work with product, you will more often than not write full services: from the ETL pipeline to the
model inference and their communication with other services with some sort of API. There's nothing wrong or scary
about it, in my opinion actually, every good senior, regardless of their specialty, should be able to do multiple things
poorly and at least one thing well. Sometimes you'll find yourself writing frontend code because stakeholders asked for 
it, and it's three times quicker than waiting for engineers to do it.

Most of the time you'll use external libraries and technologies, most of which are developed and maintained
by the aforementioned soulless corporations. There is already 1001 service to orchestrate, provision and deploy
your models, why develop another one?

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/wanna_be_ds/perfect_girl.jpg" class="img-fluid rounded z-depth-1" zoomable=true %}
    </div>

</div>

### Working with people
Regardless of whether you're doing research or solve business tasks, you almost certainly won't do it alone.
Researchers work in teams, so it's expected for you to have various discussions of newly published 
[arxiv](https://arxiv.org/) papers, brainstorms and so on.

Data scientists that work with product also can't do it themselves. Even if you are the only DS working on the
project, chances are you won't know anything about it at the beginning. For example, do you know much about
oversees container logistics? - and you'll have to optimise purchasing to minimise the costs involved; or
how what are the stages of an ore enrichment? - here computer vision can save literal billions.
That's why you'll talk to the managers, field workers, logistics specialists and any other person, who works with
it every day. Perhaps you'll even visit the warehouse or factory. And there's no escape from it, otherwise
you won't understand enough to adequately solve the problem.

Some people get annoyed by this part of the job, some people like it, but the fact is that significant share of
your workday will be spent just talking to people, especially at the beginning of the project.

### Why do you need it at all then?
As for money, DS, like any other IT specialist, will not earn gold mountains in hiring. 
Salaries comparable to software engineers, maybe a little higher. The enterprise pays more than a 
regular product company. Startups pay less, but there is a chance to make money on a share in the 
company. Now this option is quite plausible, because everyone wants an AI for themselves.

They say that altruism is inherently selfish, but I love my job because I can make people's work
and sometimes life easier. The fact that it's often done without **AI magic** is not a huge disappointment,
at least for me. And additionally every problem is unique in its own way and that adds constant excitement and
challenge.

See you in the next one!
