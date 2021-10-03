# News-Aggregator-Web-App
A web application which aggregates data (news articles) from multiple websites. Then presents the data in one location.

ews aggregator service is a very important start of the day.

There are various publications and news sites online. They publish their content on multiple platforms. Now, imagine when you open 10-20 news sites every day. The time you waste to gain information. Information gain is everything in today’s world.
In a news aggregator, you can select the websites you want to follow. Then the news aggregator collects the articles for you. And, you are just a click away to get information from various websites.

our news aggregator will work in 3 steps:

It scrapes the web for the articles. (In this Django project, we are scraping a website called theonion)
Then it stores the article’s images, links, and title.
The stored objects in the database are served to the client. The client gets information in a nice template.
