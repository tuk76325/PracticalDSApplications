# PracticalDSApplications
This repository contains modules that have been completed to practice data handling with real world applications.

# CHESS RATINGS
This problem builds on knowledge of Python data structures, string processing, and implementing mathematical functions. Here we will extract data from a recent chess tournament that captures players' ratings at the start of the tournament and the outcome of all games played. We will then use that data to calculate expected wins based on the matchups and compare our expectation with the observed results. Finally we will determine the updated Elo ratings for the players.

# REDDIT API DATA
The posts on the more active topics (called "sub-reddits") are a veritable treasure trove of information on the "pulse" of that topic. Additionally, all of this information is freely and publicly accessible via a REST API. For this problem we used the REST API to pull the "all-time" top 800 posts from this sub-reddit (as of summer 2022) for analysis. Final product of this was the construction of a similarity matrix, which showcased the similarity of scores based on the mathematical function of Cosine Similarity.

# SOCIAL MEDIA FRIEND ANALYSIS
In this notebook, social media data from Twitter and FourSquare will be analyzed. The ultimate goal will be to help people find others with common interests.

The (anonymized) data consists of the following:

    A collection of places, or points of interest (POIs), like restaurants, movie theaters, post offices, museums, and so on.
    A database of cities.
    A collection of check-ins, that is, the places that a specific person has visited.
    Existing connections, that is, "who follows whom" type relationships.

We will analyze this data and then, by the very last exercise, create a function that can, for a given person, recommend other people they might be compatible with based on their affinity for the same place

# FRAUD DETECTION IN EMAIL  
In this scenario, the US Government is investigating possible fraud committed by a company. The company has a large email archive, so the investigators are asking for your analytics help.

Thankfully, someone created a neat analysis tool that, given a collection of objects and their relationships to one another, can rank the objects by the "importance" of their connections. But to use that tool, we need to take the raw email archive and convert it into the form that the tool expects.

Here is our overall workflow for this problem:

    Part A: Two warm-up exercises
    Part B: The data: Enron emails and "email objects"
    Part C: Data cleaning and preliminary analysis
    Part D: Interfacing with the analysis tool

# NEW YORK TIMES CAPTION CONTEST
This problem is a data mining task that exercises basic data structure manipulation, strings (including regex!), and translation of simple math to code. Every week, the New Yorker magazine runs a cartoon caption contest. It presents readers with a cartoon having no caption, and then invites readers to submit their ideas. 
The data. The New Yorker allows readers to vote on the submitted captions. For this problem, we scraped the voting website to get these submissions, which will serve as your dataset. (These data are just the captions, not the votes.)

# HOW PARTISAN IS THE US CONGRESS
The United States Congress is the part of the US government that makes laws for the entire country. It is dominated by two rival political parties, the Democrats and the Republicans. One would expect that these parties oppose each other on most issues but occasionally agree.

Some have conjectured that, over time, the two parties agree less and less, which would reflect a perceived growing ideological or political divide in the US. But is that the real trend? In this problem, we'll explore this question using data collected by ProPublica, a nonprofit investigative media organization.

# ANALYSIS OF NYC 311 CALLS
We will start with a large database of complaints filed by residents of New York City via 311 calls. The full dataset is available at the NYC open data portal. Our subset is about 6 GB and 10 million complaints, so we can infer that a) we might not want to read it all into memory at once, and b) NYC residents have a lot to complain about. (Maybe only conclusion "a" is valid.) The notebook then combines the use of sqlite, pandas, and bokeh.


