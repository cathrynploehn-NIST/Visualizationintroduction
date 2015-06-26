Assessing Information Visualization
=======

>"One of our roles as information visualization researchers is to provide convincing evidence of utility...[which] presents special challenges for information visualization" 
\- Catherine Plaisant

How can we best measure and evaluate information visualizations? 

A few questions come to mind:
What makes a visualization __good__?
How can we reliably measure the __goodness__ of a visualization with a framework that captures:
1. the context of the problem solving space
2. the principles of good design
3. the benefit of the visualization to the end user

Information visualization is all about facilitating problem solving. That being said, all evaluation should center around the ability of a given visualization tool to help people solve problems. 

 A number of different approaches to evaluate and judge the validity of visualizations have been developed, as discussed by Bederson and Shneiderman (2003), Korsar (2003), Ware (2012), Lam et al. (2012), and Isenberg at al. (2013). Visualization paradigms are often assessed heuristically using best design practices as guidelines. For example, a visualization could be evaluated by number of data points and the level of granularity represented \cite{marty_applied_2009} and by types of relationships that can be represented \cite{meirelles_design_2013}. 

Empirical studies are also employed to measure visualization in terms of human performance.  Many methods used to evaluate visualizations follow conventions followed by the human-computer interaction field. The methods used to evaluate a visualization depend on the goals of the evaluation, such as a focus on the visualization itself or a focus on the analytic process the visualization supports \cite{lam2012empirical}. 

Isenberg et al. (2013) categorize evaluation approaches into slightly different categories: science evaluation, and design evaluation. . The visualization community borrows methods from these two disciplines in evaluating visualizations. The scientific approach focuses on building a representational model of the problem space that is reproducible, whereas the design approach focuses on the goal of aiding the user through maximizing usability and functionality (Isenberg 2013).  

Many researchers urge evaluation designers to focus on the __goals__ of the evaluation (Corbin and Strauss 2014, Ellis and Dix 2006, Lam et al. 2012). The goals of an evaluation should determine which methods are used to evaluate visualizations.  

Information visualization evaluations have increased in number and diversity since 1995 (Lam et al. 2012). Most visualizations trend towards three purposes (or scenarios) evaluation:

- Evaluating user performance
- Evaluating user experience
- Evaluating visualization algorithms

This makes sense - the visualization evaluation community has followed the customs of the human-computer interaction (HCI) discipline which heavily utilize controlled experiments, usability evaluations, and algorithm evaluations (Greenberg and Buxton 2008, Lam et al. 2012).

However, evaluating where visualization fits in the _process_ of data analysis may be beneficial in measuring the practical use of visualization. Lam et al. (2012) defines these purposes for evaluation, for example:

- Understanding environments and work practices
- Evaluating visual data analysis and reasoning
- Evaluating communication through visualization
- Evaluating collaborative data analysis

These types of evaluation tend to be lengthier, more costly, and have more qualitative measures. However, Lam et al. (2012) note that evaluation publications in the wider HCI community often include long-term evaluations and field approaches. More on these types of evaluations below.

There is also a resounding call for an establishment of a consistent, repeatable framework for choosing methods to conduct visualization evaluations (Chen et al. 2000, Munzner 2009, Lam et al. 2012, Scholtz et al. 2013). 

#Current approaches

##Visual Analytics Science and Technology (VAST) Challenge

The Visual Science and Technology (VAST) Challenge aims to advance the field of visual analytics through its annual challenge. The VAST Challenge is essentially a mechanism to evaluate end-user visual analytic software. The goal of the challenge is to allow developers to test their designs using the VAST Challenge evaluation framework. 

Scholtz et al. (2013) describe the necessity to construct an evaluation framework for the VAST Challenge since no guidelines for such an endeavor existed before. Guidelines should be developed based on the empirical studies or expert experience, such as they have been for fields like user experience design. 

The structure of the VAST Challened centers around its problem solving format. Participants are given data and tasks to accomplish using the data in a "real world" context. The results of their tasks are submitted online.  

Ground truth is embedded in the data, which allows accuacy to be measured. 

###Metrics used

Metrics were selected to indicate the final utility of the submitted visual analytics software. According to Scholtz et al. (2013), the correct metrics are That were able to be captured without direct access to the participant created software. 

