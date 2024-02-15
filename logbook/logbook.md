# Logbook

10/13/23
Today I worked on finding sources to outline the background information I would need to know in order to complete my project, specifically surrounding the ideas of how Covid-19 is passed and how we can use AI models to predict Covid-19 cases.

10/15/23
Today I took all of my sources and created an annotated bibliography which can be accessed here: https://docs.google.com/document/d/1_K_5YrJnE1rd8h-irvmBUi3SujoYheFPt_lQqFRzG5Y/edit?usp=sharing 

10/16/23
Today I met with my mentor and we identified my final project surrounding the idea of which method will give us the most accurate Covid-19 predictions. To do this I will be following a few tutorials in order to create a variety of code blocks to create predictions and see what the best way is using either wastewater or google trends data.

10/18/23
Today I had my facilitator meeting and I was able to get some feedback on my rough draft of my Research Proposal. It was really helpful to have some new eyes on my work and it gave me some direction (specifically that I should make sure to lay out everything so people can understand my project)

10/20/23
Today I worked on my Research proposal but I think I need some more information to clear up my methods and what I should write for them.

10/23/23
Today I met with my mentor, we clarified some things, and I have settled on my research question: how can we use machine learning to predict Covid-19 cases using Wastewater data and Google Trends data. We also attemted to work through a tutorial for cleaning some data and begining machine learning, but there were errors on my computer and since I am getting a new one on Wednseday we decided to wait util then to continue. Then I worked on my first reflection assignment for STAR.

11/1/23 - 12/18/23
During the end of the semester I completed the tutorial, learning more about how to use facebook prophet and what each specific piece of setting up the machine learning model did. Although it was a lot of work (and the logbook got updates less) I am now prepared to apply these ideas within my own project. From here I will clean both of my datasets and ensure they are good to run through my model, and then adjust my model to best predict cases. 

1/12/24
Today I met with my mentor, we went over some issues I was having with my datasets and putting them into a format that is usable with the model we are using. We figured out that there is a lot of issues with not having enougn overlap in our different datasets to endure our work is accurate because the wastewater data only goes back to june of 2023. We are reaching out to the people who created the dayaset to see if there is more data available to us, but if not we will be using out model to predict the wastewater data instead, by using the google trends as a comparison and prediction method. From here I am going to be working on finalizing the cleaning of the datasets and then merging them all together.

1/16/24 
Today I worked on cleaning my dataset and getting it to a point where I can merge them. I am still running into an issue interpolating the data, but I have been working on getting the google search terms into datasets that I can use. I have gotten about 5 out of 15 terms coded in. From here I just need to get the interpolating to work, add in the last 10 terms and then merge all the data.


1/17/24
I worked with a STAR Lab coordinater to look at my code today. I am still having an issue getting the data to interpolate, but he pointed out that the main issue I am having is because of my computer not running the same program, likley a lower level of python. I am working to find another way to execute my code to see if that changes anything, but we are still struggling to get the data to interpolate. He is working on it on his own time since I cannot use this computer to help right not, and if he is able to format the data correctly he is going to reach out again. Regardless, I have a meeting with my mentor on friday so I should hopefully get a chance to work through some of this with her.

1/19/24
Today I worked on my physical science notebook, and then I was able to solve the interpolation issue with my mentor. The issue seemed to be because the data had a non numerical answer, but we changed the data so that it is all numerical. With it working we moved onto merging the data, but we are now having an issue because the merged data is dropping rows, a lot of them. So now I am working on that. in the meantime I have to get all the google trends data and then find out which ones have the most correlation and the best flex in time. After that we will run the google trends through prophet for more information.

1/23/24
Today I managed to get all of my data imported, but the merging still does not work. From here I have to interpolate them all, and then find the correlation. Once I get that done and fix the merging I can work on the predictions!

1/30/24
The last week I have been focused on getting past the errors that I have been having. I finally got the merging to work with the help of my mentor. There was an issue with the way that my code was alligned, but after looking at the way theirs was organised I was able to get the code to a place where I could run it all. Now I have added in my 12 google search terms as regressors to my predions. I also am looking at my root mean squared error, or my RMSE to try and get it as low as possible, meaning that the predications aer as accurte as possible. Right now I have a 27 on a scale from 0 to 80, but I am attempting to get that lower. Once I decide the data is as accurate as possible I will move onto communicating data through graphs and discussion in my paper. 

2/15/24
Over the last few weeks I have been working on lowering the RMSE, and through a lot of parameter tuning, and using 'Face Mask' as the only regressor the RSME lowered to a 6. This means that the error is small enough that the model can still predict the directional trend of the virus (increasing or decreasing) but is not accurate enough to predict day to day. From here I will be working on communicating these results using a paper and slideshow.