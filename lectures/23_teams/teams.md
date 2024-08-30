---
author: Christian Kaestner
title: "17-445: Fostering Interdisciplinary Teams"
semester: Spring 2022
footer: "17-445 Machine Learning in Production, Christian Kaestner"
license: Creative Commons Attribution 4.0 International (CC BY 4.0)
---

# Fostering Interdisciplinary Teams

(Process and Team Reflections)

Christian Kaestner

<!-- references -->

Required reading: Nahar, Nadia, Shurui Zhou, Grace Lewis, and Christian Kästner. "[Collaboration Challenges in Building ML-Enabled Systems: Communication, Documentation, Engineering, and Process](https://arxiv.org/abs/2110.10234)." In International Conf. Software Engineering, 2022.



---

# Learning Goals

* Understand different roles in projects for AI-enabled systems
* Plan development activities in an inclusive fashion for participants in different roles
* Diagnose and address common teamwork issues
* Describe agile techniques to address common process and communication issues


---
# Case Study: Depression Prognosis on Social Media

![TikTok logo](tiktok.jpg)


----
## The Project

* Social media company of about 15000 employees, 500 developers and data scientists in US
* Use sentiment analysis on video data (and transcripts) to detect depression
* Planned interventions through recommending different content and showing ads for getting support, design for small group features
* Collaboration with mental health professionals and ML researches at top university


---
<svg version="1.1" viewBox="0.0 0.0 800 400" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg">
        <style>
    text { font: 60px sans-serif; }
        </style>
        <circle r="180" cx="250", cy="200" fill="#b9ff00" fill-opacity="0.514" />
        <circle r="180" cx="550", cy="200" fill="#ff5500" fill-opacity="0.514" />
        <text x=230 y=160 dominant-baseline="middle" text-anchor="middle">Data</text>
        <text x=230 y=240 dominant-baseline="middle" text-anchor="middle">Scientists</text>
        <text x=570 y=160 dominant-baseline="middle" text-anchor="middle">Software</text>
        <text x=570 y=240 dominant-baseline="middle" text-anchor="middle">Engineers</text>
</svg> 

----
## Data scientist

* Often fixed dataset for training and evaluation (e.g., PBS interviews)
* Focused on accuracy
* Prototyping, often Jupyter notebooks or similar 
* Expert in modeling techniques and feature engineering
* Model size, updateability, implementation stability typically does not matter

<!-- split -->

## Software engineer

* Builds a product
* Concerned about cost, performance, stability, release time
* Identify quality through customer satisfaction
* Must scale solution, handle large amounts of data
* Detect and handle mistakes, preferably automatically
* Maintain, evolve, and extend the product over long periods
* Consider requirements for security, safety, fairness

----
## Continuum of Skills

* Software Engineer
* Data Engineer
* Data Scientist
* Applied Scientist
* Research Scientist