Metrics used in the VAST Challenge are a comination of qualitative and quantitative measurements. Scholtz et al. (2013) define useful metrics as measurements that provide feedback effective enough for teams to revise their software. 

####Accuracy

Accuracy, according to Scholtz et al. (2013), is not a simple metric in the context of real world scenarios. Tasks and decision making in the context of scenarios are multidimensional and best represented by a narrative. Evaluating accuracy is the top challenge in recent VAST Challenge years. 

Nevertheless, the initial VAST Challenges utilized a quantitative accuracy component. This was accomplished by using forms with lists of questions to be responded with data values to enter. 

A debrief is also collected from participants, which is evaluated using guidelines standard to the intelligence profession. 

####Analytic Process

This metric was included to ensure an measurement of the evaluation process separate from the overall accuracy of conclusions. The decision to include the analytic process as a metric was to account for the possibility of teams arriving at faulty answers despite using a high quality process in their software systems.

####Visualizations and interactions

Reviewers provide feedback using rating scales on the effectiveness and intuitiveness of visualizations used in the visual analytic software submitted (perhaps a sort of quasi heuristic evaluation). Reviewers are also able to add comments for each rating. 

Scholtz et al. (2013) note that there are no agreed upon guidelines for the visualization design space, unlike the field of human-computer interaction. However, a meta-analysis of reviewer feedback unearthed emergent guidelines, even from other domains.  

###Strengths

The VAST Challenge uses a real world context and captures the entire problem solving task. The entire software product is tested, visualization and all. 

###Limitations

The time and funding constraints of the VAST Challenge limited the implementation of certain elements that provide rigor to evaluations. However, the VAST Challenge is intended to be an "economical, practical, and useful community based evaulation method" (Scholtz et al. 2013).  The challenge is intended to be a resource for teams to "do their own nested validation and evaluation process" (Scholtz et al. 2013).

####Usability standards untested
Scholtz et al. (2013) assert that "the normal definition of usability" could not be used in the VAST challenge due to limitations. For example, usability testing is inadequate to measure the problem solving tasks of analysts, which may take many hours. Another example given is the impracticality of conducting controlled expreiments measuring speed and error differences. However, there is benefit to the utilization of controlled environments with potential end users. 

####Teams analysed data with their own software
The VAST Challenge sidesteps taking the costly task of testing prototype systems and the recruitment and onboarding of analysts. Instead, the challenge asks developers to analyze challenge data using their prototype systems.

With this approach, the usability of systems is not thoroughly isolated. Developers are entrenched in the inner workings and nuances of the system. It is hard to determine the usability of a system without the appropriate end users. 

# Discussion of current approaches

##Meta-analysis of current approaches

Chen et al. (2000) conducted a meta-analysis of empirical information visualiation studies.Three aspects of information visualization are described: 

__Users__: The role of differences between people in the context of a problem space supported by visual analytics
__Tasks__: Design of studies concerning visual analytics
__Tools__: Variety of design options for visualizations in a study

##Themes in Evaluation 

Plaisant (2004) found four main themes of visualization evaluation:
- __Controlled experiments__ comparing design elements
- __Usability evaluation__ of a tool
- __Controlled experiments__ comparing two or more tools
- __Case studies__ of tools in realistic settings

###Empirical vs heuristic

We can also sort studies by their use of theoretical or practical evaluation techniques: 
__Empirical__: Usability testing and controlled experiments. Appear to be at the core of evaluation (Chin et al. 2002). 
__Heuristic__: Expert review according to established guidelines

####Empirical

Chen et al. (2000) utilize _accuracy_ and _efficiency_ measures as dependent variables in their meta-analysis. 

__Accuracy__ measures include:
- precision
- error rate
- average number of incorrect answers 
- average number of correct documents retrieved 

__Efficiency__ measures include:
- average time of completion
- performance time

Chen et al. (2014) use the measures of efficiency and effectiveness for evaluating visualizations:

__Effectiveness__ is the correctness of accomplishing a task.

__Efficiency__ is the time taken to accomplish a task. Three variables affect the time taken to accomplish a task:

