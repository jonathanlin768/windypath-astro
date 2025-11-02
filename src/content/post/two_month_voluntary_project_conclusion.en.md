---
layout: ../../layouts/post.astro
title: "Reflections on Two Months of Working on a Passion-Driven Project"
pubDate: "2024-04-14T18:59:08+08:00"
dateFormatted: "Apr 14, 2024"
description: ''
---
Recently, I participated in an independent game project powered by passion, where a group of online friends came together to remake a single-player game set in the Three Kingdoms period. "Powered by passion" here means working without pay, driven solely by the desire to pursue a dream. From February 4, 2024, when I first learned about the group, to February 7, when I joined, and up until April 4, when I left, I spent a total of two months on this project.

I don't want to dwell too much on the issues I encountered in this development team, as they were quite specific to the group and not necessarily applicable to other situations. Instead, I want to share some insights and advice for individual developers who might be considering joining a passion-driven project.
<!--more-->
Timeline
2/4: Learned about the project.
2/6: Passed the interview and joined the team.
2/7 - 2/17: Took a break for the Chinese New Year, didn't study project-related materials, and felt slightly pressured (lightly "PUA'ed").
2/18 - 2/24: Began learning about the project.
2/24: Fixed the first bug.
2/25 - 3/30: Fixed a total of six bugs, ranging from minor to significant.
3/30 - 4/4: Realized much of my work involved cleaning up others' mistakes, found it meaningless, and felt that I had wasted too much personal time on the project.
4/4: Decided to leave the team.

# Team Issues
The main problems with this team were the lack of comprehensive documentation and the heavy reliance on video tutorials, which were too low in information density and difficult to follow. Additionally, many features in the previous project's codebase were only half-finished, with the unfinished parts left to be treated as bugs. This made it very challenging for the bug fixers, as it was unclear where the feature boundaries lay, leading to a lot of uncertainty during the fixing process. The lack of proper documentation made modifications even harder. Lastly, with no financial incentives in passion-driven projects, it often felt like working for free, with no tangible rewards such as GitHub stars or other forms of recognition, leading to burnout over time.

# The Passion-Driven Mindset
From my experience in this project, I've gathered a few key takeaways:
1. **More Free Time Than You Think**: You often have more free time than you realize. Sometimes, just one or two hours of high-efficiency work can achieve a lot. If you have a clear expectation of what you want to accomplish, it won't feel burdensome, and completing small milestones can be incredibly satisfying.
2. **Don't Rush Big Projects**: For large projects, don’t rush to complete all the features at once. Take time to organize modules. When working on features, clearly distinguish between "unfinished features" and "bugs." For unfinished features, analyze them, estimate the time needed, and advance gradually. For bugs, analyze the cause, distinguish between correct and incorrect results, and discuss solutions only after thorough analysis. This is a long process, so don't slack off just because there’s no immediate reward.
3. **Set Realistic Expectations**: If the project doesn’t offer direct compensation, you need to control your expectations and find a personal reason to keep going. And if there’s no direct compensation, don’t feel guilty about quitting.

# Choosing the Right Project
Here are some lessons I’ve learned about selecting the right project team:
1. **If There’s No Direct Compensation, Get Something Else**: If a project doesn’t provide direct compensation (like this team or contributing to a public GitHub repository), make sure to get something else in return (like GitHub stars, industry reputation, resources, or connections). Alternatively, ensure the project itself is interesting, valuable, or promising. Don’t accept nothing, as that goes against the basic principles of value. If nothing is provided, the project is likely of little value and not worth your time.
2. **Don’t Rely on Empty Promises**: Perseverance requires substance. Sustainable effort comes from working on something valuable that you slowly build over time.
3. **Maintain a Main Occupation**: Having a stable means of livelihood is essential to support your dreams. Alternatively, if a project offers valuable resources and connections, it’s worth your time.
4. **Be Ready to Pivot**: Don’t be afraid to change direction. Don’t get stuck on one path, and don’t fear making mistakes. No compensation means no obligation. While responsibility is generally encouraged, it should never come at the cost of your own well-being.

# Project Summary
I can’t say I was entirely blameless in this group. In fact, I started from scratch with Lua and found that learning the entire codebase took longer than expected. Weakly typed languages and game client development differ somewhat from game server development. I spent more time than I anticipated getting up to speed with the basic project framework. This experience taught me that understanding open-source projects and helping with them is a rare skill. Reading others' code has its own set of challenges, not just in terms of language, framework, and design but also in navigating without real-time answers. When no one is there to provide guidance, how do you learn from just the source code and runtime environment (if the project even doesn't have one)? This challenge includes whether we have enough free time to dedicate to these projects.

