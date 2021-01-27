


South America Tweet Visualization
For this project, I use Twitter data to analyze language use in Tweets in South America. I use the "rtweet" package to stream and process tweets using the Twitter API. I have not included the actual streamed Twitter data in this repository for anonymity and confidentiality reasons. I then used a combination of the "ggplot2" and "maps" packages to create the visualization.

This repository is organized as follows.

proj/
├── scipts/
├── graphics/
└── data/
Highlights
The map visualization is interesting for a few reasons. First of all, it demonstrates the usefulness of the Twitter language data. This data required some cleaning but the clear division between Spanish and Portuguese Tweets along the Brazil border, for example, validates the accuracy of this data and visualization method.

For the most part the languages are distributed as might be expected. The occasional Italian Tweets in Chile and Argentina were somewhat surprising to me, as were the few Tagalog tweets in Brazil.

The visualization also gives some insight into where people tweet most often -- or at least where they were tweeting most often when I was streaming. There is certainly some correlation between where people tweet most and where most people live, but an interesting extension of this exploration might be to compare this kind of visualization with a population density one. This could uncover discrepancies in Twitter usage across countries, regions, and languages.

References
Some ideas and code were borrowed from Friedrich Geiecke (Assistant Professor, The London School of Economics and Political Science).