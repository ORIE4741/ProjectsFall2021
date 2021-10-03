# news-engaement
Project With Matty(mjd358), Mina(mh859), and Jordan(jsa242)
[Repository](https://github.com/JordanAle/news-engaement)

Proposal Draft:

For almost a century [1], news outlets based their business model on generating revenue through running advertisements in their news products. Nowadays, the majority of people get their news through social media [2]. Consequently a significant portion of any news outlet’s advertising revenue hinges on traffic directed to their articles from social media sites. While the precise details of any particular site’s newsfeed algorithm are unknown, it is no secret that posts with higher engagement in the form of reactions, comments, and shares reach more users of these platforms. It is therefore crucial to be able to understand and predict how a particular piece of content will perform on a social media platform in terms of these metrics. Even beyond individual news outlets, platforms for news aggregation like Google News or Apple News have a vested interest in understanding how people interact with internet news, in order to identify pain points and tailor their platforms to be a more enjoyable internet news experience than the competition.  

The dataset ‘Internet news data with user engagement’ includes information about article headlines, publishing time, content, publishing source, article image urls and some Facebook engagement metrics such as reactions and comments. Using this data we hope to predict the popularity of news stories so news outlets can better tailor their content creation strategies.

We are currently analyzing the usefulness of our prediction method. If we create a classification prediction model, article creators may iteratively tweak their stories until they can be classified as “will be popular”. Alternatively, we might consider regression to rate the popularity of an article and have that be an indicator of predicted popularity. Our direction is flexible at this point and both approaches have merit. We currently favor the classification method because it provides a tool that’s non-numerical and may put less pressure on article creators to achieve a specific score––their articles will either be predicted to be successes or not and they can make the changes until they have achieved a successful classification if that is their goal. 

To assess our predictions we will divide our data into test and training sets. Our training set will prime our model and our test set will provide us with feedback about the effectiveness of the classification or regression. 


https://www.sceneonradio.org/s4-e11-more-truth/
https://www.forbes.com/sites/petersuciu/2019/10/11/more-americans-are-getting-their-news-from-social-media/?sh=1704a9f93e17
