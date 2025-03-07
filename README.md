# Quantifying Social Resilience in Houston, Texas Post Hurricane Harvey

In this project, we aimed to quantify the ability of cities and their inhabitants to continue functioning after the passing of a natural disaster. Specifically, we wanted to investigate Hurricane Harvey’s impact on Houston’s 311 service requests. Our objective for this project was twofold: 
1. How did Hurricane Harvey impact the frequency of 311 service requests and 
2. How did Hurricane Harvey impact Houston’s ability to respond to 311 service requests?

To attain this, we created a counterfactual environment at least for the variables that we did the modeling on. Looking at the results of both the final AutoRegressive(AR) models, we saw that the city did take a hit and took about 2 months to get somewhat back to normal. But, an important thing to consider here is that the data doesn’t explain everything. For example, just because people have stopped reporting the issues, it doesn’t mean that all their problems have been solved. Despite that, an analysis like this can be useful to assess how a population and its government within a metropolitan area respond to traumatic events. Modeling the expected outcome can help the city officials in future planning for disasters by pointing out the places where they have been lacking.

More study could continue this line of inquiry and pinpoint what aspects of the city were most impacted by the hurricane by running similar analysis on specific service request types. Also, a spatial exploration of the same could be undertaken, and Houston, which is divided into 4 quadrants, would make a good playground for this.

This project has been done by Davey Ives, Imran Khan, Soham Mody ad Timur Mukhtarov. We worked on this as the project for the subject Applied Data Science while doing our masters at New York University.

The link for the raw dataset can be found in [311-Public-Data-Extract-Harvey.csv](https://github.com/SohamMody/Quantifying-Social-Resilience-in-Houston-Post-Harvey/blob/master/311-Public-Data-Extract-Harvey.csv).The metadata for the dataset is available in [metadata.csv](https://github.com/SohamMody/Quantifying-Social-Resilience-in-Houston-Post-Harvey/blob/master/metadata.csv).

The entire code done in Python using Jupyter can be found in [Final_Code.ipynb](https://github.com/SohamMody/Quantifying-Social-Resilience-in-Houston-Post-Harvey/blob/master/Final_Code.ipynb). This includes all the parts of the project from getting the data in to preprocessing it to the modelling and finally, the analysis based on the results of the models.
