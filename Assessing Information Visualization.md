Assessing Information Visualization
=======

Write about where visualization fits in a data science task

Visualization is about facilitating problem solving.

- Provides answers to questions the data is meant to solve.
- Introduces more questions
- describes the qualities of the data

#Previous approaches

Much of the literature surrounding visualization evaluation is mainly applied to studying the effectiveness of new visuation methods. Many of these methods can be applied to an evaluation of visualization tools that may leverage new or common ways of visualization.

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

#Current approaches
##Visual Analytics Science and Technology (VAST) Challenge

Possible approach
- Need to define the problems the datasets should be solving
	- Clean data should be used
	- emulate real world application
- Can borrow from the evaluation of new visualization techniques (Forsell and Cooper 2014)

- Usability study that uses both theory and experimentation to validate.

- Heuristic review
- measured response experiments
- interviews

#Sources

Cleveland, W. S., & McGill, R. (1984). Graphical perception: Theory, experimentation, and application to the development of graphical methods. Journal of the American statistical association, 79(387), 531-554.

Forsell, C., & Cooper, M. (2014). An introduction and guide to evaluation of visualization techniques through user studies. In Handbook of Human Centric Visualization (pp. 285-313). Springer New York.

Mackinlay, J. (1986). Automating the design of graphical presentations of relational information. Acm Transactions On Graphics (Tog), 5(2), 110-141.

Plaisant, C. (2004, May). The challenge of information visualization evaluation. In Proceedings of the working conference on Advanced visual interfaces (pp. 109-116). ACM.