- Data centric attributes: data set properties, such as size
- Human-centric attributes: amount/type of insight to be gained, type of judgement to be made, cognitive load required, etc.
- __Information delivery attributes__: Medium, display device, type of visual representation, etc. Critical to accomplishing a task efficiently

Chen et al. (2014) use "saving time" (rather than the common focus on the vague term "insight") in the forefront of their definition of visualization. They outline some implications of this new focus.

__Measurement__: Time is more readily quantifiable than other terms commonly used to define visualization
__Empirical studies__: Most empirical studies use the measure of accuracy and response time
__Design optimization__: Most important metric to guide optimization of design of visual systems
__Theory of visualization__: No fundamental theory of visualization has been reached by consensus. Still, time should be a fundamental component of any theory
__Practical wisdom__: Helps in the articulation of visualization in terms of a cost-benefit relationship

#####Model of Graphical Perception

In The Elements of Graphing Data (1984), Cleveland describes a model for graphical perception that would allow the measurement of the perceptual decoding process of visualizations. The decoding process must be studied in order to allow desingers to make informed decisions on how to create usable graphs. Data and experimentation should inform design choices to enhance visual perception. =(^.^=) meow. The model is used as a framework for studying the display methods, providing a rationale for display methods.

Pattern perception is the visual decoding of physical information (data-ink without the labels or tick marks). Pattern perception is differentiated from table lookup, or the "value in the units of the data." Pattern perception involves the perception of geometric objects to unearth patterns. In other words, pattern perception involves the ability to decode trends and relationships in the data through a visualization.

Three visual operations in pattern perception are:

- detection: visual perception of a geometric object
- assembly: grouping detected geometric objects visually
- estimation: visual assessment of quantitative values

Three visual operations in table look-up are:

- scanning: Browse or search data
- estimation: Estimate value or relative value
- matching: Connect two pieces of information

The accuracy of both pattern perception and table lookup can determined by the speed and accuracy of the operations above.

The model presents visual operations that are central to visual perception. These operations should be considered in evaluating a visualization. Cleveland states that the relative importance of each visual operation may vary by use case.

####Heuristic

Mackinlay (1986) used two terms for the evaluation of evaluating graphical designs:

__Effectiveness__ criteria "determine whether a graphical language exploits the capabilities of the output medium and the human visual system" (Mackinlay 1986).

The criteria for effectiveness may be based on a variety of factors. For example, accurate interpretation may be the main criterion for a visualization.

__Expressiveness criteria__ "determine whether a graphical language can express the desired information" (Mackinlay 1986).

Facts can be expressed if the graphic encodes only and all the facts in the set.

###Evaluation scenarios

As mentioned above, Lam et al. (2012) provides an overview of multiple evaluation scenarios. The overview was the result of a literature review of visualization study goals over 800 visualization publications. The results represent a descriptiEach evaluation scenario has associated goals. The goal of the evaluation should determine the methods used in the evaluation:

The scenarios are sorted into those for __understanding data analysis__:

- __Understanding environments and work practices__ - Glean design insight through gaining a better understanding of the "work, analysis, or information processing practices by a given group of people with or without software use" (Lam et al. 2012)
- __Evaluating visual data analysis and reasoning__ - Assesment of how a visualization tool "supports analysis and reasoning about data and helps to derive relevant knowledge in a given domain" (Lam et al. 2012)
- __Evaluating communication through visualization__ - Assessment of "communicative value of a visualization or visual representation in regards to goals such as teaching/learning, idea presentation, or casual use" (Lam et al. 2012)
- __Evaluating collaborative data analysis__ - Understanding the extent to which a visualization tool "supports collaborative data analysis by groups of people"

and for __understanding visualizations__: 

- __Evaluating user performance__ - Objectively measuing how specific features of a visualization affect the performance of people using a system
- __Evaluating user experience__ - Eliciting "subjective feedback and opinions on a visualization tool" (Lam et al. 2012)
- __Evaluating visualization algorithms__ - Capturing and mesuring "characteristics of a visualization algorithm" (Lam et al. 2012)

In this paradigm, evaluation is not restricted to just visualizations, but also on the processes of data analysis that visualizations support. 

###Science vs design

Isenberg et al. (2013) divide visualization evaluation methods into two overaching approaches: evaluation in the sciences and evaluation in design. 

####Evaluation in the sciences

