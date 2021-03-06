# 0636. Vue on 2018 — Interview with Evan You, author of the Vue.js framework

[Vue on 2018 — Interview with Evan You, author of the Vue.js framework](https://blog.hackages.io/https-blog-hackages-io-evanyoubhack2017-cc5559806157)

No one can deny it: Vue.js is booming. The Progressive JavaScript framework is making big gains with a growing community of users & a large amount of developers wanting to learn how to use it. Will it continue its impressive flight to the top in 2018? Is Vue going to overtake React and Angular? Wondering if you should switch to Vue.js?

A few months ago I talked to Evan You — creator of this popular frontend framework- in Brussels. We talked about the successful Vue.js journey so far and the future of it. The story is one of great inspiration for every software or web developer out there, so read on!

It was a tiresome but rewarding 3-day workshop in Brussels for Evan You, the brains behind Vue.js. When we talked he was still a bit jet lagged from the long trip from the US to Belgium, where he ran his first ever multiple days workshop during our bHack To School event. A milestone for him and for Hackages. He left the workshop participants from all over Europe amazed about his skills and knowledge.

At the time of talking in October 2017, Evan was working full-time on Vue together with his core team, and with funding mainly coming from his Patreon funding campaign. Before working full-time at Vue, Evan was active as an engineer at Google and Meteor. His career up until now is inspiring for every developer out there, as is the full interview we conducted with Evan. I hope you’ll enjoy reading as much as I enjoyed talking to him.

「Viewing Evan live coding while opening the box of Vue: it’s magic」— Vue.js HackCamp participant

Evan with the Vue.js HackCamp group during bHack To School, October 2017

## 01

Evan, tell us your story in a nutshell. How did you start developing and how did you come to the point where you are now, giving a 3-day workshop in Belgium?

That’s a long story. There’s an extended interview on Medium「Between the wires」that gives a detailed description of the early stages. But long story short: I came to the US when I was 18. In college I didn’t study Computer Sciences but I went for a major in Art History instead.

3『 [Between the Wires: An interview with Vue.js creator Evan You](https://www.freecodecamp.org/news/between-the-wires-an-interview-with-vue-js-creator-evan-you-e383cbf57cc4/) 』

「I just took only a few computer classes and I didn’t think I would become a programmer」- Evan You

Back then I wanted to become a designer and went to Parsons Designer School in NY where I did a Master of Fine Arts in Technology. So that was both design and coding. That’s the point where I started to learn JavaScript. I also got into creative coding in the browser and started building some Chrome experiments.

After graduating I joined Google Creative Lab as a creative technologist. I was using Angular and I wanted to build something lighter, so I started to experiment in the early stages - I think for about 6 months. I was becoming pretty bored and decided to turn Vue into a proper open source project. In February 2014 I made it public and it all started from there for Vue.js.

Then I worked on Vue in my spare time mostly, until October 2015 when 1.0 was released. In February 2016 I started to work full-time on it. Since the experimental stage it has only been 4 years now. 

## 02

How did Vue become so big in that short time span, you think?

There were several growth stages. The first big growth period was when the Laravel community started using Vue. All the people in Laravel started using it because it was so much better than JQuery. They did that even before 1.0 was released.

The release of 1.0. helped people adopting it because they started seeing it as a stable library. Then 2.0 introduced new features; making it lighter, faster and better in every way. This increased the popularity of Vue.js and it has been continuously growing at a good pace since then.

Recently with the React licensing issue, Vue got an extra boost. It mainly made many people realise they could also use Vue instead of React. That helped us in exposure. I’m happy that Facebook eventually changed its React license, resolving much of the fuzz. But I think this issue helped promoting Vue anyway, to be honest.

「Vue got more exposure and React became open source: that’s a win win」— Evan You

## 03

What’s the secret of the success of Vue, according to you?

There aren’t many secrets. I am a really interest driven person. My motivation comes from a sense of fulfilment when working at something. The whole reason that I’m working full-time on Vue right now is that at one point I started to realise that I got more sense of fulfilment by working on Vue than by working on my job back then. And when I work on Vue, on the code, it doesn’t really feel like work. I naturally have this urge…sometimes I can’t control it: if I have a bug I want to fix it. It kind of pushes you to put a lot of heart into the project.

「When you want to succeed at something, it’s really important that you feel that you’re naturally inclined to enjoy working on it」— Evan You

If you feel like it’s always a struggle, to force yourself to do something, then it’s probably very hard for you to succeed at it. Obviously discipline and persistence are important too. But yes, I’m really doing this with passion. I really was just following my heart.

Although being able to do that is not necessarily easy. You need to still be able to support yourself at that time. I think in that aspect I was lucky because I didn’t even know if it could work, when I started working full-time on it. I said「let’s try this」and if it doesn’t work I’ll just find another job. But it turns out it’s working pretty well right now.

## 04

How did you manage to survive at the beginning?

I started the Patreon Campaign where people can pledge money to support my work on Vue. When I quit my job I think I received 4000 dollars a month on Patreon.

「So I was like: okay, at least I won’t starve to death working on Vue, so I’ll just do it. Let’s see what happens」— Evan You

Now I make more money than I would at my previous job, so financially I’m doing pretty well. Doing workshops like this also helps (laughs).

## 05

What was your biggest challenge?

It’s always an uphill battle when there are bigger players like React & Angular out there. Today people consider Vue an equal choice as to Angular and React. But for the first years it was like: why using Vue when there is React and Angular? We really had to find our position on the market and figure out what makes it different than the other frameworks. So I had to deal with self-doubt. In the process I sometimes thought: ‘maybe I should stop, because there is React and Angular’.

When you read Twitter you think everyone is doing React. But when I talk to users they pick Vue instead of other options. I realised I’m not building Vue to compete with React, but I’m building it for users who really like using it. Overcoming comparing yourself with others, that was the challenge mainly.

Over time I’ve come to realise there are so many developers out there and there is actually enough room for several major frameworks to coexist. There is definitely overlap in our user bases. But Angular, React and Vue each have a group of users that are naturally attracted to the solution because it sits well with their mental model.

React kind of attracts a lot of functional oriented programmers. Vue attracts a lot of people who’d prefer the more classic HTML, CSS & JavaScript model of development. And Angular attracts a lot of people coming from a Java or C# enterprise background.

「Lots of developers just need a solution that’s tailored for them」— Evan You

There are developers who can sway between some of the solutions but there are also a lot of developers that stay with one solution that fits them. Vue was able to fill a market gap between React and Angular and that’s why we were able to grow to where we are today.

## 06

How would you counter critics that say there’s no big company behind Vue? That it’s just you and your core team, and thus unstable?

It’s okay for a project to depend on one person because Vue is still relatively young. If you think about projects like Python, Linux, Ruby or Laravel; they were all projects that critically depended on one person. But these projects are hugely successful and many companies build on top of them. So it’s not necessarily bad, it just depends on how these projects can evolve to reduce the person factor. And that’s something we’re actually working on.

「I personally don’t want to be responsible for everything. I want the project to be able to evolve, even if someday I stop working on it. So part of my work right now is to make that happen」- Evan You

I’m cultivating the core team to be able to contribute more to Vue. To make them able to understand how the inner mechanisms work. Eventually I want to turn this project into a group driven project. It’s a progress and I’m pretty optimistic about it.

On the other hand I don’t think a big company backing the project is absolutely necessary. It’s cool to have companies financially sponsoring a project, but Angular for example is being controlled by Google. React is being controlled by Facebook. So users of Angular and React are trusting that Google and Facebook will be good towards the project. But they’re still full profit companies. Their interest doesn’t necessarily align with those of the users of their open source software.

Whereas Vue is completely funded and supported by its users. So our interest really just aligns with our users. The whole reason we’re working on Vue is to make it better for those people who use it. It’s not because we’re using it in a full profit organisation. I think that actually makes a pretty big difference. That’s an advantage, in my opinion.

## 07

What advice would you give to people who try to convince their boss of using Vue?

Interesting question. First you need to figure out what your boss cares about in terms of frontend frameworks. The most common argument I get against Vue is that there is no big company behind it. This question actually translates into two separate things. One is sustainability: will this project suddenly die or stop evolving? Second is stability: is this project responsible, will it suddenly break? Because big companies usually require their products to be super stable.

In terms of sustainability you can point to our Patreon Campaign, to our Open Collective Campaigns and more importantly to look at the GitHub activity — our release cycles. You can see that we’re very active and well maintained, and it has been consistently like that for the past 3 years. And there is really no incentive for us to just suddenly stop doing that.

The second thing is stability. We obviously value stability a lot. Companies want their projects stable, so we want to avoid breaking changes for as long as possible.

「You can look at the track records and see how we handled breaking change in the past: we don’t want to break our user’s code」- Evan You

To be honest there are so many companies, and I think around 300.000 developers using Vue in the world today. We have a lot of responsibility not to break their code. We have some pretty high profile and production apps that rely on it. It really is in our interest to keep the API as stable as possible. There is a Vue.js status report coming soon, I will share it on Twitter. The data and content in it will also help people to show their management to understand where Vue stands today.

## 08

How do you see the future of Vue?

We’re planning to keep working on the project obviously. Our long term goal and vision is that we want to make it easier for developers to build things on the web. That’s kind of the bigger, blurry vision.

「If the landscape of web development changes in the coming 5 to 10 years, we will want to help existing Vue users to adapt to those changes」— Evan You

We will evolve Vue to take advantage of whatever is coming up in the web platform. Making sure that people who have invested in Vue can also get on board with those new improvements in the platform.

It’s going to be adaptive, but there are some potential great things going on in the web world. We want to keep Vue competitive. For us it’s really important to keep an eye on what’s coming and what can change. We want to think about what we can do. Luckily for us I think we’re in a pretty good shape right now. So we’re going to be stable for the next few years.

## 09

Last question to wrap up: what did you think of your bHack To School workshop in Belgium?

I was a bit stressed when I was first here, as it’s the first 3-day workshop I give. But everyone is very friendly, what I really like. People come and say thank you after the workshop, so there’s a really good atmosphere. Overall it went pretty smooth, so it was a positive experience!

Thank you for this interview, Evan. We hope to see you back next year during bHack To School 2018!

bHack To School 2.0 will take place in Brussels, Belgium from 15 -19th of October 2018. Sign up here to receive updates on mentors & workshops for this event.

You can read a second part of this interview here:「Developer learning styles — A chat with creator of Vue.js Evan You」.

3『 [Developer learning styles — A chat with creator of Vue.js Evan You](https://blog.hackages.io/developer-learning-styles-a-chat-with-creator-of-vue-js-evan-you-a11f2dc5deac) 』

You can find more information about Hackages on our website. We’re a community driven company that offers high level training on the latests frameworks and technologies around JavaScript. We also love to contribute to open source and to organise free community events all around Europe! Check our upcoming training and events near you at https://hackages.io/training.