So, asking "Why am I doing XXX?" is a very valuable question. If it’s for a better-looking resume, then it might be more effective to just study for interviews, practice coding problems, and learn about frameworks and common design patterns. If you think it’s "interesting," then consider whether the project’s level of fun is enough to replace your usual leisure activities (like travel, gaming, or socializing). If not, then maybe it’s not worth pursuing. If it’s to learn a trending technology, is that technology really worth your time? Perhaps it’s better to figure these things out before diving in.

Additionally, studying someone else’s project code can be incredibly tedious. Programming offers a lot of creative freedom, so everyone has their own design solutions. Despite coding standards, people often get stuck in their own way of thinking. It’s essential to have an open mind when trying to understand code. More importantly, when facing difficulties, it’s crucial to assess the project’s value and make the most of every moment. After all, your free time should belong to you.

Finally, remote communication is fraught with noise. A single word or sentence can easily be misinterpreted, which is why technical documentation is so important. Good documentation should be unambiguous and able to convey a lot of information, sometimes even more important than the code itself. Especially when communication is not face-to-face, how to maintain alignment and move forward together is a complex issue. In my two months on this project, I’ve realized that both parties must have high technical skills, excellent communication, and sufficient patience and responsibility for things to progress smoothly. This might be why remote work tends to favor hiring senior developers.

# Thoughts on Open Source
This section is not directly related to the passion-driven project but is also a reflection from the past two months.

Since May 2023, I’ve started playing Counter-Strike again, a game whose abbreviation, CS, coincidentally matches Computer Science. Sometimes I find it quite fitting, as I chose CS as my major in university, worked in the CS field, and now am almost "addicted" to the game CS.

One recent insight comes from a discussion by a CS streamer, Shyeark, about what it takes to become a professional CS player. In this [video](https://www.bilibili.com/video/BV16T4y1e7HA), Shyeark mentions that many talented CS players reached the top ranks with around 700 hours of playtime, after which they were invited to join professional teams. On the other hand, most casual players with dreams of "going pro" lack the talent necessary to become professional players. Shyeark concludes that most professional players became pros simply because they genuinely enjoyed playing CS
, discovered they could play at a higher level, and wanted to compete with better players.

I see a similar pattern among open-source project maintainers. Take, for instance, Vue’s creator, Evan You, who developed Vue in his spare time while working at Google. Due to its simple and user-friendly design, it quickly gained attention from developers. But initially, the core team only had four members [at the 15:06 mark of this video](https://www.bilibili.com/video/BV1L7411M7Ut). This shows that most people can’t truly contribute to GitHub projects because they lack the necessary passion and talent (yes, I’m talking about myself). Uploading your code as open-source and maintaining it for the community without compensation is similar to how current CS
pros practice their skills, learn new strategies, and compete in tournaments without a robust support system like that of League of Legends. It requires both passion and talent. Only with enough passion can they keep striving for something intangible, and only with talent can they reach the pinnacle of their skills and gain global recognition and support.

Finding a valuable project, sticking with it, and waiting for a result, whether good or bad, is a process that will always yield some reward.

Open-source developers who contribute for recognition alone, like those who play CS
just to become professional players, won’t last long. The only sustainable motivation for such unpaid endeavors is passion and habit. Apart from the external rewards of money, fame, or honor, ask yourself: does what you do in your spare time truly bring you joy? If not, then perhaps it’s not worth the effort.

I remember the autobiography of Linux creator Linus Torvalds titled *Just For Fun*. It also brings to mind an interview with Meiko, a support player for EDG who won multiple championships, where he mentioned something like, "League of Legends is genuinely fun." Linus didn't start writing Linux with the idea of "creating a better operating system than UNIX," and Meiko didn't start playing LOL with the belief that he would become the world's best support player. But eventually, they both achieved their goals, driven by passion and persistence.

Honestly, I’m not yet at a point where I can quickly dive into an unfamiliar field, nor have I found an open-source project that I’m particularly passionate about. So, for now, I'll focus on my job, read more books, and explore open-source projects to broaden my horizons, all while waiting for "that project" that truly resonates with me.
