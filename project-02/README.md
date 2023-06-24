# Data Visualization 

> Paul Dubois 

### Mini-Project 2

An analysis of the 2017 Boston Marathon

The data consists of 22 features with 26,410 observations
1. Bib"           
2. Name"
3. Age"           
4. M/F"  
5. City
6. State
7. Country
8. 5K            
9. 10K
10. 15K  
11. 20K"
12. Half"
13. 25K" 
14. 30K"
15. 35K"
16. 40K"
17. Pace"
18. Proj Time"
19. Official Time" 
20. Overall"      
21. Gender"     
22. Division"     

I was mainly motivated to try to raise a competition between the top 25 runners' countries and within the USA. The visualizations completed compliment my motivation very well. 

##### The interactive plot
I originally wanted to have a lollipop graph which would show the name of the runner when hovering over. As I attempted and got nowhere, I now have a column plot with the names of the runners over the columns in the graph, and when hovering over it, we can see the exact number of seconds they completed the marathon in. I couldn't figure out how to keep the hours, minutes, and seconds format as the `dplyr` functions to `summarise` was converting it. 

i. In first place, we have a Geoffrey Kirui from Kenya, in second place is our proud USA citizen Galen Rupp, and in third was Japan's Suguru Osako. It's interesting to note that in the Top 15 runners, there are no repeating nationalities. Everyone is from a unique country, I enjoyed finding this out.

##### Spacial visualization 
A map of the United States, and here I wanted to know the number of participants from each state in the United States. We know there aren't only participants from the USA, however, I wanted to create a little competition to see how many local runners were competing with out-of-state runners. This was simple enough by taking the count of runners by state. 

i. Massachussets had 4,586 runners at the marathon, while the state with the second most participants was California, coming in at 2,049. There were a total of 20,757 runners from the United States. 16,171 came from outside of Massachussets, I'm not sure why but I expected way less!

##### Models
I wanted to see how age and gender affected overall results. We can see there is a positive relationship, the younger the runner is, the quicker they could be. Generally speaking, due to many other factors, runners of all ages can have very fast and very slow times as they are the ones who decide their pace. 

i. When specifically speaking of the fastest runners, we can see that relationship holds true. The younger someone is, typically they will run the marathon quicker. In the age range of 20 - 40, there is an interesting dilemma as the times to complete the marathon are quite similar. 


