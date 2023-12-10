---
title: 'Fun With Failure'
date: Mon, 03 Aug 2020 03:15:04 +0000
draft: false
tags: ['Uncategorized']
---

It's a fantastic time to try and find a new job, and so I'm taking full advantage of these flourishing economic times. It certainly helps that I'm trying to switch to a new programming language and I'm going for a bit of a salary increase.

I've been doing a lot of interviewing lately, and it's been interesting to see the different interview styles. Software engineering interviews are always different but still have some common characteristics. For example, they don't ask or seem to care about academic credentials, and there is always a code challenge of some sort.

Every now and then I'll agree to an interview or code challenge, being fairly sure that I'm not really going to make the cut, but I just want to see where I'm at skill level wise, and get some practice. As an example, I had a nice chat with a company recruiter who asked me what my salary requirements are, and I said well, in Idaho I'd ask for 90k, but since this position is in the Bay Area, I'd probably have to ask for more. She replied, "oh, you'd get about double that".

Well, then.

I agreed to the technical interview, thinking it was likely that I'd get hit with a difficult 180k-style problem and crash and burn pretty hard, but that it would be good practice nonetheless.

The interview consisted of a video call with a software engineer, who asked me a couple of preamble questions for 15 minutes, and then had me log on to an online code editor that we could both use. He presented me a problem, that I had 45 minutes to validate a sudoku board, which basically meant making sure it had correct numbers. The kicker was that it was in Javascript, which is not a language I've used in several years (I was told it was going to be in another language). Fortunately, Emily has been doing a lot of programming in Javascript, and I routinely help her work through a programming problems she's dealing with, so I'm fairly up to date on the language.

In the end, it wasn't nearly as bad as I thought and I was able to produce a correct solution before the time ran out. I got the feedback a couple days later that stated essentially that although I had a correct solution, I hadn't handled 'edge cases', which usually means something wacky and rare that might happen, but still needs to be accounted for. I did get stuck a couple of times along the way working through the problem, which meant I didn't have time to get to everything I wanted to. That meant I got knocked out of the running. Big deal. Honestly, I had fun with the interview, which is probably a little weird.

My biggest disappointment was with a company who specializes in machine learning for publishers, meaning helping anyone with content to optimize their platform to get the most advertising dollars possible, increase user experience, etc.

