
### Project Problem and Hypothesis

- I would like to explore the world of wine tasting and wine ratings.  Of
- Where does this seem to reside as a machine learning problem? Are you predicting some continuous number, or predicting a binary value?
- What kind of impact do you think it could have?
- What do you think will have the most impact in predicting the value you are interested in solving for?

### Datasets

- The data set is comes from the popular online wine cellar cellartracker.com.  In that website, users "store" their wines and they write descriptions and tasting notes.  Also, they give the wines a rating on a scale from 1 to 100 (most wines get rated beween 80 and 100). The website was the first site of its kind, so it has the most users of its kind.

- The sample comes from a website of a Data Science class. It is a text file.

- Here is a sample entry:
wine/name::: 2001 Chateau d'Yquem
wine/wineId::: 120962
wine/variant::: Semillon-Sauvignon Blanc Blend
wine/year::: 2001
review/points::: 98
review/time::: 1289433600
review/userId::: 131028
review/userName::: Rafal
review/text::: What an experience to taste this perfect balance. The aftertaste stayed in my mind hours later and it seemed way too complex to describe in words. The nose was that of usual suspects: orange, honey, rose, and peach, but all rather gentle and subdued, not heavy at all, yet highly perfumed. And whether you like me to say this or not, I was blown away by the scent of a linden tree in full blossom that somehow conjured memories of happy sunny days in the months of May... The palate was delicate, graceful, and completely in accordance with the nose. I could not discern any flavours in my mouth that I did not smell. My only regret was having to drink it so young, but what an experience it was... I am giving it 98 because I just have to keep 2 points aside for those statistically possible exaltations later in my life. Otherwise, it would be a 100 so-far.

- The data is 2.2 million entries. It is a very large set, and requires long compute times (and high computing capacity). Therefore, I will concentrate on 20,000 rows.


### Domain knowledge

- My experience in this area comes from a personal interest in wine that I have had for a long time.

- The research in this area because the information is usually available only on subscription members.  Therefore cellartracker has now stopped providing these types of data.  However, this set is from a couple years ago and can still be very useful

- The type of verbal reviews and tasting notes can potentially give us information on which wines are going to be rated higher than others.


### Project Concerns

- I am a bit apprehensive about how to use the data - should I use NLP or another method?
- I am not sure if the descriptions/tastings can be correlated to the ratings
    - I wish I had the prices of the wines so I could use them as well
    - Since I am using a part of the whole dataset, I may miss some of the nuances that are revealed with "big" datasets

### Outcomes

- I am hoping to be able to show which words are corellated with the better rated wines
- Also, I am hoping to see which types of wines tend to rate better than others
