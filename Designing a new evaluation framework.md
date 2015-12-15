[< Back to home](README.md)

Designing a new evaluation framework
====

#Important questions

Where does visualization fit in a data science evaluation? __Data science__ involves techniques for _analyzing_ and _extracting knowledge_ from data.

The purpose of information visualization is to function as a _problem solving tool_. In order to understand a tool, visualizations and the processes the visualizations support should be evaluated (Lam et al. 2012). Data visualization relies on __context__. Many visualization evaluations use methods to measure the utility of a visualization in terms of how effectively users can accomplish their context-specific tasks.

For example, the same data can be represented many different ways. The effectiveness of a visualization is tied into _which_ representation strategy is chosen to fit the task a researcher is trying to accomplish. At the same time, researchers may need to look at the same data represented in different ways to find interesting patterns.

Some questions that need to be answered:

__Abstract__
- Should a prospective visualization task emulate real world application/use case?
- What are the problems the datasets should be solving for a visualization task?
- Should we model off of recent visualization evaluation work. 

__Logistical__
- Should an entire software package be tested, despite possibly involving tasks not directly involved with visualization?
- Should clean or dirty data should be used for visualization?

But perhaps the most important question to answer, as asserted by Lam et al. (2012) is _what is the goal of the evaluation_? 

The goal of our evaluation will drive the goal of our visualization evaluation, and determine which methods to use in order to measure the success of the visualizations submitted to the evaluation. 

#Recommendation for an evalaution framework 

In developing an data science evaluation framework that includes visualization, I propose a focus on the _data analysis processes that visualizations support_. The proposed goal of a visualization task within this framework is to measure a tool's ability to support visual analysis and reasoning about data. 

Focusing on measuring how a visualization supports the _data analysis process_ allows an emphasis on the practical application of visualization technology. Grounding an evaluation in realism is ideal for promoting technology transfer. Furthermore, focusing on the realistic role of visualization would promote the development of visualization methodology and technology to support real-life tasks and domains.

There has been a call in the visualization community to focus research efforts on the _context_ of visualizations: Perer and Shneiderman (2009), Shneiderman and Plaisant (2006), Isenberg (2013). Specifically, the use of __case studies__  is common place to promote the transfer of technology into practical applications (Lam et al. 2012). Case studies are often emplyed by the visualization community to measure how well visualizations fit into the data analysis process. 

The scale and scope of case studies used can vary. For example, most case studies consist of a domain expert interacting with a visualization to answer provided benchmark questions (Lam et al. 2012) such as:

- How does this visualization support 
  - information seeking
  - searching
  - filtering
  - reading
  - extracting information

- How does this visualization support the schematization of information or analysis of theories?

- How does this visualization support the generation of hypotheses?

- How does this visualization support decision making?

(derived from Lam et al. 2012)

Other methodologies that are used to evaluate process include __laboratory obersveration and interviews__ and __controlled experiments__. Metrics include both quantitative and qualitative metrics. For example, the measure of time in accomplishing visualization goals could play an important role in a laboratory experiment (Chen et al. 2014). 

## The proposed structure

### Domain analysis
1. Problem identification: Gain realistic information on the domain the evaluation is to be conducted in. Work with domain experts to identify problems in the domain. Identify domain expert goals. Research activities include:
    - Contextual inquiry / ethnographic research
    - User interviews
2. Translate domain expert problem into data science problem. Identify datasets and technology necessary to solve domain problems.
3. Construct evaluation plan according to domain analysis. Required tasks to be implemented created
4. Pass requirements and evaluation plan instructions to evaluation participants (developers).

### Design and development

1. Developers design and implement a system 
2. Technical "back end" is sent to evaluation proctors for evaluation (data science eval as is)
3. Developers continue with design and development of "front end" (human-in-the-loop) components 
4. Developers deliver and set up system in domain expert workplace 

### Empirical evaluation

#### A. Case study
1. After developers install and train domain experts, 
2. Domain experts review tool usage at increments of useage
3. Use of any data science tools used for domain tasks (with and without use of new developer system) are logged
4. Importance of tasks rated by domain experts. Tasks will be used for performance and usability evaluation

#### B. Usability evaluation
1. Top tasks molded into controlled experiments
2. Domain experts (different from case study experts) perform task experiments on site for each developer system

### Heuristic evaluation

Visualization/data science experts review and score system effectiveness and efficiency 

1. Visualization algorithms rated
2. Visualization principles
3. Usability principles

### Results

Heuristic and empirical evaluation results condensed into formatted report containing both contextual reviews and performance reports of usability and expert reviews of design competency. 

##Alternatives

Instead of focusing on process, it also may be useful to switch focus to lower-level experiments entirely, such as evaluations that measure user performance of pieces of a visualization or evaluating user experience. However, controlled laboratory studies tend to become "distant from practical problems and broader goals" (Shneiderman and Plaisant 2006).

[< Back to home](README.md)

# Sources

Lam, H., Bertini, E., Isenberg, P., Plaisant, C., & Carpendale, S. (2012). Empirical studies in information visualization: Seven scenarios. Visualization and Computer Graphics, IEEE Transactions on, 18(9), 1520-1536.

Perer, A., & Shneiderman, B. (2009). Integrating statistics and visualization for exploratory power: From long-term case studies to design guidelines. IEEE Computer Graphics and Applications, (3), 39-51.
Chicago	

Shneiderman, B., & Plaisant, C. (2006, May). Strategies for evaluating information visualization tools: multi-dimensional in-depth long-term case studies. In Proceedings of the 2006 AVI workshop on BEyond time and errors: novel evaluation methods for information visualization (pp. 1-7). ACM.