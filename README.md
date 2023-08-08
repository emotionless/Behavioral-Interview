# [Leadership principles](https://leetcode.com/discuss/interview-question/437082/amazon-behavioral-questions-leadership-principles-lp)
[LP meaning at interviewgenie](https://interviewgenie.com/blog-1/category/Amazon+interviews)
### 1. Tell me about a situation where you had a conflict with someone on your team. What was it about? What did you do? How did they react? What was the outcome? 
(S) I got conflict with one of my team mates during pair review. (T) I wrote code for a feature about profile picture of an user. So in order to make it fast I compressed user's image and then stored it in device's memory. But my team mate told me to fetch the image from online storage everytime cause stored image was less quality then the original. And it kills space on user device. (A) But I wasn't agree with him because fetching data everytime will take time and keeps user waiting. And it is bad expericence for user. So we talked with my manager and after hearing these both solution (R) he suggested a hybrid solution that by default image will be showed from local cache. But when a user clicks on his picture to see it in full screen then we will fetch the original image from online storage. It should be fine for user and us. I followed this hybrid approach and from then I follow this idea for images/data which have frequent usage.

Also I summed up with cache eviction policy after every 10 mins.

(S) I got conflict with one of my team mates during pair review. (T)Before pushing my changes to remote I ask my team member for peer review. He told me to change the commit message that he provided after reviewing. I could not agree with him as I think my message was enough descriptive to me. (A)So we showed both messages to manager. After reviewing both messages he changed into new one. (R) Now we follow a format provided by my manager for commit messages. This happens because English isn't our native language and sometimes we face problems to describe.

(S) Got conflicted with my manager. (T) On the eve of my religious festival he told me to work on festival day. (A) I didn't agree with him because if I would work during that time then it would take my happiness with my family far apart and that would give me suffer in the long run. So I explained why I was not interested to work during that time. (R) He understood my point and told me to reach him if I need any extra leaves for this.

TODO: Conflict with customer

(S) Got conflict with my coworkers when I designed virtual nodes' heat detection and mitigation. (T) I proposed a new library/package for detecting heat and mitigate it. But my coworker suggested to integrate this with our current design since if I create new package it increase dependencies to other packages for our project. (A) So I arranged one-to-one call with him and explained the advantages that we may get if we make this one as library. He explained library needs to be maintained separtely but if we integrate it with current design, we don't need to think about the upgrade option. (R) We concluded to make a new library for this one with some suggestions from him.

### 2. Give an example of when you saw a peer struggling and decided to step in and help. What was the situation and what actions did you take? What was the outcome?
(S) One of my team members / colleagues was struggling in his assigned task. (T) He was assigned to understand a feature and implement another feature which was almost similar to that. (A) The assigned person wasn't fresher in job experience. He worked in R&D team and them he joined my team. So was new in SDE. When I saw that he was struggling and might miss the assigned date I decided to step in and helped him. First I understood his knowledge about the project and internal tools. Then when I found both of them were not sufficient to complete the feature so I helped him explaining my knowledge about my project in simple way and then provided him some useful links of internal tools which needs for my project. We also had lunch for several times and discussed in case of any confusion.
(R) As a result I saw that he could meet his deadline and was interested to take new challanges willingly. I also learned many things and became clear about some concepts.

(S) One of my team members was struggling on the polling task. (T) The task was to poll metrics for some cache nodes from Host Manager service. (A) I stepped into the task and explained what should we need (service principles, white listing of accounts etc) to get data for oversubscribing. Also I provided some documents which explains why this is needed (security, quota etc) and how to achive them. (R) After some guidelines, I saw he could meet the deadline and was interested to take new challanges willingly. I also learned many things and became clear about some concepts.

### 3. Tell me about a time you committed a mistake?
(S) In my current job once I had to fetche all AiModels assigned to a specific tenant. (T) So I had to write a sql query to fetch the aimodel list. (A) I wrote the query in inefficient way. My plan was to make query on indexed column. But when I wrote the code I forgot to create index at that column. When describing to my manager I explained that it would be indexed column. It was fine in local machine but taking long time in live application.
I rechecked all the code if I made any mistakes. I found nothing in the source code. Then I checked my documentation about the process and found that I forgot to add index. Then I wrote down that mistakes into my list so that I never repeat them again. (R) Now before submitting any changes of my code I recheck if source code and planned (Documents) are same or not. Also check my mistake list so that I never repeat those mistakes again.

(S) In my current team I created an alarm to detect if any DMSHost monitors more/less vitual nodes than prediction (anomaly detection). (T) I tested this one with few virtual nodes and was working fine. But when it went to the production, DMSHost is created according to load. So it triggered lots of alarms frequently. It caused problem to the person who was oncall.(A) I had to fix that with CPU percentage usage of DMSHost. Then I wrote down that mistakes into my list so that I never repeat them again. (R) Now before submitting any changes of my code I recheck if source code and planned (Documents) are same or not. Also check my mistake list so that I never repeat those mistakes again.

### 4. Tell me about a time when you earned your manager's trust?
(S) It was after joining to my current company. As I am new here so it is not obvious that he knows me well. (T) So I need to earn his trust by my work. (A) I asked my co-worker about my boss activities. I mean what he likes or dislikes and which approaches he follows. I found something useful that must be acquied to earn his trust like letting him know which tickets I am working right now, what's the ticket status, constant update, constant check-in, and letting him know then task is finished. Also he likes to be consistant on those. Above all, I need to communicate with him by myself. Then making consistently good decision like which approaches/tools would be best for a case and why, which features should be given more emphasized, prioritizing tasks etc. Not only taking decision but also keeping commitment with those decisions. Also hearing others idea and check why it is good and why not good, compare my task with the highest standard (Reading blogs, and checking how other developers work), tell directly to managers/teammates when I fail, and helping others when they need help. (R) I heared once he told to my team-mates that I the Sachin TendulKar (!) of my team. By following these process, right now I am used to these process in my personal life !

### 5. Tell Me About a Time When You Failed to Meet a Deadline. What Things Did You Fail to Do? What Were the Repercussions? What Did You Learn? (Customer obsession, ownership, deliver result)
(S) In my current project when I was working on Graphical view of endpoints (Cameras) I had to write the code flow for that module. In my team it is strictly followed that everyone should write the code flow after implementation. I follow this so that any new guy in my team can understand source code easily. (T) So I also needed to write code flow of that feature. I had 3 days in my hand. (A) So I wasn't much serious about it because I thould I would be able to finish that within single day. So I spent first two days with some less important taks like refactoring my code, changing into more meaningful variable name etc. At 3rd day when I started writing code flow I saw that there are lot of things that I need to write also. And I was not concern about those. (R) So basically I failed to deliver that task on that day. I needed one more day to complete. After explaing this, I requested my boss to increse it for one more day. He agreed with me as it was a mistake and told me not to repeat the same again. There are several thinkgs that I learned from it.
> 1. Never think anything less important unless you are familiar to it
> 2. Try to complete your task at the first part of assigned time
> 3. Make a priority list to complete your task
> 4. Update your plan to boss so that he can guide you in any time
I write down all my mistakes in a list so that I never repeat them.

### 6. Tell me about a time when you invented something? (Invent and Simplify, Ownership)
(S) When I worked on Samsung, during developemt, one device could get only one time data for testing. In order to get new data we needed to reinstalled the app. It was boring. Besides, server provided data only one time because that server was using for another large application (S-Health). (T) So I decided to do some mechanism so that server doesn't get load and from mobile site we get latest data. (A) I thought a mechanism that I will shift the data from old to new. I did this by myself. But I face serveral challanges because every table's timestamp was unique. When I tried to shift them I got serveral exception because of unique constrant. So I took a backup of data to temp, then delete all the data from main database then tried to add timestamp with each entry. (R) By this way, we could solve our problem and it saved our time to negotiate with server team and also it decreased server load time and increased our productivity. 

### 7. Tell me about a time when you took important decision without any data? (Frugality, Learn and Be Curious, Dive Deep)
(S) When I was fresh student of my graduation time I participated serveral online programming competitions. (T) Suddenly some of my friends stopped participating in the competitions. I asked them the reason of not participating. They told me that there is no future of this kind of competitions. (A) As I am interested to be Software Engineer and logic is called the brain of a software so I continued. They told me that it will be useless of my hard works. During that time I didn't have any sufficient data to prove that competitions is really important for increasing thinking capabilities of an engineer. But I continued it as I love it and I have great enthuasism on it. (R) After participating many competitions in online and onsite I could make some good positions. I got offer from serveral local companies before competing my post graduation. And now as a software engineer I believe that business logic is the core part of a software. And still I am learning to improve it.

### 8. Tell me about a time when you helped one of your teammates? (Bias for action, Ownership, Deliver result)
(S) In my current project when I work on a service then sometimes I need to call another service through gateway. When I was about to finish a task I saw that some test cases were not succeeded. (T) I rechecked everything and found okay from my side. But as in the service layer I need to call another service so it might had some possibilites that that service was providing wrong data. (A) So I by myself check that service and found that there are some missing cases there. I walked to him and informed about it. He also checked it and found the problems. But he was busy with other task. So I offered him that I could do it for him because at the end of the we had to finish the project before the deadline. After fixing those bugs I pushed that changes and added him as a reviewer . He reviewed and merged that changes. (R) Then the bugs were fixed and my module also passed for all cases. I got inner peace helping him.

### 9. Have you ever failed at something? What did you learn from it?
The interviewer wants to check these 3 topics -
1. Did you own it?
2. What did you learn from this mistakes/failure
3. What was the recovery/success?

(S) In second year of my graduation, I had a team of 4 people to complete our semester project. (T) We planned to make a management type project. We had only two weeks at our hand. (A) I took the responsibility to implement the backend. Others also took their interested part. I was confident about my task. But after that I got two assignments to complete whose deadline were before the project submit date. I tried my best to complete them according to deadlines. I had completed the assignments but realised that I might fail to complete my part. And that's it. I couldn't complete it. (R) Although we were marked well enough for designing, documentations, presentation, but I felt like I let everyone down.


Learnings -
After that, I knew that I needed to manage my time better. I needed to inform that status to my teammates. Then I started using project management software like checklist and priority list. After That semester, I had a similar group project, and I gave myself several weeks to complete my part. When I delivered everything a week early, my team was thrilled.
1. Inform your teammates/manager about your status
2. Ask them for help when you are stuck or think that it might not be possible to meet the deadline
3. Try to utilize time making a priority list

### 10. Tell me a time when you came up with novel solution?
(S) It happened at my current project when my team was using mysql for some services. After using some days disk was full. (T) We needed to free up the memory from our server. But all the data were so important. Besides, according to our design the server should be run for 5 years in memory. (A) I took the responsibility to fix it from those servers. Some of us also tried but no one didn't find any solution. Some of us also suggested to change the servers. But I requested my manager to give me time before moving into another. Previously one of us faced the same issue and he solved it moving into another. But after analyzing I found that mysql was taking more spaces than necessary. And it was taking log of each query to make future query faster. But this log/cache were so huge that our server ran out of memory. (R) Then I removed them and fixed the problem. Also I impelemnted a scheduler that automatically delete those logs/cache when total memory consumption is > 70%. 

### 11. Tell me a time when you received negative feedback from manager and how you responded?
(S) It happend at my previous company. All employees need to start office before @10 am sharp. Due to some problem in my family I went to bed late night. So I was late for couple of days consecutively. (A) Once during scrum meeting my manager told me that I was not serious about the time of entrance. I also realized that I was late for several days. I told her that I was sorry and would try to overcome that soon. So after the meeting I went to my manager and share my problem with her. (R) She told me that now she can realize the problem and promised me help in any circumstance. When I overcame my problem then again I could reach office timely and thanked her help.

### 12. Tell me a time when you went above and beyond your job responsibilities?
(S) Let me tell you a time when I went above and beyond my job responsibilities. When I was working on my current project, sometimes my manager needs to delete container, model or firmware. There are a lot of dependencies and sometimes were not synchronized properly. (T) So I thought to make a feature for my manager to do this task easily. (A) I developed a feature for testing for my manager as well as others (Like PDM, testers) that calling an API with secretToken will delete all dependencies for model, container and firmware. And it will add some significant demo data to database so that presentation/testing becomes easy for anyone. (R) This feature were really amazing when anyone faced problem with synchronization. Also then my manager decided to keep this feature as hidden feature of my project!

### 13. Tell me  a time when you helped someone grow in career and it benefited them?

(S) When I was in my last company I had about 13 members in my teams. In order to increase employees efficiency Samsung organizes Coding Challanges among all employees. Those who get good scores are promoted according to their coding level. (T) I passed that level just after joining and planned to help my team to increase logical thinking. (A) So I took several sessions, guided them, provided feedback and many more. (R) Among them, 8 people could pass that level and the rests also improved their logical thinking. It helped to make better project and thinking efficiency before any task. It also helped them to ace interviews and new challanges.  

### 14. Tell me a time when you helped some grow and it didn't benefit them?
> Need to recheck this answer
 
(S) When I was final year student I took a course called "Graph Theory". (T) I suggested one of my friends to take that course as most of us were taking it as a interest. (A) He also took that course. But I saw he was struggling on the midle of that period. I helped him from my side as possible and once I understood that he was not much interested with that course. But he took that course because all of this friends had taken that course. So I felt guilty for this. Besides, his interested was to be a banker. (R) After struggling a lot, he could pass with lower grade than us. So after completing his graduation he joined at a bank. And till now that course/theory didn't help me much.
Learning - 
1. Know once's interest and suggest
2. Help as much possible when someone stuggle
3. Do/Take which things that comes from your mind

### 15. Tell me a rime when you were 75% through a project and realized you had the wrong goal?
(S) It happened with me when I was at Samsung. I was working on an ios project. (T) I designed and implemented client site database by myself. But when my manager pull that request she saw that android and ios database design for client side cache were different. (A) She called me and told me to follow android design as all of us were following android desgin and we will keep all client side database similar. I was not agree with her and discussed with android guy. He show me some advanced design that will be followed in next version and that's why his design was scalable. (R) I understood his design and got the answer to follow him. From then we discuss with others when finalize design.

### 16. Tell me a time when your team members were not supporting something but you pushed and went for a more optimal solution?
(S) It happened when in my current project. When I was working on a service I needed to verify an user which is maintain in another service. I was getting error for some users. (T) I informed this issue to the responsible person but was not getting response from him actively. (A) So I went to him and asked if he could check that because I was stuck to verify. During that time he was busy in another task so he wasn't active with me. I offered him to check collaborately and found that for testing he added some special checks which should not be added there. I offered him to mock the DAO layer and remove those checks. When he finished others dependencies he implented those according to my suggestions. (R) He used this mockito to test other modules also and removed all kind of extra checks. And it made him tenseless.

### 17. Tell me a time when you pushed back a decision from your management for better long term benefits?
(S) I pushed back a decision with my project lead about changing team. (T) There were no new tasks/features to the new team. That was only supporting team. But as a developer I want to explore and try to get the best solution of a problem. I like these kinds of thing very much. (A) So I disagreed with my lead and refused to join to the new team. And I gave him some options where I will feel comfort about the tasks. (R) Then he assigned me to another team from my choose list. I also did well to that team and my lead was very pleased to me.

### 18. Tell me about yourself?
I completed my post graduation from JU in 2017. I am an innovative software engineer with more than 3 years of experience developing and managin all aspects of software with small or medium-sized team. My current company is AnyConnect. Here I am in charge of developing and managing 4-5 microservices. We prioritize custommer requirements, efficent design, documentation and scalable system. In 2020, our plan was to get 3 customers. And our product is so cool that we got 5!!! When I was working with graphical view of all cameras, I used google map with satelite view to show the cameras. It is really cool. From then I am really interested to work such kinds great projects. So I am really interested to work at google.

### 19. Tell me a time when you were working on a project on a time constraint?
(S) When I was a student of final semester of final year, I with two other had to complete a project. (T) I planned and designed about our tasks and features. But suddenly heard that my head examiner was planning to give convocation to us. So he wanted to finish the project soon. (A) As time was less than the planned so I talked with my supervisor and eliminated some extra features which were less important during that short time. (R) When I submited that I were marked good enough as I completed main features of that project.

### 20. Time when you needed help from somebody?
(S) I was at SRBD. I had to complete localization task for my team. (A) Localization feature was new in my team so I was searching a person from whom I can get help. I had a friend in another team who also completed localization feature for her project. So I asked her to help me. I went to her desk and spend times to understand the way of implementing/using localization. (R) After that I implemented that feature to my project and completed that successfully.

### 21. Tell me about a time you faced an obstacle/problem and how you overcame it?
(S) I faced a problem in my current company when I merged some code changes. (T) I created a pull request and that created other services in deadlock. (A) In order to overcome the same kind situation not only for me but also for all, I planned and implemented a system test which would be trigger after each commit. If all tests passed then anyone can request for pull. (R) Now I am less tensed then previous also all my other team members got releaf from tension about new changes.

### 22. Tell me a time you took some risks?
(S) When I was at samsung, we had a presentation to show our client about our project. (T) I completed my task clearly for the version that I had. Others also did the same. But when we glued all features into one then we saw that some pages were broken. It happened because of ios version. (A) I addressed this issue to my manager and it was just before the demo day. So I asked my manager about the specific version which will be used during presentation. I heared the version and told everyone to make it workable on that version at least. It was risk for us because we were presenting infront of client and we did it as it wass just only demo project. (R) Luckily, everything went well during that time and we fixed the issue for all modules. Now it is responsive for all version.

### 23. Tell me a time when you learned new technologies?
(S) It was just after finishing my study and on the eve of my career life. (T) When I started working on Enosis my supervisor introduced a technology which will need for lifetime. It was git. (A) After hearing this name I searched on the internect and watched some videos. I found it really interesting and wished if I could learn this during my graduation life. If I would learn it during that time then I could save all of my works/code into remote so that I don't loose them. Then for learning more, I bought a book named ["Pro Git"](https://xiangxianzui.github.io/2018/05/git%E7%89%88%E6%9C%AC%E6%8E%A7%E5%88%B6/progit.pdf) by Scot Chacon. (R) After reading this book I could get rid of all confusion about git and now I suggest to everyone new joiners to learn git first if he/she hasn't learned yet. Now I maintain my works in git.

### 24. Tell me about a time you had multiple solutions and you had to select an optimal one?
(S) In my current project every user can see its location on the web. (T) One solution for this was to track locations of active users every time and then show them when get query result. And another solution is to get data from camera side when location is change in every 5 seconds. (A) I chosed the second one because it gives us almost live location. So it is almost latest. And I needed to pin that location to map. But we faced problem if in a second there are lot of changed location. Also one business account can't make more than 10 requests in a second. If I want to make more request then I need to pay. So I created multiple accounts so that whenever any account is full then I will make request through another account. (R) It gives us almost live location and serves our purpose when free of cost which is profit for our company.

### 25. Tell me a time when you had limited time and what was it's impact? (Frugality)
(S) In my current company once we had to show our product to a new client. I was walking on the right direction in right way. (T) But suddenly for some problems the client wanted to meet with us earlier. (A) So I hadn't enough time to complete all the features that required. So I talked with my teams and listed out them according to priorities. Then I implemented the mostly used features and planned to implement the rest after the meeting. (R) The client was happy to see that most of the importants features were implemented and I completed the remaining features within next week.

### 26. Tell me a time when you Handled a tight deadline? (Frugality, Bias for action)
(S) Let me tell you a time when I was at SRBD. (T) We had to release first version of the project within 1 and half months. It was really tough for us to complete the required features with that short time. (A) I prioritized the features and completed followed them accordingly. Also during that time a new intern joined at our group (A group might have several teams). So I talked with him and described my plan of my project and asked if he was interested to work with me. After getting positive response I requested my manager to assign the intern with me. Besided, I talked with managers and co-workers to get important tips on how simply I can complete the tasks. (R) Following these approaches, when I am at the close of deadline I saw that I almost had completed all the impotant features that were required during that time. My manager was pleased with me.

### 27. How would you help a new employee who is facing technical difficulties? (Bias For action, Learn and Be Curious)
(S) When I joined at my current company I was totally new to this environment. I never used ubuntu as a professional before this company. (T) After 5/6 months of my joining a fresher joined at my team. And as it is pandemic time so it was hard for him to make his environment ready. (A) As I just completed those steps so I knocked him by myself about his status. He told me some difficulties that he was facing. I helped him doing that sometimes by screen sharing and sometimes accessing his pc. But he faced one problem that I also couldn't solve. So I asked our technical guy to solve this if possible as I am unable to fix it. He solved it and I saw the steps that he followed and learned it to solve for next time. (R) After somedays when I got one new pc so I had to setup environment newly. And I faced the same problems that the fresher faced during that time. And I could solved all of them without any help.

### 28. Tell me about tim when you faced a difficult challenge?
(S) When I was at SRBD I faced a difficult situation. (T) We had a release on the first day of week. So everything was working fine till diner. Most of my co-workers left office on that day. Normally I take diner at office. So I was testing my application as final test. During that time I faced some data inconsistancy (Like milliseconds) problem when I was sednding data from wearable device to my application. As next two days were weekend and release was at the beginning of week so I took that issue seriously. 
(A) Lickily my manager was also in office on that day. I informed this issue to him immediately. He called the person who developed that feature. But the responsible guy was already out of office on that day and he was on the way to his home. So I told my manager to help me to find the issue. Also the responsible person helped us on call. I found some inconsistency between data generated time and data sending time. I fixed it and commited the changes. (R) The issue was solved and my manager was happy with my insight.

### 29. Tell me about a time when you thought of an unpopular idea?
(S) I had an unpopular idea when I was at SRBD. (T) My manager called me and my team mates in a meeting room suddenly and told us to give any idea that could be submitted from my team. (A) During that time I approached an idea (Eye power, status detection) which was not popular at that time. Because in order to make this device we need more money than existing devices. And my plan was to integarte this with mobile devices. And it was also costly. So that idea wan't accepted. (R) Idea can be anything. Don't stop making idea. One day it might be worthy.

### 30. Tell me a time when you had conflicted idea with teammate and how did you resolve it?
(S) I got conflict with my team mate about a task who was supervising me during that time. (T) There are many ways to complete a task. I chosed the one which is easy. But supervisor told to to follow another way. (A) But I told him that as it was serving our current requirements so it would be better. He told me about some scalable system and I was totally new to this term. I verified this from other mates too. Then I learned it from him and appreciated his idea. (R) This learning guided me to think about scalable system during design and implementation. From then before going to implementation I always think about scalable system and pass this information to juniors also.

### 31. Tell me a time when you faced a setback initially but still achieved the goal?
(ST) In my current project I faced setback/difficulies when I was told to make backend and front end align. As our backed was almost ready so I needed to give more emphasis on front end. I sat with front end guy. (A) Initially it was difficult for me because I had no idea about front end which tools (Bootstrap, jquery) are using my project. Also sometimes I needed to provide some more APIs or modify existing API which makes more sense. But day by after learning from him and own study now (R) I can run parallerlly with him. First step for a new task is always difficult. If I give some extra effort without losing hope then everything is possible.

### 32. Tell me about a time when you felt under pressure that you wouldn't be able to get something done?
(S) When I was working at samsung my team got a new project. (T) I with my team mates needed to finish a mvp project withing a week. And similar project was also developing by another R&D center. And only one of them would get the project to complete. (A) As I am at Dhaka City so I tried my best to complete that project. But most of us were fresher and it was my first android project. I took a lot of pressure to complete my parts and to help others. I did my best withing that time. But as less experienced my project were not better than the competitor. (R) So we didn't get the project. But considering our work dedication and motivation my team got another B2B project.

### 33. Tell me a time when you had to take a pivot at the last minute?
(S) Let me tell you a story of 2017. (T) I participated a National Programming Competition. We were given some problems to solve. (A) It's length was 5 hours. When others team were able to solve 6 problems in 4 hours, we had only 4 !!! I was trying my best to solve but getting several bugs in my code. The last hour was the turning hour for me and my team. After checking code I found that one of my team mate missed some cases because he overthinked on some cases. I addressed them and he fixed them. And in the meantime I approached another problem from scratch and solved it at the eleventh hour. (R) At last I solved or helped to solve 4 problems in total where my team mates solved 3 and ranked 3. And champion team also solved 7 problems.



# Company Specific Questions
### 1. Why do you want to work here?

> Do not talk about salary Talk about product, culture, job description Talk about mutual connection's feedback who works at their company Long term goal

* Evaluate your intensions: make a quick list for why you want to work for the company and what inspire you most about the positions.

* Do your Research: Find out everything about the company and the positions

* Show that you're the solution to their problem:

* Be yourself and show your passion:

* Be specific with your examples:

 > Small company: "I want to be in a place where I'm not just a cog in the machine, and can have plenty of opportunities to grow."

 > Big company: "I want to be in a place where my work has an impact on millions of users."

## Quora
### 2. Why Do you want to work at Quora?

>Quora has a millions of user and I always wanted to work in a global company where my work will create an impact on these huge number of people. I wanna grow myself as a full stack software engineer. And in quora I'll get the opportunity to work with from Machine Learning to Distributed Systems. Also If I'm not wrong, then quora uses Continous Integration, so I don't have to wait weeks before I can see my code live. That's very fascinating to me.


[Behavioral interview](https://linlaw0229.github.io/2019/06/29/Amazon-behavioral-prepare/)

[All questions that are asked in Amazon LP](https://www.youtube.com/watch?v=RMA7tI-LTWY&ab_channel=DanCroitor)
[In text](https://pastebin.ubuntu.com/p/vBGThQzyvg/)
> Check it's description

> SBI = Situation Behavior Impact rules

## Importants things to keep in mind
* STAR = Situation, Task, Action, Result
* Research the company and your interviewers
* Get a list of 10 interesting questions
* You are almost certain to encounter certain questions, for example, a quick overview of your recent project, your top strengths, your development areas, why you apply to this role. You should have very crisp answers to these questions.
* Bigest strength -> Related to roles with story (Taking initiative)
  1. Started System test for my team
  2. Started weekly practice session
  3. Started feeback session anonymously
  4. Started weekly knowledge transer with my team so that everyone becomes up to date with latest code
  
* Weakness -> Don't relate too much with roles
  1. Feel sleepy during metting if meeting helds right after lunch
* 

### 3. Do you have any questions?
Ask critical/hard questions.
1. What's the work expectation here? How does that balance with life?
2. How does the reward structure work there? I mean if people do really good job's then how does the company reward them?
3. If I pass phone interview, Where will my onsite interview be held?
4. What's the training proccedures for freshers.
5. As far as I know it is hard to get Switzerland's visa from BD when I have experience less than 5 years. So what will happen if I don't get visa?
6. What do you expect from me after 5 years?
7. What does google do for career growth of an employee?
8. What will be the focus area during the interviews? How do you decide who interviews candidates?
9. What is the expected time to come back with a solution during the interview?
10. What should I prepare for the interview?
11. What are the most likely reasons candidates get rejections?

1. Can you tell me more about the day-to-day responsibilities of this job? 
2. How do you define success for this position? What metrics are you using to measure my accomplishments?
3. Do you have any hesitations about my skills or experience for this job?
4. Where do you think the company is headed in the next 5 years?
5. What are the biggest opportunities facing the company/department right now?
6. What have been the biggest challenges this year for the team?
7. What do you like best about working for this company?
8. What are the opportunities for advancement and growth in this position?
9. Why did you decide to join this company?
10. What are your favorite and least favorite things about working here?
