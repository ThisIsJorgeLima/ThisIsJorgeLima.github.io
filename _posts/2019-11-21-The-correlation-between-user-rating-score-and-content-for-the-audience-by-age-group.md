The correlation between user rating score and content for the audience by age group.

Most of you, if not all, have viewed content on a variety of platforms. Many like to view content in an assortment of ways. Some may consider an old fashion show, some a new show or a trending show online. Or some may watch a film, or binge-watch one's favorite show. What leads us to discuss one of the most popular platforms Netflix. This platform in which in part has changed the new status quo that has changed the way we view content. Either on the go or the comfort of our home. It has made a subtle invitation to our lives.

My curiosity not only as a former filmmaker in motion pictures but my future career as a data scientist. What was interesting for me was to see the variety of content available for individuals to view. Furthermore, the ideology of selecting the content for its audiences.

In regards to this dataset. All we know. Due to the vast amount of time, it would take to collect 1,000 shows one by one. The individual gathered method preyed on Netflix's suggestion engine. The suggestion engine recommends shows like the selected shows. "As part of this data set, I took 4 videos from 4 ratings (totaling 16 unique shows), then pulled 53 suggested shows per video. The ratings include G, PG, TV-14, TV-MA. I chose not to pull from every rating (e.g. TV-G, TV-Y, etc.). "- Chase Willden

source: data.world Netflix Suggestion Engine

As we dug into the data, we found that there are approximately a thousand shows within this data frame. Yet, when analyzed, we found more than half duplicated titles. Leaving us with 496 titles to work within in the information gathered.

So Let's start…

What I first wanted to see if Netflix had a diverse library of content with the array of ratings. And we found within the dataset that they have twelve categorical ratings. Ranging from G to TV-MA.

The rating system from Netflix indicates how the audience it's broken down by rating:
        - Little Kids G, TV-Y, TV-G
        - Older Kids PG, TV-Y7, TV-Y7-FV, TV-PG
        - Teens PG-13, TV-14
        - Mature R, NC-17, TV-MA
        
another source: Film Ratings

I wanted to see the correlation of the Audience Age impact to the individual user rating score. and how that may affect the library as a whole.

By doing this I did some feature engineering by adding an audience column to our dataset. Which allowed us to associate the ratings from show ratings by individualities. In this case: Little Kids, Older Kids, Teens, and Mature.

As some may ask oneself how can a minor user score be even validated? I do not know. There is not enough data to support that thesis. But, since this dataset. Netflix has implemented the ability for the consumer to rate the content with a "thumbs up" or "thumbs down." This could make a minor more able to rate content viewed. My suggestion as a parent is that the previous method was most likely rated by an adult.

Source: Netflix on new Netflix Ratings & Recommendations

I wanted to figure out Netflix's popular shows by title. This way we can see how if they are relevant to its selection process to regards of user rating scores.

For this, I utilized a word cloud to see which titles within the dataset are most popular. As one can acknowledge from this research. Netflix does a great job making sure it meets its demand by assuring the proper titles are in their library.

Working with this dataset with a past career in motion pictures was fascinating. To learn the skills I have within a few week's time. I was able to dissect, articulate, extract and feature engineer this data set. From this project. It makes sense how studios select which projects move forward. And can see how studios stick with those models to make it easier to predict and help the selection process. In this case, Netflix. With the amount of content in their library, the audience will view content a la carte. Having the subscriber tunned in and pleased.
