## **The correlation between user rating score and content for the audience by age group.**



Most of you have viewed content on a variety of platforms in an assortment of ways. Some may consider an old fashioned show, others a new show or a trending show online. Some may choose to watch a film, or binge-watch one’s favorite show. This is what leads us to discuss one of the most popular platforms: Netflix. A platform that has shaped the new status quo and changed the way we view content. Either on the go, or the comfort of our living room, this platform in has made a subtle invitation into our lives.


My curiosity not only as a former filmmaker in motion pictures but also as a future data scientist lies in gaining a better understanding of the variety of content available for individuals to consume. Specifically, the ideology behind selecting and suggesting content for its viewers.

Concerning this dataset and due to the vast amount of time it would take to collect 1,000 shows one by one; the individual gathered method preyed on Netflix’s suggestion engine. The suggestion engine recommends shows like those selected in this dataset.  *"As part of this data set, I took 4 videos from 4 ratings (totaling 16 unique shows), then pulled 53 suggested shows per video. The ratings include G, PG, TV-14, TV-MA. I chose not to pull from every rating (e.g. TV-G, TV-Y, etc.). "*- Chase Willden


source: data.world [Netflix Suggestion Engine](https://data.world/chasewillden/netflix-shows)


As we dug into the data, we found that there are approximately a thousand shows within this data frame. Yet, when analyzed, we found more than half duplicated titles, leaving 495 titles to work within in the information gathered.


So Let's start…



> *First, I wanted to see if Netflix had a diverse library of content with the array of ratings. I found within the dataset that they have twelve categorical ratings, ranging from G to TV-MA.*
![alt text](https://miro.medium.com/max/1220/1*Y5gRPAP82yyE_xq__eUXQA.png)

The rating system from [Netflix](https://help.netflix.com/en/node/2064) indicates how the audience it's broken down by rating:
        
*   Little Kids G, TV-Y, TV-G
*   Older Kids PG, TV-Y7, TV-Y7-FV, TV-PG
*   Teens PG-13, TV-14
*   Mature R, NC-17, TV-MA

        
another source: [Film Ratings](https://www.filmratings.com/)

> Secondly, I wanted to see the correlation of the Audience Age’s impact to the individual user rating score and how that may affect the library as a whole.

I used feature engineering by adding an audience column to our dataset, which allowed me to associate the ratings from show ratings by individualities. In this case: Little Kids, Older Kids, Teens, and Mature.

![alt text](https://miro.medium.com/max/1078/1*DfkQ9SD0EfDyC2rT8Ptu6w.png)

![alt text](https://miro.medium.com/max/1098/1*XJP0abMe3OMml0KgXc_ooA.png)

Some may asks… how can a minor user score be even validated? I do not know. There is not enough data to support that thesis. But, since this dataset, Netflix has implemented the ability for the consumer to rate the content with a “thumbs up” or “thumbs down.” This could make a minor more able to rate content viewed. My theory as a parent is that the previous method was most likely rated by an adult.

Source: [Netflix](https://help.netflix.com/en/node/9898) on new Netflix Ratings & Recommendations


> *Lastly, I wanted to figure out Netflix’s popular shows by title. This would allow me to determine how and if they are relevant to its selection process regarding user rating scores.*


I utilized a word cloud to see which titles within the dataset are most popular. As one can acknowledge from this research, Netflix does a great job making sure it meets its demand by assuring the proper titles are in their library.

![alt text](https://miro.medium.com/max/1280/1*lpUygJ8TqlfH9S4SnKwZMA.png)

Working with this dataset with a past career in motion pictures was fascinating. To learn the skills I have within a few week’s time I was able to dissect, articulate, extract and feature engineer this data set. From working on this project, it makes sense how studios select which projects move forward and particularly how studios stick with these models to make it easier to predict and help the selection process. For a platform such as Netflix, the amount of content in their library allows audiences to view content a La carte, leaving their subscribers tuned in and pleased.

## You can applaud my story on Medium:
![Medium Link](https://medium.com/@ThisIsJorgeLima/the-correlation-between-user-rating-score-and-content-for-the-audience-by-age-group-4539a9f230a7)

### Here is a link to my code:
![Code Link](https://colab.research.google.com/drive/1jzKf7goCdi4RGpqWJfwaNYY8JI2gV2sH)
