[< Back to home](README.md)

Designing a new evaluation framework
====

#Important questions

Where does visualization fit in a data science evaluation? __Data science__ involves techniques for _analyzing_ and _extracting knowledge_ from data.

The purpose of information visualization is to function as a _problem solving tool_. In order to understand a tool, visualizations and the processes the visualizations support should be evaluated (Lam et al. 2012). Data visualization relies on __context__. Many work in the visualization evaluation space use methods to measure the utility of a visualization in terms of how effectively users can accomplish their context-specific tasks.

For example, the same data can be represented many different ways. The effectiveness of a visualization is tied into _which_ representation strategy is chosen to fit the task. 

Can we tease measurement of the visualization from the context of use? Certainly specific technologies can be measured (such as visualization for the browser, or for mobile devices).

Some questions that need to be answered:

__Abstract__
- Should a prospective visualization task emulate real world application/use case?
- What are the problems the datasets should be solving for a visualization task?
- Should we model off of recent visualization evaluation work. 

__Logistical__
- Should an entire software package be tested, despite possibly involving tasks not directly involved with visualization?
- Should clean or dirty data should be used for visualization?

But perhaps the most important question to answer, as asserted by Lam et al. (2012) is _what is the __goal__ of the evaluation_? 

The goal of our evaluation will drive the goal of our visualization evaluation, and determine which methods to use in order to measure the success of the visualizations submitted to the evaluation. 

There has been a recent call to focus research efforts on the _context_ of visualizations. Perer and Shneiderman (2009), Shneiderman and Plaisant (2006), Isenberg (2013)

[< Back to home](README.md)

# Sources

Lam, H., Bertini, E., Isenberg, P., Plaisant, C., & Carpendale, S. (2012). Empirical studies in information visualization: Seven scenarios. Visualization and Computer Graphics, IEEE Transactions on, 18(9), 1520-1536.