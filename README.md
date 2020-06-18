# Design and Analysis of Dynamic Games

## Overview

### Motivation

short overview of the goals of this seminar  
and knowledge application areas (including crypto/TokenEnginering), alternatively own section  

### Prerequisites

This course assumes working knowledge of multivariate calculus, linear algebra and optimization. More advanced mathematical topics will build on these areas. Additionally, a working knowledge of algorithm game theory is assumed. Approaches presented in the course are specific to state based games with many players, many mechanisms and a statespace which includes arbitrary data structures.

Depending on what field you come from, mathematical notation varies. My course material will leverage notation similar to that of Stephen Boyd at Stanford. I recommend his lecture notes on linear systems for getting acquainted with the notation.

[todo: add links to prequisites]

### Topics to be covered

The course has three major components: mathematical foundations, computational methods and applications. Mathematical foundations will focus on dynamic games as dynamical systems where the inputs are controlled by strategic agents with their own beliefs, preferences, etc. Computational methods will include a survey of techniques and associated best practices with a focus on design of and decision making in real world systems. The application component will make use of the learnings in the prior two components to explore some real world systems.

### Teachers and TAs
Name A, title, bio, link  
Name A, title, bio, link  
Name A, title, bio, link  

### Logistics

The seminar will start on (date) and will run over 12 weeks with weekly session from HH:MM to HH:MM in the US Pacific time zone.  
All information on logistics and application here: (link)  
__Application deadline:__ (date)  

There will be no grades but attendees will participate in teams which will be expected to push their assignments and projects to a public github repo.

## Syllabus

Sessions will be 2 hours. All sessions will include some lecture component. Some will include presentations from guest lecturers and most will include time for discussions.

### Part 1: Mathematical Foundations

[future link to folder in repo]

#### Week 1
Introduction to Dynamical Systems; attention will be paid to continuous time, discrete time and event based models. For simplicity only linear models will be considered initially. A sample system for which the event time, discrete time and continuous time representations are all relevant will be considered.

[future link to md page]

#### Week 2

Extension of the mathematical notation to nonlinear dynamical systems, attenion will be shifted to inputs controlled by two players and outputs representing players goals. Dynamic strategies, optimal control and the relationship between reinforcement learning and dynamic games will be introduced. 

[future link to md page]

#### Week 3

Introduce the concept of the configuration space. The dynamic games formalism is extended to include a generalized statespace which is an arbitrary data structure and variations with many players as well as multiple mechanisms for transforming the system state. Agent strategies will be framed path planning alogrithms.

[future link to md page]
 
#### Week 4

Introduce potential functions, their differential under admissible action sets and the notion of *better response* dynamics. Discuss how gradient descent relates to dynamic optimization and how this relates to games roles as sense-making tools through the lens of estimation theory.

[future link to md page]


### Part 2: Computational Methods

[future link to folder in repo]

#### Week 5

Scoping models for computation methods Attention will be paid to seperation of temporal and spatial scales. Discussions will include mapping actors, mechanisms, metrics (KPIs) and exogenous processes. The goal is to produce models which are useful to some decision making (design or intervention) and as simple as possible but no simpler.

[future link to md page]

#### Week 6

Review a range of methods with relative strengths and weakness as well as addressing the complementary roles of models and data. System Dynamics, Agent Based Modeling, networked models and multiscale models will be reviewed. Various modeling software will referenced by this course will primarily leverage tools in the scientific python ecosystem.

[future link to md page]

#### Week 7

Highlight the concept of observability, and apply it to introduce state estimation and system identification. Explore in more details the roles of data and models in forecasting including a variety of techniques for evaluating designs and interventions in modeled systems, including sensitivity of results to the model's assumptions.

[future link to md page]

#### Week 8

Applying computational methods for design and intervention. Computational models are tools for doing computational thought experiments; session will focus on building test grids, running many experiments, scoring metrics and the practice of translating experimental data into concrete decisions while still respecting and documenting uncertainty around the expected outcome. 

[future link to md page]

### Part 3: Applications

Lecture components in part 3 will be noticibly shorter focusing on examples from active projects; guest presentations and discussions will be prioritized as teams are focusing on their projects. Reference examples and guest speakers will be announced closer to the dates of these seminars.

[future link to folder in repo]

#### Week 9

Reference Example[tbd]  with Focus on the scoping phase. 

#### Week 10

Reference Example[tbd]  with Focus on the mathematical modeling phase. 

#### Week 11

Reference Example[tbd]  with Focus on the writing and running computational experiments phase. 

#### Week 12

Reference Example[tbd]  with Focus on analyzing data and making decisions phase. 

### Finale: Project Showcase

Live stream event for presenting projects.

## Assignments

Assignments should be submitted via pull request to this repo. All assignments (except 0) may be done as a team, each team will have a folder in the assigments directory where they can submit markdown, python code and jupyter notebooks.

[future link to folder in repo]

### Assignment 0

Read Section 1 (pages 3-72) *Foundations* of **Engineering a Safer World** by Nancy Leveson 

Further reading in this text is recommended but not required. The purpose of this assignment is to ensure we're thinking about the role models play in engineered systems, and how those models effects the sociotechnical systems composed of those engineered systems, humans and other exogenous factors.

Deliverable: 500 word essay describing an aspects of this reading reasonates with you, that you found suprising or identify a major point you disagree with; explain why. Alternatively, provide any thoughtful reflection on the material that you feel merits the attention of others.

### Assignment 1

Mathematical modeling problem set

[future link to md file]


### Assignment 2

Simulations problem set

[future link to md file]

### Assignement 3

Team project goals and scoping deliverable

[future link to md file]

### Assignment 4

Team project model and model preoperties deliverable

[future link to md file]

### Assignment 5

Team project final deliverable: simulation results and analysis, conclusions and next steps

[future link to md file]

## Further Reading

Summary and links for Relevent Papers, Textbooks, and Projects.

(* indicates more advanced material, ** indicates very advanced material)

### Weeks 1 and 2

<a id="aoki_1996">[Aoki (1996)]</a>
Aoki, Masanao.
_New Approaches to Macroeconomic Modeling_.
Cambridge UP, 1992.

<a id="day_1994">[Day (1994)]</a>
Day, Richard H.
_Complex Economic Dynamics_.
MIT Press, 1994.

<a id="gulick_1992">[Gulick (1992)]</a>
Gulick, D.
_Encounters with Chaos_.
McGraw-Hill, 1992.

**<a id="katok_hasselblatt_1995">[Katok and Hasselblatt (1995)]</a>
Katok, A. and B. Hasselblatt.
_Introduction to the Modern Theory of Dynamical Systems_.
Cambridge UP, 1995.

### Weeks 3 and 4

*<a id="bertsekas_2007">[Bertsekas (2007)]</a>
Bertsekas, Dimitri P.
_Dynamic Programming and Optimal Control, vols 1 & 2_.
Athena Scientific, 2005, 2007.

### Weeks 5 and 6

<a id="dreo_et_al_2006">[Dreo _et al_ (2006)]</a>
Dreo, J., A. Pétrowski, P. Siarry and E. Taillard.
_Metaheuristics for Hard Optimization_.
Springer, 2006.

<a id="levy_et_al_2000">[Levy _et al_ (2000)]</a>
Levy, M., H. Levy and S. Solomon.
_Microscopic Simulation of Financial Markets_.
Academic Press, 2000.
