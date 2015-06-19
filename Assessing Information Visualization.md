Assessing Information Visualization
=======

How can we best measure and evaluate information visualizations? A few additional questions come to mind:

What makes a visualization __good__?
How can we reliably measure the __goodness__ of a visualization with a framework that captures:
1. the context of the problem solving space
2. the principles of good design
3. the benefit of the visualization to the end user

The main issue is how to apply the established evaluation conventions from the disciplines that intersect visualization in a way that captures the specific nuance of the information visualization space. For example, Human-computer interaction principles are important in answering the question of how to evaluate visualization tools. In fact, information visualization tools can be a subset of the computer software products and interfaces that usability researchers could evaluate. 

Information visualization is all about facilitating problem solving. That being said, all evaluation should center around the ability of a given visualization tool to help people solve problems. 

- Provides answers to questions the data is meant to solve.
- Introduces more questions
- describes the qualities of the data

#Previous approaches

First, I'll describe previous approaches to establishing visualization evaluations. 

Much of the literature surrounding visualization evaluation is mainly applied to studying the effectiveness of new visuation methods. Many of these methods can be applied to an evaluation of visualization tools that may leverage new or common ways of visualization. I mainly focus on the literature that applies to a general evaluation of visualizations, both novel and established. 

##Model of Graphical Perception

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

##Expressiveness and Effectiveness

Mackinlay (1986) used two terms for the evaluation of evaluating graphical designs:

__Effectiveness__ criteria "determine whether a graphical language exploits the capabilities of the output medium and the human visual system" (Mackinlay 1986).

The criteria for effectiveness may be based on a variety of factors. For example, accurate interpretation may be the main criterion for a visualization.

__Expressiveness criteria__ "determine whether a graphical language can express the desired information" (Mackinlay 1986).

Facts can be expressed if the graphic encodes only and all the facts in the set.

##Efficiency and Effectiveness

Chen et al. (2014) introduce the measures of efficiency and effectiveness for evaluating visualizations:

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

##Lossiness and Fidelity





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
The VAST Challenge sidesteps taking the costly step of testing prototype systems and the recruitment and onboarding of analysts. Instead, the challenge asks developers to analyze challenge data using their prototype systems.

With this approach, the usability of systems is not thoroughly isolated. Developers are entrenched in the inner workings and nuances of the system. It is hard to determine the usability of a system without the appropriate end users. 

##Meta-analysis of current approaches

Chen et al. (2000) conducted a meta-analysis of empirical information visualiation studies

###Users, tasks, tools

Chen et al. (2000) describe three aspects of information visualization: 

__Users__: The role of differences between people in the context of a problem space supported by visual analytics
__Tasks__: Design of studies concerning visual analytics
__Tools__: Variety of design options for visualizations in a study

###Accuracy and efficiency 

Chen et al. (2000) utilize _accuracy_ and _efficiency_ measures as dependent variables in their meta-analysis. 

__Accuracy__ measures include:
- precision
- error rate
- average number of incorrect answers 
- average number of correct documents retrieved 

__Efficiency__ measures include:
- average time of completion
- performance time

###Recommendations for experimental design

Chen et al. (2000) give the following aspects to consider for improving the clarity, quality, and comparability of information visualizations:
- Use standardized testing information
- Clearly describe visual-spatial properties of information visualizations
- Use standardized task taxonomies for activities such as: 
	- visual information retrieval
	- data exploration
	- data analysis
- Focus on task-feature binding
- Use standardized cognitive ability tests
- Use detailed reporting of statistical results

Additionally, studies were unable to be utilized in the meta-analysis due to
- Lack of comparisons between 
	- visualizations and control conditions
	- cognitive factors
- Insufficient data
- Did not include information-retrieval tasks

Chen et al. (2000) also mention the Text REtrieval Conference (cosponsored by the National Institute of Standards and Technology and the U.S. Department of Defense.

Desinging realistic and practical tasks is a challenging issue in the design of informatoin visualization evaluation. A need for the development of task-feature taxonomies is also needed. This development is contingent on the an understanding of how users utilize visualozation capabilities. 


#Sources

Cleveland, W. S., & McGill, R. (1984). Graphical perception: Theory, experimentation, and application to the development of graphical methods. Journal of the American statistical association, 79(387), 531-554.

Forsell, C., & Cooper, M. (2014). An introduction and guide to evaluation of visualization techniques through user studies. In Handbook of Human Centric Visualization (pp. 285-313). Springer New York.

Mackinlay, J. (1986). Automating the design of graphical presentations of relational information. Acm Transactions On Graphics (Tog), 5(2), 110-141.

Plaisant, C. (2004, May). The challenge of information visualization evaluation. In Proceedings of the working conference on Advanced visual interfaces (pp. 109-116). ACM.

Scholtz, J., Plaisant, C., Whiting, M., & Grinstein, G. (2013). Evaluation of visual analytics environments: The road to the Visual Analytics Science and Technology challenge evaluation methodology. Information Visualization, 1473871613490290.