---
title: And the award goes to...
subtitle:
image: img/Oscar-Promo.png
---

**Odds of winning one? - 1 in 11,500.**

I never sat down to watch the Oscars because of the glam, red carpet, and speeches. I'd tune in to watch the many artists I once viewed as mentors from afar, all seating under one roof. The very first film I remember watching when I was three years of age was a man running from a crop duster in the cornfields. A haunting image for a three-year-old one would imagine. That scene has always stuck with me to this day. Little did I know at the time that Alfred Hitchcock inspired me, one of the most influential and extensively studied filmmakers in the history of cinema. The film I speak of is *North by Northwest*, released in (**1959**) staring Cary Grant, Eva Marie Saint, James Mason. *Nominated for three Academy Awards* yet came empty-handed.

As a previous Documentarian filmmaker, I've always wanted to see what it takes to win a golden statue.


![alt text](https://cdn-images-1.medium.com/max/1600/1*xomrE9FaNqPeVYEGd5JEyw.png)

*"You can't approach baseball from a statistical bean-counting point of view, it's won on the field with fundamental play, you have to steal you have to bunt, you have to sacrifice, you got to get men in scoring position, and you got to bring them in. You don't do that with a bunch of statistical gimmicks. Nobody reinvents this game."* ~ from the Motion Picture ***Moneyball*** nominated for ***six Oscars.***

There is a lot to be said about this quote, adapted from [Moneyball: The Art of Winning an Unfair Game.](https://www.amazon.com/dp/B000RH0C8G/ref=dp-kindle-redirect?_encoding=UTF8&btkr=1) Although, as Data Scientist, there is more than Machine Learning and AI that goes into predicting potential outcomes. It takes someone to write a great screenplay, someone with a vision, and a great crew in preproduction, principal photography, and post-production to push the film through the finish line. Something that AI will never have. A heart and a soul. A lot goes into making a motion picture I know from first-hand experience.

"In feature films the director is God; in documentary films, God is the director." ~ *Alfred Hitchock*

Now that I'm studying Data Science, I decided to scratch the itch out of curiosity.

Without further ado, let's get down to the brass tax, shall we!

For this project, I gathered data from Oscar categories in prior years. This specific data was from 1980–2016.

![alt text](https://miro.medium.com/max/1400/1*teEqqt849De_CupQqvK0-A.png)

The data that I pulled was from other award ceremonies like the BAFTAs, Guilds, critics' scores, and historical data.

*"A total of 3,096 [Oscar](https://www.wikiwand.com/en/Academy_Awards) statuettes have been awarded from the inception of the award through the 91st ceremony."*

Winners are chosen from 24 categories. I selected eight out of the 24 for my model, as shown below:

![alt text](https://miro.medium.com/max/2000/1*7jbIZIMef8GyZV_Ew8sHLw.png)




A lot of my peers from the film business would cringe that I left such exciting technical awards. Yet, with a limited time frame to work on this project, I decided to select the major ones.

First, I wanted to break down the correlations between awards, by quarterly release dates, Ratings, and Running time before running them through models and to familiarize the data first hand.

The top three awards before capturing the Oscar we analyzed were BAFTA, Golden Globes, and the Guild.

![alt text](https://miro.medium.com/max/1366/1*aljP-agHt7wTeOAVefRcUA.png)

When viewing this chart, one can lean strongly that the Golden Globes may be a strong suit when predicting the Oscars. Yet let's see how strongly this holds up as we continue our analysis.

The next interest was the quarterly release dates and why this may play a factor.
![alt text](https://miro.medium.com/max/1366/1*SjoE6hs8dcMvoxd-QR7ydQ.png)

In this count plot, one can see the benefits of releasing a motion picture in Q4 and Q1, which makes a lot of sense. It's close to award season, and this helps during the campaigning process while it's still fresh in regards to the Academy.

Most of the films that go on to win are "R" rated films.

![alt text](https://miro.medium.com/max/1366/1*JrIXVKcBkixm5g6HvkDjvw.png)

Running time for an unbeaten run to snag an award is a 123-minute motion picture.

![alt text](https://miro.medium.com/max/2000/1*sIphMmTr_E4mVPAIY7CUww.png)



So for those planning to produce a film in regards to winning an Oscar with current information thus far.

Make a Drama film, keep it at 123 minutes long and release it in the first or fourth quarter; you may have a shot, one in 11,500 chance to be exact.

Here I did some future engineering and added a wins column and extracted the data in films nominated in each of the categories and grouped them by nominations and wins.


![alt text](https://miro.medium.com/max/1400/1*9zw3UW8c0wFVRyAa_n7Qpw.png)

As one would know, there are a lot of the variables used in these predictions dispursing a variety of output the data that was collected from award shows leading up to the Oscars. After thoroughly analyzing the data and running on the remaining features:

![alt text](https://miro.medium.com/max/1400/1*f5fJzXBaUH9DrYzEW6ad0A.png)
![alt text](https://miro.medium.com/max/1218/1*RttW--Srsc4qCfxlZfb_IA.png)

From reading literature while working on this project in regards to prediction. Candidate to go on to win Best Picture. The film has landed three crucial guild nominations that indicate support from multiple quadrants across the Academy: SAG's Cast in a Motion Picture, PGA, and DGA.

With the little time that I have, and I'll continue to scratch this itch and wrangle more data. The model also predicts a 55% probability.

Top 3 reasons for prediction also includes:
1. Rotten Tomatoes Audience Score is at 96.0
2. Box Office success is 389900000.0.
3. Star Count was at 6.0
![alt text](https://miro.medium.com/max/2000/1*lBf2Zh7BUYed9O9KNvBong.png)



The fans need some input by showing up at the box office. It's not just the Academy that has the final say. in this partial dependence plot PDP, and you can view box office performance in this graph:

![alt text](https://miro.medium.com/max/1400/1*96TnJU4psI3gmxCZdSxaYQ.png)

In closing, I had a blast working on this project, and I wish I had more time to dig deeper. I will continue exploring and being a filmmaker at heart. Although the Oscars haven't yet happened. Here are my predictions from what I learned during this data analysis.


---

**Best Director:** Sam Mendes **"1917"**

**Adapted Screenplay:** Steven Zaillian **"The Irishman"**

**Original Screenplay:** Noah Baumbach**"Marriage Story"**

**Best Actor:** Joaquin Phoenix **"Joker"**

**Supporting Actor:** Brad Pitt **"Once Upon a Time in… Hollywood"**

**Lead Actress:** Renee Zellweger **"Judy"**

**Supporting Actress: Laura Dern **"Marriage Story"**

**Best Picture:** 1917

Tune in on February 9, 2020, 6:30 PM EST

### want to get in touch?

*  [Linkedin](https://www.linkedin.com/in/jorgelima/)
*  [Twitter](https://www.twitter.com/thisisjorgelima/)
*  [Podcast](https://mailchi.mp/db9640dec7a5/a-month-of-saturdays)
*  [Instagram](https://www.instagram.com/thisisjorgelima/)
*  [Facebook](https://www.facebook.com/thisisjorgelima/)
*  [Website](https://www.thisisjorgelima.com/)
*  [Github](https://www.github.com/thisisjorgelima/)

### You can applaud my story on Medium here:
[Medium](https://medium.com/@ThisIsJorgeLima/and-the-award-goes-to-f1896ba2efbe)

### Here is a link to my code:
[Code](https://github.com/ThisIsJorgeLima/Unit-2-Project)
