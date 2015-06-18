Information Visualization Measurement and Evaluation
=======

_Cathryn Ploehn_

This resource gives a summary of information visualization in the following parts: 

- An overview meant for researchers outside the visualization field, 
- approaches to measurement and evaluation (or lack and need of such), 
- and a proposed visualization task in the traffic domain

##Contents

[Guiding Principles of Information Visualization](Guiding Principles of Information Visualization.md)

[Assessing Information Visualization](Assessing Information Visualization.md)

[Types of visualizations](Types of visualizations.md)

[Tools of the Trade]()

[The Visualization Community]()

##What is visualization?

Visualization has become a loaded word. 

> "Graphics is the visual means of resolving logical problems" - Jacques Bertin

![According to the graph, human statements become more inane depending on cat proximity](/images/cat_proximity.png) _xkcd_

Chen et al. define visualization as:

> "__Visualization__ is a study of transformation from data to visual representations in order to facilitate effective and efficient cognitive processes in performing tasks involving data."

There are many types of visualizations, however, I'll focus on _computer supported data visualization_, which features data and computers. 

###Semiology of visualization

Semiology is the creation of meaningful communication. Visualization is a communication tool that leverages the powerful visual perceptive capabilities of the human mind. 

Below are descriptions of some semiological components of visualization. 

#### Knowledge vs information 

Bertin (1981) distinguishes between graphics used for communication and graphics leveraged in processing data. The process of solving a problem involves distinct types of graphics, or visualizations. __Knowledge visualizations__ communicate the answers discovered through __information visualizations__. Information visualizations are visual analytic tools for exploring and extracting patterns from abstract data. 

We use knowledge visualization to communicate ideas:

![t-rex is more closely related to sparrows than stegosaurus](/images/birds_and_dinosaurs.png) _xkcd_

And we use (sometimes cryptic) information visualization to discover patterns in data:

![PCA biplot](/images/Fig_PCA_biplot.jpg) _spatial-analyst.net_

In addition to focusing on _computer supported data visualization_, I will also focus on _information visualization_. (Although some concepts may also apply to knowledge visualization)

#### The Data

Data lies at the center of visualization. Data can be in a multitude of formats, for example: text, image, sound or video.

Data values can be separated into three categories (Card and Mackinlay 1997):

- __Nominal__: Only = or ≠ to other values
- __Ordered__: Follows a < relation
- __Quantitative__: Can be processed by arithmetic

The best type of visualization method for data will vary depending on these categories and other factors.

####Visualization vocabulary

Card and Mackinlay (1997) introduce an visual vocabulary to describe visualization. 

__Marks__: Point, line, area, surface, volume

__Controlled Processing of Graphical Features__: Process abstract encodings (text, etc.)

__Automatically Processing of Graphical Features__: Process visual properties (position, color, etc.)

- __Retinal encodings__: Color, size shape, gray-level, orientation, texture, connection, enclosure
- __Position__: X, Y, Z, T (3D space plus time)

The vocabulary builds upon previous work by Bertin (1983) and Mackinlay (1986).

Visualizations establish mappings between data and the visual vocabulary described above (Card and Mackinlay).

##Why information visualization is important

The display of data is a potentially powerful tool for data analysis. Visualization allows for the thorough exploration of the structure of data (Cleveland 1994). Many techniques of data analysis, which leverage data reduction - reduce the data to a handful of statistics. On the other hand, data visualization is a form of data analysis that can be leveraged to "convey the wealth of information that exists in data" (Cleveland 1994). 

The use of data visualization tools also allows for the encounter or surprises of the data, "yielding conclusions to questions not originally asked" (Cleveland 1994). 

> "The graph retains the information in the data" - W. Edwards Deming

# Sources

Bertin, J. (1981). Graphics and graphic information processing. Walter de Gruyter.

Bertin, J. (1983). Semiology of graphics: diagrams, networks, maps.

Card, S. K., & Mackinlay, J. (1997, October). The structure of the information visualization design space. In Information Visualization, 1997. Proceedings., IEEE Symposium on (pp. 92-99). IEEE.

Chen, M., Floridi, L., & Borgo, R. (2014). What is visualization really for?. In The Philosophy of Information Quality (pp. 75-93). Springer International Publishing.

Chen, C., & Yu, Y. (2000). Empirical studies of information visualization: a meta-analysis. International Journal of Human-Computer Studies, 53(5), 851-866.

Cleveland, W. S., & McGill, R. (1984). Graphical perception: Theory, experimentation, and application to the development of graphical methods. Journal of the American statistical association, 79(387), 531-554.

Mackinlay, J. (1986). Automating the design of graphical presentations of relational information. Acm Transactions On Graphics (Tog), 5(2), 110-141.


