# Project Name
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Through this model we will know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

Dataset : (https://github.com/shrutich91/BikeSharingAssignment/blob/master/day.csv)
Data dictionary : (https://github.com/shrutich91/BikeSharingAssignment/blob/master/datadictionary.txt)
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

The features that positively impact the count of rentals
- Year
- Temp
- month of March
- month of Oct
- month of Sept


The features that negatively impact the count of rentals
- Holiday
- Spring
- Light Snow or Rain
- Misty or Cloudy
- month of July



As the year increses, the demand is definitely set to increases


81% of the variation of total rentals in training dataset and 84% in test dataset can be explained by the selected features, hence the model accuracy is considered acceptable.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- pandas - 1.3.4
- numpy - 1.20.3
- seaborn - 0.11.2
- sklearn - 0.24.2
- statsmodel - 0.12.2


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
This project has been prepared from learning from Upgrad at https://www.learn.upgrad.com


## Contact
Created by [@shrutich91] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
