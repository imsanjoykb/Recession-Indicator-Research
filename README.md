# Research
**Yield Curve as Recession Indicator in the framework of Machine Learning** 


Abstract

This paper studies the infromation content of the yield curve as recession
indicator in the Eurozone. This paper employs a dataset extending from 1970 to
2017 to create an aggregated syntheic yield curve for 3-month interest rates, 10-
year interest rates and rate of GDP growth. This paper is the first to utilise
Support Vector Machine for forecasting of recessions in the Eurozone.
The forecasting accuracy is tested in an out-of sample test. The model using
only German term-spread proved to be the most accurate. Nevertheless, this
model raised two false alarms between 2013 and 2016. Therefore, the findings
of this paper are inline with previous emperical investigation indicating
diminished information content of the yield curve.

The first folder (Extraction) contains the raw data and as the name indicates I extract and try to clean the data (NaNs). I admit the data interpolation was quite rough and dirty (probably a name of XXX-Movie) same as the creation of unified GDP growth Rate (WAV-Weighted average), yields (3-month and 10-years) and the term spread (10 minus 3). But, there is no but as I am quite contempt given the time and 1st attempt of doing such a thing. 

In the second (Develop) foler I create 6 models using (SVM with rbf) out of different term-spread combos contained in Full Data.xlsx

Lastly, the third folder (Deliver) well... I deliver, I deliver the visual representations of the model's performance saved under 4th (Graph) folder.

Straight out of an MOOC (udemy), however I have not done a lot of coding nor theory in the past 5 months as I was busy studying. The study  has no relationships to programming or modeling in any way My excuse for possible (head scratchers and overall confusion) given that someone ever reads this. 


I would more than welcome suggestions, reccomendations how to improve the code, the whole set up, model. But also direct comments when my description/organization seems to be unclear as well as mistakes within the application of the model and data cleaning. 
