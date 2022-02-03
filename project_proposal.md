# Metis Project 3: Making It as a Musician on Twitch
## The Summary
The rise of YouTube and Twitch has made some individual entertainers very, very wealthy and famous, and their success has subsequently opened up opportunities for them in the future. For many, this is their dream; "making it" on social media like YouTube or Twitch to gain popularity and make a living. However, as these platforms have been seen as more legitmate, organizations that are already established via other means have joined the platform, making it more difficult for individuals to stand out. The scope of this project is to determine whether "making it" on Twitch is still a reality, and if it is, trying to determine what is working for the people who are succeeding.
## The Problem
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">A reminder for (myself and) anyone else who wants it: a lower sub count than usual doesn’t mean your content is suddenly worthless, it means that people are making cuts after post holiday spending and tightening up finances as a result of New Years resolutions</p>&mdash; lara6683 (@Larawithabird) <a href="https://twitter.com/Larawithabird/status/1484380173097377797?ref_src=twsrc%5Etfw">January 21, 2022</a></blockquote>

For musicians who make their living by playing online, a steady source of income can be very difficult to come by. These musicians rely on tips and subscriptions to services like Twitch and Patreon for their income. Especially for people starting out, finding a path to monetization and full-time income can be daunting.

Lara de Wit has been performing music online for over a decade. She's an example of someone who has "made it" -- her popularity was earned through work on social media platforms, she has a dedicated following, she receives brand sponsorships, and has reliable financial support for somebody in this type of business. She is one of the very few, and there are many streamers trying to carve out an audience, and if possible, a living, following in her footsteps. The problem this project is trying to address is if somebody without an existing following can build one, and how that can be accomplished.

As streaming on Twitch is a relatively new avenue for success, the main method most people have been using to try to succeed is by trial and error. By incorporating data science methods to this project, I am hoping to eliminate a lot of the error of that process. If successful, this will save somebody trying to be successful a tremendous amount of time from trying methods that won't bear fruit.

For this project, I will be focusing on Calvin Thomas, a streamer that spends 10 hours a week performing his music on Twitch to try to earn a following and an income.
## The Data
Data will be taken from sullygnome.com, a site that tracks Twitch streamer metrics including viewership, stream time, growth over time, etc. Data can be downloaded as a csv. Streamers that fit the right profile will have data scraped from their Twitch "about" page to gain insight to their presence on other social media platforms. This data will then be used to inform any actionable insights.
## The Scope
Once data is collected, the first goal will be to classify the profile of somebody who is successful based on their Twitch metrics. Then, they will be grouped into different categories. For example, is this person famous from somewhere other than Twitch? Do they have a large following on Twitter or Instagram? How much or how regularly do they stream? Finally, analysis will be done to see if there can be an actionable prescription.
## The Tools
Google Sheets will be used for preliminary analysis. Selenium and BeautifulSoup will be necessary for any future web scraping.
