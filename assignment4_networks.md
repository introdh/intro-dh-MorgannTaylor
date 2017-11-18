# Network Analysis Assignment 

## Part 1: Network
Build your network in R. Save images of your networks to include in your paper. 



## Part 2: Paper

The 500-1500 word paper should address the following:

- Describe the data you selected for your analysis. Assume the reader is unfamiliar with the data.
- Explain the questions/ arguments your network generate about your data.
- Drawing on the constraints, critiques and ideas in our readings, discuss the possibilitie and limits of network analysis as applied to your network and for network analysis generally. Make sure to cite the readers. 

## Data

You can build your own data set or use the Supreme Court data. 

### Supreme Court

Washington University in St. Louis assigned each United States Supreme Court case to a legal issue (ex. desegregation). Pick two or more issues and analyze.  The [code book](http://scdb.wustl.edu/documentation.php?s=1) lists the corresponding issue assigned [each issue number in the data set](https://github.com/introdh2016/response3_network/blob/master/ussc-31.zip).  In order to better understand this Supreme Court data, read [The authority of Supreme Court precedent](https://github.com/nolauren/dh2017/blob/master/authority_of_supreme_court_precedent.pdf) and [Network Analysis and the Law](https://github.com/nolauren/dh2017/blob/master/network_analysis_and_the_law.pdf).

### Baseball

The baseball data gives either links between MLB teams (that share players) or
links between MLB teams and college teams (again, that share players). The latter is bipartite.

[MLB - Edges](https://github.com/nolauren/dh2017/blob/master/mlb_teams_edges.csv)
[MLB - College Edges](https://github.com/nolauren/dh2017/blob/master/mlb_college_edges.csv)
[MLB - College Nodes](https://github.com/nolauren/dh2017/blob/master/mlb_college_nodes.csv)
[MLB - College Edges](https://github.com/nolauren/dh2017/blob/master/mlb_teams_nodes.csv)


How do we read these edge lists?

[MLB Team Edges](https://github.com/nolauren/dh2017/blob/master/mlb_teams_edges.csv): When looking at the second row, it says "MAN,BRA,1872,1". This is read as the Brooklyn Atlantics had 1 player in 1872 that once played for the Middletown Mansfields.  For this project, one would only be looking at if a team shared players. The number of shared players will not matter because the network will not be accounting for edge weights (i.e. 1 in this example). 

[MLB - College Edges](https://github.com/nolauren/dh2017/blob/master/mlb_teams_nodes.csv): When looking at the second row, it says "fordham,TRO,1871,1". This is read as the 1871 Troy Haymakers team had 1 player who also played at Fordham. Like the MLB teams, one is only looking at if a team shared players since we are not acocunt for edge weights in this assignment. 


You will want to create a subset to analyze. Consider picking a year (or few years) to explore. 
 



### Your Data

Want to use your own data? Go for it! 
See lab09_network2.md for instructions on how to build your data set.
Please create the data in google sheets and include the link in your paper. 





## More details:

- Citations: Use a modified format since citations will be drawn from course readings. Cite relevant readings using in-text/ parenthetical citations: (author, publication, date). Ex. (Blevins, personal blog, 09-09-2009) or (Goldstone and Underwood, JDH, 2012).

- Images: Include images of your networks. 

- Save as "Assignment4_YOURLASTNAME.md" in your repository.


- Grading: [Rubric](https://github.com/nolauren/dh2017/blob/master/assignment3_rubric.pdf)
