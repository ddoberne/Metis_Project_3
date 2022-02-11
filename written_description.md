# Making It Big on Twitch
## Background
The rise of YouTube and Twitch has made some individual entertainers very, very wealthy and famous, and their success has subsequently opened up further career opportunities for them. For many, this is their dream; "making it" on social media like YouTube or Twitch to gain popularity and make a living.

The problem: the job title of "Social Media Personality" is one that is rapidly developing and without abundant historical precedent. For many, the best strategy they have at their disposal is trial and error, a very time-intensive and inconsistent process. Furthermore, there's a gigantic risk of failure along with little guarantee of payment, where somebody can spend endless hours for little monetary gain. The goal of this project is to provide insights in this rapidly developing field that can give someone an amount of certainty they wouldn't have otherwise, while saving them a lot of time. The impact hypothesis is that data from existing streamers who make a living off Twitch can help inform how much success somebody entering the field will have.

This project is directed at [mcd00dle](https://www.twitch.tv/mcd00dle), a Twitch streamer with a modest following who is trying to decide if she wants to pursue playing music on Twitch as a career or become a music teacher. This project will be able to provide statistic-backed insights to help inform whether she could feasibly pursue a career in social media, and if so, what her best chance is for success. This is a large upgrade over the anecdotal evidence and survivor bias that is pervasive in the field.

## Data
Viewership data of the top 1600 music streamers from the past 3 months was taken from [sullygnome](https://sullygnome.com/). That data was cross-referenced with subscription data from [twitchstats](https://twitchstats.net/) to provide income and date of account creation.

Data analysis showed that roughly a third of partnered streamers had monthly base income of at least $1000 before tips. These streamers typically streamed between 20-100 hours per month, with base income topping out at $13,500 after excluding outliers. There was a wide variety of start dates for streamers, so success wasn't entirely skewed toward first adopters. It is definitely a competitive field, but not a strictly exclusive one.

Data for further exploration can be taken from the "About" page of each streamer on [Twitch.tv](https://www.twitch.tv). Streamers provide links to their other social media platforms, which has follower information that can be scraped or be fed into another aggregate site similar to the ones (sullygnome, twitchstats) already used.

While arguably the most important aspect of an entertainer's success, how entertaining they are, is not easily quantifiable, speed of growth on various platforms could be used as a proxy. 
## Design

The next step of the project would be to incorporate data from other social media sites and make use of growth over time.

Further EDA will seek to answer the following questions:
* Can growth over time give us useful information about a streamer's potential?
* What are the indicators of success on Twitch given other social media platforms?
* Do certain other platforms help favor growth over income or vice versa? Eg. does TikTok bring in a lot of followers who don't pay for a subscription?
* How does account creation date affect channel growth? Eg. was Facebook successful in the early '10s but less successful later?
* Can a robust model be made to predict which channels will or will not enjoy monetary success?

Most importantly, the process will be iterative to keep up with the fast-changing landscape of social media.
## Tools/Techniques
* BeautifulSoup and Selenium were used for web scraping
* pandas was used to convert the scraped data into .csv form
* Google Sheets was used to merge the datasets, calculate new fields, clean the data, and filter the data for presentation
* Tableau was used for visualization
## Communication
The findings from preliminary EDA are available on a [Tableau dashboard](https://public.tableau.com/app/profile/dayv.doberne/viz/TwitchMusicbyStreamerFinal/Dashboard1?publish=yes) and in [presentation slides](/Making%20It%20Big%20on%20Twitch.pdf). Furthermore, the project will be presented in a five-minute presentation and in an article on [my blog](https://ddoberne.wordpress.com/).
## Just For Fun
[Alex Moukala on artistry and recognition on social media](https://twitter.com/alex_moukala/status/1488152170721681408?s=20&t=0YW9O0fEJYABXqkL5OtFgw)