Researchers using the scientific approach try to understand the world and develop a representative (often methematical) model (Fitts Law, etc.) to describe it (Isenberg et al. 2013). Model validation, reproducability, and turning mathematical models into computer algorithms are core concepts. 

In particular, verification and validation of models are essential tasks:

- __validation__: ensuring correctness of a model (conceptual or mathematical)
- __verification__: process of determining the acuracy of an implementation of a model

Validation is difficult and must be accomplished in an empircal nature. In the validation process, reproducibility of experiments is essential.

####Evaluation in design

Researchers using the design-based approach introduce tools that are intended to alter the state of the world (Isenberg et al. 2013). In this approach, the user, 'human-in-the-loop', usability, tool functionality, aesthetics are the main focus.

A primary concern of Human-computer Interaction evaluations of computer aided processes is __effectiveness__ (functionality), with a secondary concern of __efficiency__ and __aesthetics__.

##Recommendations for experimental design

Chen et al. (2000) give the following aspects to consider for improving the clarity, quality, and comparability of information visualizations:
- Use standardized testing information
- Clearly describe visual-spatial properties of information visualizations
- Use standardized task taxonomies for activities such as: visual information retrieval, data exploration, data analysis
- Focus on task-feature binding
- Use standardized cognitive ability tests
- Use detailed reporting of statistical results

Additionally, studies were unable to be utilized in the meta-analysis due to
- Lack of comparisons between 
	- visualizations and control conditions
	- cognitive factors
- Insufficient data
- Did not include information-retrieval tasks

Chen et al. (2000) also mention the Text REtrieval Conference (cosponsored by the National Institute of Standards and Technology and the U.S. Department of Defense).

Desinging realistic and practical tasks is a challenging issue in the design of informatoin visualization evaluation. A need for the development of task-feature taxonomies is also needed. This development is contingent on the an understanding of how users utilize visualozation capabilities. 

Munzner (2009) presents a model that splits visualization design into nested levels. Each level is assigned specific evaluation methodologies. 

- Domain problem characterization
- Data/operation abstraction design
- Encoding/interaction technique design
- Algorithm design

Validation of visualizations is measured with metrics falling into four categories:

- wrong problem
- wrong abstraction
- wrong coding/interaction
- wrong algorithm

Errors in one level of the model may cascade into the other nested levels. For example, data abstraction design errors may interfere with the correctness of the final algorithm design of the visualization. 

Lam et al. (2012) assert that the goal of an evaluation should drive the selection of methods used for evaluation design. Exploring and creating evaluations using a goal driven approach is given as a process involving:

1. __Choosing a focus__

2. __Picking suitable scenarios__

3. __Considering applicable approaches__

4. __Creating evaluation design and planned analyses__

##Challenges of evaluation

Plaisant (2004) points out the challenges in evaluating information visualization. =(^.^=) meow. The critiques are mainly intented on improving the measurement and communication of the utility of new tools developed by researchers. 

- __Matching tools with real problems__:
Utility of a tool needs to be demonstrated in a real setting.

- __Improving user testing__: Many empirical evaluations use simple tasks without capturing the full range of lengthy and complex tasks a user might need to perform. 
	- Tasks like ranking, clustering, or categorizing are often left out. 
	- Many evaluations do not report results per task, instead focusing on performance as a whole. Data and tasks are often selected via ad-hoc process. 
	- A development of task taxonomies would aid in the reuse of user studies.

- __Other unmeasured aspects of information visualization__: Plaisant (2004) identifies the characteristics and goals of information visualization that make evaluation particulary challenging, reviewed below.

	- __The same data from different perspectives__: Studies tend to observe users for a short period of time using a specific tool or visualization. However, the process of discovery using information visualization in practice involves longer stretches of time with many different tools, looking at a dataset from different points of views. Longitudinal studies and domain experts are beneficial for realistic measurement, but often difficult to integrate into studies. 

	- __Answering unasked questions__: One of the benefits of information is the enarthing and answering of new, unasked questions. However, evaluations tend to measure the performance of specified, pre canned questions. Plaisant (2004) suggests allowing the users to explore the data on their own as one possible remedy.

	- __Chances of discovery__: The chance of a payoff, in other words. A measure of estimating the chances of discovering a trend or phenomena in the data has not been implmented in many studies. Furthermore, the ripple effect of an increased awareness a visualization may bring (such as network administrators being more aware of network traffic) should also be measured. 

