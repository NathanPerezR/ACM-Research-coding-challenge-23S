# ACM coding challenge

---

## What is this?

this coding challenage is for ACM 2023 research.  The goal of the challenge was to "do something" with the data.

## Results

below are the results of the research, for more infomation open the ipynb file.

### setup

The set up for the notebook included the downloading of pandas, matplotlib, numpy, and seaborn.  Three tuples are made that make graphing the data easier.  The data set used is from a kaggle dataset.  

### correlation matrix

From the correlation matrix we can tell there exists positive correlation between radius and star type and a strong negitive corrolation between star type and absolute magnitude.

### star type

The most common star type of the data set is all of them, as they all occur 40 times.

### Temputure, Luminsoity, Radius (R/Ro)

These three data items are graphed in the main notebook.  It shows that the Temputure, Luminsoity,and Radius (R/Ro) skew towrds the lower end of their respective set.

### Pi chart of Spectral Class

From the graphing of the pi chart we can tell that class M is the most common on the data set.

### HR diagrams

#### Graphs by Spectral Class, Star Type, and Star Color Based on existing data set

From these diagrams we can see that the Spectral Class of the star is closly related to the log of the temputure of the star. This makies sense as the Morgan--Keenan system works by using the temputure of the a star to classify them. We can also see clumping of different 'zones'.

These tests should be run to include some star colors like "yellow-white" and "Yellowish White" and "white-Yellow" can be combined. Simular combinations exist for other star colors. It is because of this they were excluded from the graph.

#### Proposed Color Changes

All colors will be changed in the upcoming code snippet based on the colors found [here](https://starparty.com/topics/astronomy/stars/the-morgan-keenan-system/). This is done to more clearly see the colors. of the stars.

The new colors are now the following.

O – greater than 30,000 Kelvin – colour description: blue
B – 10,000 to 30,000 Kelvin – colour description: blue white
A – 7,500 to 10,000 Kelvin – colour description: white
F – 6,000 to 7,500 Kelvin – colour description: yellow white
G – 5,200 to 6,000 Kelvin – colour description: yellow
K – 3,700 to 5,200 Kelvin – colour description: orange
M – 2,400 to 3,700 Kelvin – colour description: red

Doing the graph this away allows for a much cleaner expression of the stars colors, and the viewier can easily see that blue stars are the hottest stars, while red are coldest. The viewer can also see that stars of simular temps can have different lum's. Intrestingly a star is present that is outside of this data range, having a temp of 1939, and a listed type of M.

Although stars being outside of their expected class is intresting, There is not enough infomation given to be sure why this is occuring. The data shows that the errors are not distributed along the whole data set, but instead showing clumping in the areas that are mainly Main Sequence Stars, Super Giants, and white dwarfs.