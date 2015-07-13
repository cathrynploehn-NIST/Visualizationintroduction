[☜ Back to home](README.md)

Creating a visualization
=====

How does one actually go about creating a visualization tool? Because visualization is a component of the larger context of using data analysis to solve issues, it all begins with a __problem__: 

_I want to figure out the fastest and safest way to travel via car from my home to any bakery in Washington D.C._ 🚕🚙🚗

Where do I begin in solving the problem? Lam et al. (2012) and Munzner (2009) discuss the process of creating and evaluating visual analytic systems (software to analyze data that include visualization). It's helpful to note that data science tasks (cleaning, alignment, prediction, etc.) and statistics (principal component analysis, etc.) are a central part of the workflow, often integrated in software tools.

I draw from Lam et al. (2012) and Munzner (2009) to draft a process that builds upon the human-centered design lifecycle from the standard [ISO 9241-210:2010, Ergonomics of human-system interaction: Human-centred design for interactive systems](http://www.iso.org/iso/home/store/catalogue_tc/catalogue_detail.htm?csnumber=52075) (previously ISO 13407).

![Visualization design process](/images/visualizationdesignprocess.svg)

Each step builds upon the last. The earlier steps (planning, user research) heavily influence later steps (design, development). Errors made in one phase of the design process often cascade into the succeeding phases (Munzner 2009). Visualization evaluations can take place at any phase of visualization design cycle. 

#1. Analyze 

The first step is to gain an understanding of the __context of usage__. The first part of phase is understanding the domain in which the problems and users operate. Every domain has its own key words, common problems, and nuances. For visualization, understanding the user's work environment and work flow is critical. Which data will the users be working with, in what situations will they be using your tool to analyze data, and what problems are they trying to solve?  

This is the __research phase__ of the lifecycle. User research, competitor research, ethnographic methods, and other tasks are common and useful in this phase. Other methods for understanding users in a domain include:

- Field obervation
- Interviews
- Laboratory observation

Assumptions about the problem space, users, and domain need to be identified and minimized. 

Formal evaluations in this space have the overarching goal of understanding the practices of people in the domain (Lam et al. 2012). Evaluations in this phase are not as common as in the other phases. Plaisant (2004) argues for more researchers to study the context and work practices of visualization tools.
 

##The traffic domain

In the traffic domain, the main users are automobile drivers. Problems in this space include time and safety elements. Traffic (flow of vehicles) is affected by variables such as incidents, weather, time of day, and day of the week. For example, the time it takes to drive from Gaithersburg, MD to Hyattsville, MD is highly variable depending on time of day and day of the week. Safety (loosely defined as the average number of incidents in an area), changes with variables such as location, weather, and time of day.

![The traffic domain](/images/thetrafficdomain.svg)

Drivers in the traffic domain want to get from one geographic location to another, preferrably in the least amount of time and in a relatively safe manner. Task types include planning a drive (such as road trips, or finding new restaurants to try) and driving (to familiar and unfamiliar places). 	

Based on the problems and tasks required by the problem space, we could imagine the need to develop a __web application for planning the safest and fastest driving routes__. Embedded in this step is deriving system requirements from user problems. A draft for the specifications of the system is created, and iterated during the entire process. 

#2. Design 

The next phase in the lifecycle is design. Based on human cognition, a visual encoding and interaction design paradigm is developed (Lam et al. 2012). At least two subtasks exist in the design phase: 

__Operation and data type abstraction__

When working in visualization problems, a mapping of problems from the domain to the computer science domain. The output from this task is a description of generic (not domain-specific) operations, or tasks (Munzner 2009). 

For example, high level tasks could include: 

- _expose uncertainty_
- _concretize relationships_
- _formulate cause and effect_
- _determine domain parameters_
- _multivariate explanation_
- _confirm hypothesis_

__Visual coding and interaction design__

The visual encodings used for data and interactions are mapped out in this task. Mock ups, low fidelity prototypes, and other design materials are used.

Task flows, scenarios, and other user experience design tools are useful in this stage. 

In the traffic domain, a good design should bridge the abstract tasks of finding the safety level and time of any route into operational tasks such as predict number of incidents and predict the average time.

After tasks are designed, a strategy to present the data and interface to operate on the data is necessary. Static designs of the encoding strategy that could be used, such as the type and display of visualization(s), are designed. 

#3. Prototype

The prototype phase, developers implement the designs. In computer-supported visualization, this usually takes the form of code or software. 

__Algorithm design__

In this phase, an algorithm is designed to automate the visual encoding and interaction design of data. In other words, an automated way of handling and displaying different data sets. This algorithm is eventually implemented as software.

In designing the traffic web application, for example, a working prototype for the application would be developed to predict travel time and travel safety. During the development process, the designs for the system would be translated into algorithms and eventually actual code. Different pieces of code could handle the procesing and display of traffic data. Code could also be developed to handle the display and interaction of traffic data through visualization in the browser.   

#4. Evaluate

The visualization and data analysis software/code is validated. Evaluations could take the form of user studies, heuristic reviews, case studies, and a multitude of other forms mentioned in [Assessing Information Visualization](Assessing Information Visualization.md). However, it's important to note validation can occur at any stage of the lifecycle (Lam et al. 2012). Furthermore, there are different sets of methods appropriate for each phase of the design process.

In this stage, a prototype may revised and deployed based on evaluations.

For the traffic domain, potential users/subject matter experts, drivers planning a new route, could be brought in to test the prototype. This could take the form of controlled experiements with structured tasks, and/or qualitative feedback and interviews. For example, the drivers could perform a pre-planned scenario and attempt to plan a driving route on the system. On the other hand, this could take the form of studying the deployment of the web application and how it affects the workflow of the drivers who use it. 

Also, visualization/data science experts could be brought in to provide feedback on the prototype. Reviews can consist of structured (pre-planned question surveys) and unstructured (comments on the design of the system) components. For example, the adherence of a route planning interface to the interaction conventions implemented by GPS, Google Maps, and other driving applications on the market. 

#Iterate

Any phases above repeat until a sufficient product is created or until time and resources run out. The results from formal and informal evaluations are guidelines for improvement at any stage.  

[☜ Back to home](README.md)

#Sources

DIS, I. (2009). 9241-210: 2010. Ergonomics of human system interaction-Part 210: Human-centred design for interactive systems. International Standardization Organization (ISO). Switzerland.

Lam, H., Bertini, E., Isenberg, P., Plaisant, C., & Carpendale, S. (2012). Empirical studies in information visualization: Seven scenarios. Visualization and Computer Graphics, IEEE Transactions on, 18(9), 1520-1536.

Munzner, T. (2009). A nested model for visualization design and validation. Visualization and Computer Graphics, IEEE Transactions on, 15(6), 921-928.
Chicago	

Plaisant, C. (2004, May). The challenge of information visualization evaluation. In Proceedings of the working conference on Advanced visual interfaces (pp. 109-116). ACM.