<!-- references -->
Talk: Ryan Orban. [Bridging the Gap Between Data Science & Engineer: Building High-Performance Teams](https://www.slideshare.net/ryanorban/bridging-the-gap-between-data-science-engineer-building-highperformance-teams/3-Software_Engineer_Data_Engineer_Data). 2016

----
![Unicorn](unicorn.jpg)
<!-- .element: class="stretch" -->


----

![Roles Venn Diagram](roles_venn.svg)
<!-- .element: class="stretch plain" -->

By Steven Geringer, via Ryan Orban. [Bridging the Gap Between Data Science & Engineer: Building High-Performance Teams](https://www.slideshare.net/ryanorban/bridging-the-gap-between-data-science-engineer-building-highperformance-teams/3-Software_Engineer_Data_Engineer_Data). 2016


----
## Data Scientists At Microsoft


* Mostly analyzing product and customer data
* User engagement (which features users like and use, satisfaction, retention)
* Software productivity (bug priorization, monitoring)
* Domain-specific problems (NLP quality, stock pricing, power prediction)
* Business intelligence (predicting investment, demand, sales)

<!-- references -->
Kim, Miryung, Thomas Zimmermann, Robert DeLine, and Andrew Begel. "[Data scientists in software teams: State of the art and challenges](https://andrewbegel.com/papers/data-scientists.pdf)." IEEE Transactions on Software Engineering 44, no. 11 (2017): 1024-1038.g

----
## Data Science Roles At Microsoft


* Polymath
* Data evangelist
* Data preparer
* Data shaper
* Data analyzer
* Platform builder
* 50/20% moonlighter
* Insight actors

<!-- references -->
Kim, Miryung, Thomas Zimmermann, Robert DeLine, and Andrew Begel. "[Data scientists in software teams: State of the art and challenges](https://andrewbegel.com/papers/data-scientists.pdf)." IEEE Transactions on Software Engineering 44, no. 11 (2017): 1024-1038.

----
## Many other Role Descriptions

* Data scientist
* Data analyst
* Data architect
* Data engineer
* Statistician
* Database administrator
* Business analyst
* Data and analytics manager

<!-- references -->
e.g.  Martijn Theuwissen. [The different data science roles in the industry](https://www.kdnuggets.com/2015/11/different-data-science-roles-industry.html). 2015

----
## Many other Role Descriptions

* Product Data Analyst (feature analysis)
* Business Intelligence, Analytics & Reporting (marketing)
* Modeling Analyst (financial forecasting)
* Machine Learning Engineer (user facing applications)
* Hybrid Data Engineer/Data Scientist (data pipelining)
* Hybrid Data Visualization Expert (communication, storytelling)
* Data Science Platforms & Tools Developer (supporting role)

<!-- references -->
e.g.  Yorgos Askalidis
. [Demystifying data science roles](https://towardsdatascience.com/what-kind-of-data-science-role-is-right-for-you-9d2f4b117e81). 2019


----
## Evolution of Data Science Roles

<!-- discussion -->

*More or less engineering focus? More or less statistics focus? ...*

----
## Software Engineering Specializations

* Architectures
* Requirements engineers
* Testers
* Site reliability engineers
* Devops
* Safety
* Security
* UIX
* Distributed systems, cloud
* ...


----
## Needed Roles in Depression Prognosis Projects?

![TikTok logo](tiktok.jpg)

----
## Common other Roles in ML-Enabled Systems?

* **Domain specialists**
* Business, management, marketing
* Project management
* Designers, UI experts
* Operations 
* Safety, security specialist
* Big data specialist 
* Lawyers
* Social scientists, ethics
* ...









---
# Interdisciplinary Teams

----
## Unicorns -> Teams

* Domain experts
* Data scientists
* Software engineers
* Operators
* Business leaders


----
## Necessity of Groups

* Division of labor
* Division of expertise (e.g., security expert, ML expert, data cleaning expert, database expert)

----
## Team Issues

* Process costs
* Groupthink
* Social loafing
* Multiple/conflicting goals










---
# Team Issue: 
# Process Costs

----

# Case Studies

Disclaimer: All pictures represent abstract developer groups or products to give a sense of scale; they are not necessarily the developers of those products or developers at all.

----

## How to structure teams?

Microblogging platform; 3 friends

<!-- colstart -->
![Small team](team4.jpg)
<!-- col -->
![Twitter](twitter.png)
<!-- colend -->

----
## How to structure teams?

Banking app; 15 developers and data analysts

<!-- colstart -->
![Small team](team15.jpg)

*(Instagram had 13 employees when they were bought for 1B in 2012)*
<!-- col -->
![PNC app](pnc.jpg)
<!-- colend -->




----
## How to structure teams?

Mobile game; 
50ish developers;
distributed teams?

![Team 50](team50.jpg)
----
## How to structure teams?

Mobile game; 
50ish developers;
distributed teams?

![Team 200](team200.png)

----
## How to structure teams?

Self-driving cars; 1200 developers and data analysts

<!-- colstart -->
![Large team](team1200.jpg)
<!-- col -->
![Uber self driving car](uber.png)
<!-- colend -->


----
## Mythical Man Month

> Brooks's law: Adding manpower to a late software project makes it later

![](mmmbook.jpg)

1975, describing experience at 
IBM developing OS/360

----
## Process Costs

![](connectedteams.png)
<!-- .element: class="stretch plain" -->

*n(n − 1) / 2* communication links within a team
----
## Brook's Surgical Teams

* Chief programmer – most programming and initial documentation
* Support staff
    * Copilot: supports chief programmer in development tasks, represents team at meetings
    * Administrator: manages people, hardware and other resources
    * Editor: editing documentation 
    * Two secretaries: one each for the administrator and editor
    * Program clerk: keeps records of source code and documentation
    * Toolsmith: builds specialized programming tools
    * Tester: develops and runs tests
    * Language lawyer: expert in programming languages, provides advice on producing optimal code.

<!-- references -->

Brooks. The Mythical Man-Month. 1971

Note: Would assume unicorns in today's context.

----
## Microsoft's Small Team Practices

* Vision statement and milestones (2-4 month), no formal spec
* Feature selection, prioritized by market, assigned to milestones
* Modular architecture
* Allows small federated teams (Conway's law)
* Small teams of overlapping functional specialists

(Windows 95: 200 developers and testers, one of 250 products)

----
## Microsoft's Feature Teams

* 3-8 developers (design, develop)
* 3-8 testers (validation, verification, usability, market analysis)
* 1 program manager (vision, schedule communication; leader, facilitator) – working on several features
* 1 product manager (marketing research, plan, betas)

----
## Microsoft's Process

* "Synchronize and stabilize"
* For each milestone
    * 6-10 weeks feature development and continuous testing
frequent merges, daily builds
    * 2-5 weeks integration and testing (“zero-bug release”, external betas   )
    * 2-5 weeks buffer

----
## Agile Practices (e.g., Scrum)

* 7±2 team members, collocated
* self managing
* Scrum master (potentially shared among 2-3 teams)
* Product owner / customer representative

----
> Large teams (29 people) create around six times as many defects as small teams (3 people) and obviously burn through a lot more money. Yet, the large team appears to produce about the same mount of output in only an average of 12 days’ less time. This is a truly astonishing finding, through it fits with my personal experience on projects over 35 years. - [Phillip Amour, 2006, CACM 49:9](https://dl.acm.org/citation.cfm?id=1151043)

----
## Establish communication patterns

* Avoid overhead
* Ensure reliability
* Constraint latency
* 
* e.g. Issue tracker vs email; online vs face to face


----
## Establishing Interfaces

* When dividing work, need to agree on interface
* Common source of mismatch and friction
* **Examples?**
    - Team A uses data produced by Team B
    - Team C deploys model produced by team A
    - Team D uses model and needs to provide feedback to Team A
    - Team D waits for improvement/feature from model A
*
* Ideally interfaces are stable and well documented

----
## Awareness

* Notifications
* Brook's documentation book
* Email to all
* Code reviews

----
## Conway’s Law

> “Any organization that designs a system (defined broadly) will produce a design whose structure is a copy of the organization's communication structure.” — Mel Conway, 1967

> “If you have four groups working on a compiler, you'll get a 4-pass compiler.”

----
## Congurence

![](congruence.png)
<!-- .element: class="plain" -->

Structural congruence,
Geographical congruence,
Task congruence,
IRC communication congruence


----
## Engineering Recommendations for Structuring AI-Enabled Systems

* Decompose the system
* Independent components (e.g. microservices)
* Isolate AI if possible
* Clear, stable interfaces, minimal coupling
* Monitoring to observe contracts and quality

----
## Team Structure for Transcription Service?

![Temi screenshot](temi.png)


----
## Breakout: Team Structure for Depression Prognosis

In groups, discuss and post to slack `#lecture`:
* How to decompose the work into teams?
* What roles to recruit for the teams

![TikTok logo](tiktok.jpg)


---
# Story Time: Conflicts at the Interface between Teams

----
![Team collaboration within a large tech company](team-collaboration1.png)
<!-- .element: class="stretch plain" -->

----
![Team collaboration within a large tech company](team-collaboration2.png)
<!-- .element: class="stretch plain" -->

----
## Common Challenge: Establishing Interfaces

* Formal vs informal agreements?
* Service level agreements and automated enforcement?
* Close collaboration vs siloed teams?
* 
* Many concerns: prediction accuracy, generalization, execution time, scalability, data quality, data quantity, feedback latency, privacy, explainability, time estimation, ...
* Formal agreements and enforcement expensive, slowing development? see technical debt

----
## Common Collaboration Points

 1. Understanding system requirements and ML capabilities
 2. Understanding ML-specific requirements at the system level, reasoning about feedback loops
 3. Project planning and architecture design
 4. Data needs, data quality, data meaning
 5. Documenting model output
 6. Planning and monitoring for drift
 7. Planning ML component QA (offline, online, monitoring)
 8. Planning system QA (integration, interaction, safety, feedback loops)
 9. Tool support for data scientists 
 10. From prototype to production (pipelines, versioning, operations, user interactions, ...)




---
# Team issues: Multiple/conflicting goals

(Organization of Interdisciplinary Teams)


----
## Conflicting Goals?
![DevOps](devops.png)

----
## Conflicting Goals?


<svg version="1.1" viewBox="0.0 0.0 800 400" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg">
        <style>
    text { font: 60px sans-serif; }
        </style>
        <circle r="180" cx="250", cy="200" fill="#b9ff00" fill-opacity="0.514" />
        <circle r="180" cx="550", cy="200" fill="#ff5500" fill-opacity="0.514" />
        <text x=230 y=160 dominant-baseline="middle" text-anchor="middle">Data</text>
        <text x=230 y=240 dominant-baseline="middle" text-anchor="middle">Scientists</text>
        <text x=570 y=160 dominant-baseline="middle" text-anchor="middle">Software</text>
        <text x=570 y=240 dominant-baseline="middle" text-anchor="middle">Engineers</text>
</svg> 

----
## Conflicting Goals?

<svg version="1.1" viewBox="0.0 0.0 800 400" xmlns:xlink="http://www.w3.org/1999/xlink" xmlns="http://www.w3.org/2000/svg">
        <style>
    text { font: 60px sans-serif; }
        </style>
        <circle r="180" cx="250", cy="200" fill="#b9ff00" fill-opacity="0.514" />
        <circle r="180" cx="550", cy="200" fill="#ff0055" fill-opacity="0.514" />
        <text x=230 y=160 dominant-baseline="middle" text-anchor="middle">Data</text>
        <text x=230 y=240 dominant-baseline="middle" text-anchor="middle">Scientists</text>
        <text x=570 y=160 dominant-baseline="middle" text-anchor="middle">Compliance</text>
        <text x=570 y=240 dominant-baseline="middle" text-anchor="middle">Lawyers</text>
</svg> 


----
## Conflicting Goals?

![TikTok logo](tiktok.jpg)


----
## How to Address Goal Conflicts?

<!-- discussion -->

----
## T-Shaped People

*Broad-range generalist + Deep expertise*

![T-Shaped](tshaped.png)
<!-- .element: class="plain" -->

<!-- reference -->
Figure: Jason Yip. [Why T-shaped people?](https://medium.com/@jchyip/why-t-shaped-people-e8706198e437). 2018

----
## T-Shaped People

*Broad-range generalist + Deep expertise*

Example:
* Basic skills of software engineering, business, distributed computing, and communication
* Deep skills in deep neural networks (technique) and medical systems (domain)

----
## Team Composition

* Cover deep expertise in all important areas
* Aim for overlap in general skills
    - Fosters communication, same language





----
## Matrix Organization

![](teammatrix.png)
<!-- .element: class="plain" -->

----
## Project Organization

![](teamproject.png)
<!-- .element: class="plain" -->

----
## Case Study: Brøderbund

<!-- smallish -->

> As the functional departments grew, staffing the heavily matrixed projects became more and more of a nightmare. To address this, the company reorganized itself into “Studios”, each with dedicated resources for each of the major functional areas reporting up to a Studio manager. Given direct responsibility for performance and compensation, Studio managers could allocate resources freely.

> The Studios were able to exert more direct control on the projects and team members, but not without a cost. The major problem that emerged from Brøderbund’s Studio reorganization was that members of the various functional disciplines began to lose touch with their functional counterparts. Experience wasn’t shared as easily. Over time, duplicate effort began to appear.

<!-- references -->
Mantle, Mickey W., and Ron Lichty. [Managing the unmanageable: rules, tools, and insights for managing software people and teams](https://cmu.primo.exlibrisgroup.com/permalink/01CMU_INST/8lb6it/cdi_askewsholts_vlebooks_9780132981279). Addison-Wesley Professional, 2012.


----
## Specialist Allocation (Organizational Architectures)

* Centralized: development teams consult with a core group of  specialists when they need help
* Distributed: development teams hire specialists to be a first-class member of the team
* Weak Hybrid: centralized group of specialists and teams with  critical applications hire specialists
* Strong Hybrid: centralized group of specialists and most teams also hire specialists

**Tradeoffs?**

----
## Example: Security Roles

* Everyone: “security awareness” – buy into the process
* Developers: know the security capabilities of development tools and use them, know how to spot and avoid relevant, common vulnerabilities
* Managers: enable the use of security practices
* Security specialists: everything security

----
## Allocation of Data Science/Software Engineering Expertise?

![TikTok logo](tiktok.jpg)


----
## Commitment & Accountability

* Conflict is useful, expose all views
* Come to decision, commit to it
* Assign responsibilities
* Record decisions and commitments; make record available

----
## Bell & Hart – 8 Causes of Conflict

* Conflicting resources.
* Conflicting styles.
* Conflicting perceptions.
* Conflicting goals.
* Conflicting pressures.
* Conflicting roles.
* Different personal values.
* Unpredictable policies.

*Understanding causes helps design interventions. Examples?*

<!-- references -->
Bell, Art. (2002). [Six ways to resolve workplace conflicts](https://www.mindtools.com/pages/article/eight-causes-conflict.htm).
University of San Francisco

----
## Agile Techniques to Address Conflicting Goals?

<!-- discussion -->
















---
# Team issues: Groupthink

![](groupthink.png)

----
## Groupthink

* Group minimizing conflict
* Avoid exploring alternatives
* Suppressing dissenting views
* Isolating from outside influences
* -> Irrational/dysfunctional decision making

----
## Example: Time and Cost Estimation

<!-- discussion -->

----
## Example: Use of Hype Technology

(agile, block chain, machine learning, devops, AIOps, ...)

<!-- discussion -->

----
## Causes of Groupthink

* High group cohesiveness, homogeneity
* Structural faults (insulation,  biased leadership, lack of methodological exploration)
* Situational context (stressful external threats, recent failures, moral dilemmas)

----
## Symptoms

* Overestimation of ability: invulnerability, unquestioned believe in morality
* Closed-mindedness: ignore warnings, stereotyping; innovation averse
Pressure toward uniformity: self-censorship, illusion of unanimity, …
----
![](svposter.png)
----
## Diversity
<!-- smallish -->

> “Men and women have different viewpoints, ideas, and market insights, which enables better **problem solving**. A gender-diverse workforce provides easier **access to resources**, such as various sources of credit, multiple sources of information, and wider industry knowledge. A gender-diverse workforce allows the company to serve an **increasingly diverse customer base**. Gender diversity helps companies **attract and retain talented women**.”

> “Cultural diversity leads to **process losses** through task conflict and decreased social integration, but to process gains through increased creativity and satisfaction.”

<!-- references -->


Stahl, Günter K., et al. "[Unraveling the effects of cultural diversity in teams: A meta-analysis of research on multicultural work groups](http://leeds-faculty.colorado.edu/dahe7472/Stahl%202009.pdf)." Journal of international business studies 41.4 (2010): 690-709.

Sangeeta Badal. [The Business Benefits of Gender Diversity](http://www.gallup.com/businessjournal/166220/business-benefits-gender-diversity.aspx). Gallup, 2014

----
## Groupthink and AI-Enabled System Projects?

![TikTok logo](tiktok.jpg)


----
## Groupthink and AI

* Need of AI
* Selection of learning method
* Fairness
* Safety requirements (e.g. Pitt delivery robot)
* Ethics

----
## Mitigation Strategies

<!-- discussion -->

----
## Mitigation Strategies

* Diversity in team composition
* Culture of open conflicts
* Appoint devil's advocate in discussions, moderate and rotate speaker order, leaders hide opinions in discussions
* Involve outside experts
* Always request a second solution
* Monitoring and process measurement
* Agile techniques as planning poker, on-site customer
















---
# Team issues: Social loafing

![](tug.png)

----
![](loafinggraph.png)

<!-- references -->

Latane, Bibb, Kipling Williams, and Stephen Harkins. "[Many hands make light the work: The causes and consequences of social loafing.](http://web.mit.edu/curhan/www/docs/Articles/15341_Readings/Group_Dynamics/required_reading/4Latane_et_al_1979_Many_hands_make_light_the_work.pdf)" Journal of personality and social psychology 37.6 (1979): 822.

----
## Social Loafing

* People exerting less effort within a group
* Reasons
    * Diffusion of responsibility
    * Motivation
    * Dispensability of effort / missing recognition
    * Avoid pulling everybody / "sucker effect"
    * Submaximal goal setting
* “Evaluation potential, expectations of co-worker performance, task meaningfulness, and culture had especially strong influence”


<!-- references -->

Karau, Steven J., and Kipling D. Williams. "[Social loafing: A meta-analytic review and theoretical integration](https://www1.psych.purdue.edu/~willia55/392F-%2706/KarauWilliamsMetaAnalysisJPSP.pdf)." Journal of personality and social psychology 65.4 (1993): 681.

----
## Mitigation Strategies

<!-- discussion -->

----
## Mitigation Strategies

* Involve all team members, colocation
* Assign specific tasks with individual responsibility
    * Increase identifiability
    * Team contracts, measurement
* Provide choices in selecting tasks
* Promote involvement, challenge developers
* Reviews and feedback
* Team cohesion, team forming exercises
* Small teams

----
## Responsibilities & Buy-In

* Involve team members in decision making
* Assign responsibilities (ideally goals not tasks)
* Record decisions and commitments; make record available

----
## Motivation

Autonomy * Mastery * Purpose

![](drivebook.gif)


---
# Learning from DevOps

![DevOps](devops.png)
<!-- .element: class="stretch plain" -->

----
## DevOps: A culture of collaboration

* Overcome historic role and goal conflicts between developers and operators
* Joint planning for operations, joint responsibilities for testing and deployment
*
* Joint goals, joint vocabulary
* Joint tools (e.g., Docker, versioning, A/B testing, monitoring)
* Mutual benefits (faster releases, more telemetry, improved reliability, fewer conflicts)
* T-shaped professionals

----
## Changing practices and culture is hard

* Ingrained "us vs them" and blame culture
* Inertia is hard to overcome (“this is how we always did things”)
* Learning cost for new concepts and tools
* Extra effort for new practices (e.g., testing)
* Overwhelmed with current tasks, no time to learn/change
* Poor adoption may cause more costs than benefits

----
## Working on Culture Change

* Bottom-up and top-down change possible
* Often introduced by individual advocates, convincing others
* Always requires supportive management
* Education helps generate buy-in
* Consultants can help with adoption and learning
* 
* Demonstrate benefits in one small project, promote from there

----
## Beyond DevOps

* Organizational culture and DevOps have been well studied
* Learn from joint goal setting, joint vocabulary, win-win-collaborations, joint tooling
*
* *What could this look like for other groups (MLOps, MLDev, SecDevOps, LawML, DataExp, SafeML, UIDev, ...)?*

<!-- discussion -->

---

# Summary

* Team dysfunctions well studied
* Know the signs, know the interventions
* Small teams, crossfunctional teams
	* Deliberately create teams, respect congruence, define interfaces
	* Hire T-Shared developers
* Create awareness and accountability
* Further Readings:
    * Mantle and Lichty. Managing the Unmanageable. Addison-Wesley, 2013
    * DeMarco and Lister. Peopleware. 3rd Edition. Addison Wesley, 2013










