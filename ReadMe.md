## How to leverage YouTube content in the most efficient way
### Introduction

Content and data are considered as the most significant resources of power in modern digital world. Whosoever controls the data and content has an edge over other competitors in the market. You tube has emerged recently as the highest used video platform for developing the content and leveraging it for expanding one’s reach.

## Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

### Project Motivation

You tube indeed can be a very effective tool in creating one’s presence among maximum population without expanding much. Analysis of records suggest that PewDiePie-Series and Gaming are the top 3 YouTube channels subscribed most by the audience across the world.

So what is that makes you unique and popular on this widely used platform? Is it like a switch platform where you can just on and off your visibility? Or there are certain strategies and hacks to it that can be utilised to benefit from the systems of the platform. We will be looking at some of the certain ways in which this platform has been leveraged and put to use across the world for maximum productivity and conversions.

Following CRISP-DM approach:

1. Business Understanding
    There are three main questions I try to find the analysis on
    1. The most sought-after contents by the YouTube audience
    2. Curating content for segment-specific audience(educational, sports, music)
    3. Definitely, Monetising your content.

2. Data Understanding
    - [dataset_link](https://www.kaggle.com/libinmathew264/youtube-top-4000-channels-based-on-subscribers) is from kaggle dataset.
    - There are 22 features ('web-scraper-order', 'web-scraper-start-url', 'userID', 'userID-href',
       'name', 'uploads', **'subscribers'**, 'videoviews', 'country',
       **'channeltype'**, 'usercreated', 'grade', 'YouTube_Link',
       'YouTube_Link-href', 'TwitterHandle', 'TwitterHandle-href',
       'InstagramHandle', 'InstagramHandle-href', **'MonthlyEarningsMin'**,
       'MonthlyEarningsMax', 'YearlyEarningsMin', 'YearlyEarningsMax') 
    - The highlighted featuers has no null data so no missing data handling in our case as we take into consieration only these features.
3. Data Preparation
    - out of 22 features we have selected (**'subscribers'**, **'channeltype'**, **'MonthlyEarningsMin'**) the highlighted features for our analysis to answer rrelated questions.
    - For correlation between different chnneltype based on number of sunscriber in each country, we need to handle missing value for number of sunscriber in each country with 0(also meaningful)

### Results

The main findings of the code can be found at the [blog post](https://medium.com/@naveenchoudhary_11/how-to-leverage-youtube-in-the-most-efficient-way-410e12be449)


### Conclusion

Based on the consumers’ analytics and data I have been able to show here some of the prevalent trends related to the YouTube platform and how these trends can be leveraged to produce revenue-generating content. Thus, I conclude hereby,

Maximum numbers of YouTube consumers seek content related to entertainment, music, and games.
Most of the subscribers that avail educational content resides in the US, India, Mexico, etc and similar trends go for the music industry.
Some of the highest revenue generating segments for YouTube platform is entertainment and music.
Based on the above conclusions it is safe to assume and infer that contents that have been developed around entertainment, music, and games targeting audiences in India, US and Britain will do better in terms of acquired subscribers and revenue generated.


### Licence and Dataset Source

This project is distribute under [MIT](https://opensource.org/licenses/MIT) License.

In this Porject I have analysed Youtube Subscriber data available at kaggle open dataset [here](https://www.kaggle.com/libinmathew264/youtube-top-4000-channels-based-on-subscribers). Dataset ownership and license information can also be found with same link.
