#Guiding Principles of Information Visualization

##Principles of Quality Visualizations

In _The Elements of Graphing Data_ by William Cleveland, basic elements of graph construction are discussed that should enhance the ability of a graph to show the structure of the data.

Visualization involves the process of encoding and decoding visual information. Graphical perception is the decoding of the information in a graph (Cleveland 1994).

###Producing Effective Visualizations

####What type of visualization should I use?

Cleveland and McGill (1984) ranked and empirically validated the accuracy of quantitative perceptual tasks:

![Accuracy of Graphical Elements](/images/degreesofaccuracy.gif)

Image created by Laurent Cailleteau, HCIL at UMD

Mackinlay (1986) extended this ranking to include non-quantitative information:

![Accuracy of Graphical Elements ranked by data type](/images/Mackinlay_PerceptualTask.jpg)


####Chartjunk and Data Ink

TODO

####Clear vision

"Make data stand out. Avoid superfluity." These are the two strategies outlined by Cleveland (1994) as the overall guiding principles to graph construction.

__Make the data stand out.__ The data are the reason for the graph's existence and should not be obscured by other elements. Visually prominent graphical elements can help the data stand out (Cleveland 1994). No data should be obscured.

Showing too many data layers and elements can obscure the data. Layers of data can be spread across multiple panels to reduce obstruction.

__Avoid superfluity.__ In other words, avoid chartjunk. For example, the use of excess symbols and tick marks.

Other guidelines Cleveland offers:

- Data points that overlap should be distinguishable.
- Superposed datasets must be readily visually assembled.
- Visual clarity should be preserved under reduction and reproduction.
- Proofread for errors

Ask for every graph:

- "Are the data portrayed clearly?"
- "Are the elements of the graph clearly explained?"

####Banking to 45°

The aspect ratio of a display affects the perception of the change displayed by the graph. The steepness of individual line segments affect our judgment of the rate of change in the graph. The absolute values of line segments in a graph should be centered around 45° for the most accurate perception of change and patterns in the data by adjustment of the aspect ratio of a graph.

In the figure below the aspect ratio affects the perception of different aspects of the graph. The upper graph indicates a accelerating increase of values. The lower graph shows a gradual increase followed by a rapid decrease of values in each spike.

![Banking to 45](/images/bankingto45.gif)

Figure by Heer, J., & Agrawala, M. (2006)

####Scales

Scales should be chosen such that the range of the scales nearly matches the range of the data. Often times two different scales on the same axes can be used to clearly communicate data (such as a log units scale and an original scale).

Use the same scales to compare related data on different panels.

####Data density and packing data

Cleveland (1994) and Tufte (2001) assert that a large amount of quanitiative data can be packed into a small region without compromising meaning.

###Producing Effective Interactive Visualizations

Shneiderman's principles of direct manipulation (1983):

- __visually represent__ the possibilities for action
- __incremental, rapid,__ and __reversible__ actions
- __selection via pointing__ instead of typing
- __immediate__ and __continuous__ feedback of results

Ahlberg and Shneiderman (1994) introduced more principles for interactive visualizations:

- __dynamic query filters__: adjusting query parameters for data displayed through GUI interaction
- __starfield displays__: Two dimensional scatterplots that structure data and reduce clutter
- __tight coupling__: Effective constraints of and feedback from GUI components used in querying data to reduce user error
- support __browsing data__ by:
	- Rapid filtering
	- progressive refinement of search parameters
	- continuous reformulation of goals
	- visual scanning to identify results

####Tight coupling

Tight coupling is an important principle in interactive visualizations. =(^.^=) meow Tight coupling involves an accurate display of the state of the software (or system) and provides constraints on interactions to prevent erroneous interactions on the system.

Effective use of tight coupling includes (Ahlberg and Shneiderman 1994):

- clear and consistent affordances (guides) for users
- rapid, incremental, reversible actions
- constraints on permissible operations
- continuous display of the information space (or data set)
- progressive refinement of data display parameters
- users can view details on demand


#Sources

Ahlberg, C., & Shneiderman, B. (1994, April). Visual information seeking: tight coupling of dynamic query filters with starfield displays. In Proceedings of the SIGCHI conference on Human factors in computing systems (pp. 313-317). ACM.

Ahlberg, C., & Truvé, S. (1995, August). Tight coupling: guiding user actions in a direct manipulation retrieval system. In BCS HCI (pp. 305-321).

Card, S. K., & Mackinlay, J. (1997, October). The structure of the information visualization design space. In Information Visualization, 1997. Proceedings., IEEE Symposium on (pp. 92-99). IEEE.

Cleveland, W. S., & McGill, R. (1984). Graphical perception: Theory, experimentation, and application to the development of graphical methods. Journal of the American statistical association, 79(387), 531-554.

Heer, J., & Agrawala, M. (2006). Multi-scale banking to 45 degrees. Visualization and Computer Graphics, IEEE Transactions on, 12(5), 701-708.

Mackinlay, J. (1986). Automating the design of graphical presentations of relational information. Acm Transactions On Graphics (Tog), 5(2), 110-141.

Schneiderman, B. (1983). Direct Manipulation: A step beyond programming languages, IEEE Computer, 16(8), 57-69.

Shneiderman, B. (1992). Designing the user interface: strategies for effective human-computer interaction (Vol. 2). Reading, MA: Addison-Wesley.

Tufte, Edward R. 2001. The Visual Display of Quantitative Information. 2nd edition. Cheshire, Conn: Graphics Press