- __Universal usability__: Evaluations should take into consideration the level of usability for people with varied computer capabilities, cognitive ability, visual impairment, etc. 

Plaisant (2004) suggests two ways to improve the evaluation of visualization:
- create benchmark data sets and tasks, such as has been done at the [InfoVis2003 contest](http://www.cs.umd.edu/hcil/iv03contest/)
- aggregate case studies

Lam et al. (2012) defines an important first step in establishing a reference base of scenarios with examples. The continuation of the coding process of papers is encouraged, with the full list of papers coded [hosted here](http://bit.ly/7-vis-scenarios). 

Isenberg et al. (2013) identifies different challenges in the realm of visualization evaluation from a computational percpective. The primary challenges are "reproducibility, verificaton, and validation in visualization research." The _reproduceable research_ movement in the computation sciences is based on the notion that it is vital for validation purposes that experimetns be reproducible. Data and source code should be published together with a paper in order to increase trust (through independent validation) and accelerate scientific progress.

The [EuroVis workship on Reproducibility, Verification, and Validation in Visualization (EuroRV3)](http://www.eurorvvv.org/) has been created to address some of the evaluation issues in visualziation. The [BELIV Workshop](http://beliv.cs.univie.ac.at/about.php) a part of the IEEE VIS conference, focuses on discussion of "novel evaluation methods for visualizations."  


#Sources

Chen, M., Floridi, L., & Borgo, R. (2014). What is visualization really for?. In The Philosophy of Information Quality (pp. 75-93). Springer International Publishing.

Chen, C., & Yu, Y. (2000). Empirical studies of information visualization: a meta-analysis. International Journal of Human-Computer Studies, 53(5), 851-866.

Chin, D. N., & Crosby, M. E. (2002). Introduction to the special issue on empirical evaluation of user models and user modeling systems. User Modeling and User-Adapted Interaction, 12(2), 105-109.

Cleveland, W. S., & McGill, R. (1984). Graphical perception: Theory, experimentation, and application to the development of graphical methods. Journal of the American statistical association, 79(387), 531-554.

Corbin, J., & Strauss, A. (2014). Basics of qualitative research: Techniques and procedures for developing grounded theory. Sage publications.

Ellis, G., & Dix, A. (2006, May). An explorative analysis of user evaluation studies in information visualisation. In Proceedings of the 2006 AVI workshop on BEyond time and errors: novel evaluation methods for information visualization (pp. 1-7). ACM.

Forsell, C., & Cooper, M. (2014). An introduction and guide to evaluation of visualization techniques through user studies. In Handbook of Human Centric Visualization (pp. 285-313). Springer New York.

Greenberg, S., & Buxton, B. (2008, April). Usability evaluation considered harmful (some of the time). In Proceedings of the SIGCHI Conference on Human Factors in Computing Systems (pp. 111-120). ACM.

Isenberg, T., Isenberg, P., Chen, J., Sedlmair, M., & Moller, T. (2013). A systematic review on the practice of evaluating visualization. Visualization and Computer Graphics, IEEE Transactions on, 19(12), 2818-2827.
Chicago	

Lam, H., Bertini, E., Isenberg, P., Plaisant, C., & Carpendale, S. (2012). Empirical studies in information visualization: Seven scenarios. Visualization and Computer Graphics, IEEE Transactions on, 18(9), 1520-1536.

Mackinlay, J. (1986). Automating the design of graphical presentations of relational information. Acm Transactions On Graphics (Tog), 5(2), 110-141.

Munzner, T. (2009). A nested model for visualization design and validation. Visualization and Computer Graphics, IEEE Transactions on, 15(6), 921-928.
Chicago	

Plaisant, C. (2004, May). The challenge of information visualization evaluation. In Proceedings of the working conference on Advanced visual interfaces (pp. 109-116). ACM.

Scholtz, J., Plaisant, C., Whiting, M., & Grinstein, G. (2013). Evaluation of visual analytics environments: The road to the Visual Analytics Science and Technology challenge evaluation methodology. Information Visualization, 1473871613490290.