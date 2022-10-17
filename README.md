# Final-Project

https://gentle-hollows-43858.herokuapp.com/

For this I have used machine learning to create a movie recommended. The user can search for  their favourite movie in the text box and then 10 movies are shown based on: Gerne, Directors, Actors similarities

Sklearn library is used to do collaborative filtering utilising TruncatedSVD function as the method to contruct the correlation matrix of each movie based on ratings

Instead of only showing the list of movie as text, the poster of the movies are shown. The the poster is not available, a black rectangle with white title will be displayed. The poster (image) is shown usind matplotlib library.

Pandas library is used to read the dataset and sample the dataset. Only a samll dataset is use as heroku RAM is limited
