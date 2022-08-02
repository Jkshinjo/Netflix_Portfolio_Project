# Netflix Portfolio Project
## By Jediah Kai Shinjo Mattison



# Introduction 
Netflix is a streaming service that is used all over the world by millions of people. It started off as a simple DVD and game rental platform and now has evolved into the entertainment behemoth it is today. With a variety of shows and movies as well as Netflix original content it has completely revolutionized how we consume media entertainment. 



# Project Focus
The goal of this project was to see what kind of content Netflix has. This consists of how many movies and shows there are and what categories they fall into. The categories are TV and movie ratings and their respective genres. I also wanted to know how Netflix's content has increased over time. Lastly I wanted to see if Netflix has content from the top ten most famous hollywood directors based on IMDB's top ten list. 

# Getting Started 
I started by using the [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows). This dataset contains columns such as title, genre, rating, date added to netflix, date released, director, cast, country and a short description of the show. I first used the pgadmin tool to create a table in my local instance of SQL. I then created the columns and imported the csv file containing the data. 


# Challenges and Limitations
When I first started I wanted to get a count of all movies and TV Shows. When I first selected all rows I noticed that the listed_in colums (genres) and the country columns had multiple values in a row. This would make getting an accurate count difficult as I would get multiple counts for the same movie. I decided to work around this by only selecting five countries (The US, UK, Japan, South Korea and India). I chose these countries because I felt like it would be a good representation of a global audience with little overlap. 

The dataset's main limitation is the lack of any numerical data. I did not have any data on profits, reviews, stock information, subscriber count etc. This would mean that I could only count the different kinds of media and change the queries to get differnt perspectives on the Netflix data. In the future I would like to expand on this project by analyzing fincial KPI's and seeing how they relate to this project.

# Analysis and Conclusion
After running my analysis on the data I noticed various trends. First Netflix focuses more on movies than TV shows. While Netflix has many different series both long running and original, the platform definetly caters toward a more moving watching audience with 6,131 movies to 2,676 TV shows worldwide. Second Netflix regardless of country definitely caters to a more adult audience with more than 60% of media being in the mature and restriced rating. Another interesting find is that Netflix does invest in big name movies. With a good chunk of American movies being from top directors. According to the data Netflix has been increasingly adding more content year by year with the peak being in 2019. 

In conclusion, Netflix has honed in on their target demographic and are pushing for an increase in the quantity of their content to cater to that demographic. Whether that content is quality or not is beyond the scope of this data; however, judging by the current decline in Netflix's profits and a stagnating subscriber count could mean that the overall quality of their content isn't enough to grow their subscriber count. Also, considereing the competition from other streaming services that have copied Netflix's business model, plus redundencies in media across those platforms, I would presume that Netflix needs to make another hit original series or movie to get new subscribers. This is not beyond their abilities as they have made many popular movies and shows; although, the opposite is true as well. Only time will tell if Netflix will survive the streaming war. 

