# Crime and Demographics in the Mile High City
### Team Members: 
- Naureen Bharwani, Sean Mulligan, Cody Thornton

### Project Description:

- We sought to study correlations between violent crime and the demographic characteristics of Denver, CO. Our initial literature survey suggested that, in general, places with higher levels of violent crime have poorer health outcomes, higher levels of poverty, lower rates of higher educational attainment, and more racial diversity. Based on this research, we sought to discover if certain neighborhoods in Denver experienced higher levels of violent crime than others and, if so, whether or not these neighborhoods reflected these demographic characteristics.
- Identifying the connections between violent crimes and demographics is important because it can provide insight on the true costs of violent crime, and how to potentially prevent it in the first place.	Like any complex social phenomenon, violent crimes are not the result of a single cause. Violent crimes are the aggregate result of well studied social issues including, for example, poverty and education.
- By examining the violent crime centroids, at both a neighborhood and regional level, we hope to see how higher levels of 
poverty, or conversely lower levels of education, affect violent crime rates. Moreover, violent crimes have costs beyond the crimes themselves, including impacts to health. By studying the violent crime centroids, again at a neighborhood and regional level, we hope to see how violent crime may impact rates of obesity and the average life expectancy. Interwoven between these layers are additional societal constructs and forces that serve as both catalysts and inhibitors to themselves and all other variables, such as income, race, religion, etc. By identifying trends in the primary crime and demographic data, resources can be better targeted to communities in need.


### Project Summary of Questions Sought and Answers:

- We discovered that certain areas of Denver have disproportionately high concentrations of violent crime. We asked and answered the following questions about these neighborhoods and regions:
    - Do these areas have poorer health outcomes?
        - Yes - 2.8 years lower life expectancy and 7.1% higher obesity rates than state averages
    - Do these areas have higher rates of poverty?
        - Yes - 7% higher rates of poverty than the state average
    - Do these areas have lower levels of education?
        - Yes - 15.2% lower attainment of bachelors degrees
    - Do these areas have larger minority populations?  
        - Yes - 44.4% more diverse than the state average 
            
            
### Project Application:

- Our results can help law enforcement identify areas in Denver that require greater attention. The neighborhoods and regions containing the centroids produced by our k-Means algorithm are good candidates for greater policing to reduce violent crime in Denver. 

- Our results can also help social programs aimed at improving health outcomes, alleviating poverty, and raising levels of education by identifying the areas of Denver most in need of this aid.

- Our results also provide rich fodder for future research aimed at identifying causality. Among the chief questions our results might inspire are: 
    - Does the presence of violent crime in a community lead to higher levels of pessimism or nihilism and thus lower motivation for healthy living?
    - Does lack of employment opportunities yield higher rates of poverty and a higher likelihood to be involved in criminal activities that result in violence?
    - Does the presence of violent crime in a community lead to greater mental stress and thus lower bandwidth for education?
    - Are there opportunities that are denied to racially diverse communities that lead to greater desperation and rates of violence?


### Description of Source Code:

- attributeStandardization.ipynb - Standardization of values for Neighborhood attribute
- dataWarehouseCounts.ipynb - Counts of crimes for creation of data warehouse
- kMeans.ipynb - k-Means clustering
- naiveBayes.ipynb - Bayesian analysis


### Video Demonstration

https://drive.google.com/file/d/1GdAsgm7XOqJwH0zgWwIDRRbYM3duRbng/view?usp=sharing

### Project Final Report:
https://github.com/nbharwani11/CS4502_Final_Project/blob/e888e14d74765c3ac4e412222a3930d4ad518ced/Milestones/01_CrimeAndDemographicsInTheMileHighCity_Part4.pdf