The first interview was pretty intense, as far as first interviews go. My interviewer was obviously technically knowledgeable, where much of the time first interviews are patsy cake non-technical chats with recruiters. The interviewer grilled me on projects that I've worked on and system architecture that I implemented, and the whys and hows of all my decision. Now this doesn't really phase me, as I can talk about software all day long, which is my favorite subject (outside of rock n' roll), so I didn't have too much of an issue coming up with answers.

I got invited to the second round, which was a two parter. For the first part, I was presented with a Google Doc, with a problem that a fictitious company was dealing with, and three potential software solutions. It was my job to analyze the three options and provide a recommendation along with my reasoning, and reply to questions that some fake person wrote (ie, what's the time complexity of this or that solution?). I wrote out some good logical reasoning for my recommendations, answered some questions, and it was off to the second part. This was a code challenge, in which I had to work with a data stream from RFID readers that came from fake robots in a fake warehouse. I was asked to perform some tasks like, what was the average speed of Robot A? I was able to clear that hurdle pretty easily, but I think I was mostly unsure about how well I did on my writing portion.

Apparently I didn't have to worry, because I was invited to the third and final round. I was told I would be given the specifications for a program that I needed to write 24 hours before my interview. At the appointed time, I was sent an email instructing me to create a reverse proxy server that would retrieve the contents of any arbitrary URL, then optionally cache the contents of the website, return the contents to the user, and in subsequent visits to that website, the cached contents would be returned instead of getting the content from the website. I was told to use my best programming language.

This is where I had a choice. I could use my best programming language as suggested, but PHP is a language I want to move away from. I'd much prefer to use Go, which is what I'm trying to switch to, though I am weaker in that language because I just don't have as much experience with it. But the role is for a Go engineer, so I figured I'd write in the language that I'd be using.

I decided to go ahead and take a risk by using Go. It wasn't long before I started to really feel the pressure, first because I've never written a proxy server before, and I was using a language that isn't my 'best'. However, I was able to do some research and I spend some hours of dedicated focus (we got pizza that night) and I was able to come up with a working solution.

The morning of my interview, I had what I can only describe as a panic attack. I'm not much of a worrier, and my anxiety levels are usually low, and this was not something that I normally experience. It might have been the result of the fact that when I looked up my interviewers on the internet (there were 5 of them listed!). One of them was the CTO of the company, who had done work on the space shuttle software in the 90's, and had written code for 'defense systems'. The interview was also scheduled to be 3 hours long, although they did say they didn't expect it to take the full 3 hours.

When it was time for the interview, I was surprised and a little relieved to see it was only two people, both of who seemed to be around my age. I had looked up one of them on LinkedIn (LinkedIn stalked?). She used to be a graphic designer but a few years ago she was somehow able to make the switch to software engineering, which I thought was very cool.

When they asked me to demonstrate my program, there was a bug which meant it didn't quite work as it was supposed to. Thankfully, I was able to fix the issue pretty quickly, and then they had more features that they wanted me to add on, which I was able to do successfully. After an hour of writing code, they had a few more questions and then ended the interview after about an hour and 15 minutes from start to finish.

I was relieved that it seemed to go well, but a few days later I got a rejection email. I emailed back and asked for feedback and the response was "The feedback was mostly on the application you came in with" and that there were issues, most of which the interviewers had gone over them with me (which I was able to fix?).

The next statement was interesting to me: "Given the current state of the country our hiring capacity has become limited for the near future. We have a pretty high bar for software engineers and unfortunately the bar is being set higher by the conditions we are all living in". So maybe that means if it wasn't for this damn virus, I would have gotten the job, I'm not sure. Or maybe I should have held my nose and written it in PHP, which is a language I'm proficient in, but I just don't care for it.

There's a lot of potential 'what if's', but needless to say I was very disappointed with this result. I felt like I had taken a risk and had done pretty well, and I feel that I _am_ good enough to work for this company. But I understand there are a lot of fish in the sea at this point, with a lot of layoffs happening, even in the tech world.

But there are some bright spots to all of this. We weren't sure we really wanted to move to Carlsbad, California. Yes, we would have lived close to the beach and within about an hours drive to Emily's grandparents. But living in California is incredibly expensive because of rent and because those silly leftists love to tax anything and everything they can get their hands on. The offer would have to have been at least 120k to even begin to make it feasible.

I've also been dreading the thought of having to work in an office. I love being able to work from home, where I can still be involved with the family.

I hate the fact that it feels like I have to choose one or the other. The reason why I want to get a software engineering role that's a step up is simply because I'm ambitious, I'm bored at my current job, and I want to realize my full potential. But if I'm ambitious in my career, the stereotype is that I'm going to necessarily be neglecting my family, but I don't see why that has to be the case. Why can't I be ambitious in my career AND my family? I'm not trying to be the CEO, I just want to see how far I can get while working in the constraints of not working crazy hours. I should say, not working crazy hours at work. I have the habit of working extra hours at home to hone my craft as a software engineer. Up to now, I'v effectively work at least 60 hours a week, but 20 of those are unpaid, at home hours. But obviously having a child makes dedicating that much time more difficult.

The only solution I can come up with is to completely cut out social media so I can be completely present in whatever I'm doing. Luckily in the past few years, I've already mostly cut out social media from my life, and my life has improved as a result.

All that to say everything is up in limbo and I don't know what the hell the future holds, so just don't ask us.

![](https://dallincoons.files.wordpress.com/2020/08/img_7590.jpg)

Kev can now pull himself up to the standing position, which he likes to do often. That means that we have to keep a closer eye on him.

![](https://dallincoons.files.wordpress.com/2020/08/img_7600.jpg)

Speaking of keeping a close eye on him, Kev took a bit of a tumble and has been sporting a horrific looking black eye. It's been healing quite nicely though.

![](https://dallincoons.files.wordpress.com/2020/08/img_7589.jpg)

I always bring Kev along to help me cook dinner. He's always very interested in what I'm doing, and I give him free samples.

![](https://dallincoons.files.wordpress.com/2020/08/img_5608-collage.jpg)

Just a fun little before and after. He's grown quite a bit!

![](https://dallincoons.files.wordpress.com/2020/08/img_7540.jpg)

Being able to pull himself up also means he can sample the dirt!

![](https://dallincoons.files.wordpress.com/2020/08/img_7542.jpg)

![](https://dallincoons.files.wordpress.com/2020/08/img_7519-copy.jpg)

He's got two little teeth on the bottom row.

![](https://dallincoons.files.wordpress.com/2020/08/img_3411.jpg)

And he's quite an escape artist. if I don't keep a close eye on him after I bathe him and put him on the ground to put his diaper on, pretty soon there will be a naked boy darting across the floor.