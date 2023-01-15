# SheHacks+ 7
**Ashley Ferreira**

**January 15-17, 2023 @WesternU**
The first actual hackathon I've gone to. Mostly just enjoying the events and meeting new people but also playing around with the Cohere API for the first time. 

Some interesting ideas I am thinking about:
- Putting UN resolutions into normal person speak (but only a summary, allow for multilingual?)
- Semantic search of UN resolutions (using embeddings, and also plotting these?)
- Extracting country votes from UN transcripts (even making a table?)
- Extracting stances of countries on issues from UN transcripts, summarizing these and doing clustering using embeddings?
- Classify ?
- Just embed resolutions and cluster, then colour in stuff like Tableau to make it interactice and publish online. To do this setup something like this setup ID to link date, country, name, resolution ID and all. Will probably need to do some PCA stuff to reduce dims enough. Look into topic modelling for this. Super ideal is summary + classification on summary to also link to number.

Resources:
- [UNGA Resoltions JSON Source](https://github.com/ICT4SD/UN-General-Assembly-Resolutions-and-Voting-Patterns)
- Transcripts

Questions:
- What is the token limit?
- Are there other summarization things to use like TLDR?
- Way to get this UN data with an API?
- Struggling on summarizing longer sections of text (even that fit within token limit), any tips online?
- Are there existing summaries you can put in simpler words instead?
- Datasets that already exist with resolution text? Way to easily scrape it?

Notes:
- Can add examples like shown on website
- Can be useful to get votes from things not passed?

[Link to Tableau visualization](https://prod-ca-a.online.tableau.com/#/site/ungaresolutions/workbooks/77336?:origin=card_share_link)
