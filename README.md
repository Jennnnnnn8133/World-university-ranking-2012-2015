# World-university-ranking-2012-2015
# World university ranking in 2012-2015 / Data 115 final project at WSU
# Yu-Tung Cheng (11678647), Scott Ciabattari (11670352), Luis Trejo (11686194), Brett Harris (11705075)
# DATA 115  Dr. Deford 3 May 2021
# Data Analytics Final Report
                
                
##                When setting out on our Final Project, our group knew we would need a solid dataset that had interesting facts and figures.  We began looking through Kaggle until we came across a World University Rankings dataset which followed the top universities from around the globe.  This dataset contained the universities’ overall rankings, what country they are in, how they ranked in quality of education, their rankings in publications and influence and much more.  For our project we wanted to focus on how publications and influence specifically affect the overall world rankings. Once we had found the data the next step was processing.  We ran into a couple problems because the initial .csv file had some missing values for some schools way down the list.  
       
       
##            For this we just got rid of those data points because we felt that because they were so far down that it would not have a massive impact.  After we had finished the cleaning process we moved to implementing the data into R.  The data had already been made available as a .csv which saved us some time.  When we started to create the visualizations we wanted to use, we ran into a couple problems there.  We had trouble with our linear regressions in which we were helped out by Dr. Deford.  After our visualizations were complete, we took a step back and realized a big problem: our big question was not going to be strong enough.  We had initially thought about going more in depth on the quality of education stacked up against publications and influence, but once the visualizations were complete we decided against that due to it being too messy. So we shifted our question to the one listed in the first paragraph and continued on.  After we had changed our question it was clear that the data was more of a fit with the new question.  
               
               
##               We specifically wanted to look at publications and influence for a couple reasons.  Initially we were confused on how these were ranked and we wanted to learn more.  Once we did more research into the specific topics we decided they would be good data points to work off of.  Our exploratory analysis process took a long time as we were looking through our visualizations and dataset.  We tried to create different visualizations to give us new perspectives on our data points but they all came back with similar results.  Our preliminary conclusions were that publications and influence had extremely similar impacts on world rankings.  When looking at our graphs it was tough to see the differences between the two and get a clear idea of which had the greater impact which is why our initial thoughts went towards what we had determined for the preliminary conclusion.
               
               
##               The methodology behind our conclusion was something that we went back and forth on for a while.  We had looked through all of the visualizations and even took into account quality of education rankings and that impact yet we still could not find a clear enough data point that had more impact.  As a group we came to the conclusion that we did after we had exhausted all other efforts.  We maybe could have cut down the data size to top 50 or so schools to see if that had a more clear impact without all of the schools on the back end which got wider and wider as shown in our visualizations. 
               
               
##               Our final conclusion was a tough one, but at the end of it all we still could not find if publications or influence had a greater impact on the world rankings. If you look at the visualization it can be determined that we made the right decision.  Our analysis, while thorough, just did not show that one had a clear leg up on the other. As we had mentioned before, the only other analysis that we could have looked into was cutting off the data set after top 50 or 100.  This would have given a better look at how publications and influence affect the top schools, but would not have shown us the complete picture which is why we decided against going that route. 



#Initial Dataset: https://www.kaggle.com/mylesoneill/world-university-rankings

#References: Bastedo, M.N. and N.A. Bowman (2010) “The U.S. News and World Report College Rankings: Modelling Institutional Effects on Organizational Reputation”, American Journal of Education, 116(2): 163–183.
