[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14095218.svg)](https://doi.org/10.5281/zenodo.14095218) [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15046657.svg)](https://doi.org/10.5281/zenodo.15046657)[![DOI](https://zenodo.org/badge/DOI/110.5281/zenodo.17348234.svg)](https://doi.org/10.5281/zenodo.17348234)


# CLINT project data for the study of user reliability, ideological bias, and polarization


This repository contains the Twitter and YouTube data used in the project [**CLINT**](https://clint-project.github.io/) during the tasks focused on the network mapping of user reliability and the study of related emerging social phenomena. The results are published in the paper:

**Bassolas, A., Massachs, J., Cozzo, E., & Vicens, J. (2025).** [*Multifaceted polarization and information reliability in climate change discussions on social media platforms*](https://royalsocietypublishing.org/doi/10.1098/rsos.241974). *Royal Society Open Science, 12*(11), 241974.

## Table of Contents

- [Open Twitter Data](#open-twitter-data)  
  - [Statistics Summary](#statistics-summary)  
- [Annotated Twitter Data](#annotated-twitter-data)  
- [Open YouTube Data](#open-youtube-data)  
  - [Statistics Summary](#youtube-statistics-summary)  

## Open Twitter data

We extracted data related to climate change discussions in Twitter across four topics: [the 27th United Nations Climate Change Conference](datasets/twitter/cop27), [the Sixth Assessment Report of the United Nations Intergovernmental Panel on Climate Change](datasets/twitter/ipcc), [Climate Refugees](datasets/twitter/climate-refugees
) and [Doñana Natural Park](datasets/twitter/donana).
We used the Twitter’s search to gather historical tweets and the streaming API to follow specified accounts and also 
collect in real-time tweets that mention specific keywords. To comply with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), 
we are only publicly releasing the tweet IDs of the collected tweets. The data is released for non-commercial research use. 

**With Twitter's changes to its Academic API policies, it’s no longer possible to collect or rehydrate tweets 
as we usually did, however we open data in case at some point it will become feasible to do it.**


### Statistics summary

| Dataset           | IPCC		| Doñana	| Climate Refugees    	| COP27    	|
| --                | ----              | ----          | ----			| -----		|
| Number of tweets  | 352,723		| 1,487,425	| 1,938,932         	| 6,225,508     |
| Number of authors | 157,056		| 290,782       | 841,454           	| 1,351,903	|
| First tweet date  | 2023-03-18	| 2019-01-01    | 2008-03-10        	| 2022-09-01	|
| Last tweet date   | 2023-03-26	| 2023-04-30    | 2022-12-31        	| 2022-11-27	|

## Annotated Twitter data

The annotated data available [datasets/twitter_annotated/tweet_annotated.csv](datasets/twitter_annotated/tweet_annotated.csv) includes tweets from four different datasets: COP27, IPCC, Climate Refugees and Doñana. Each dataset is represented by 80 tweets.
The information included in the dataset is the following:

network_id – ID of the network the tweet belongs to.
community_user – Community of the source user.
community_referenced – Community of target user.
id – Unique tweet identifier.
original_tweet – Text of the tweet in its original language.
translated_text – Translated text of the tweet.
model_score – Score assigned by the predictive model.
negativity_score_reviewer1 – Negativity score from reviewer 1.
negativity_score_reviewer2 – Negativity score from reviewer 2.
negativity_score_reviewer3 – Negativity score from reviewer 3


## Open YouTube data

We extracted the YouTube video ids the Tweets in each of the four different datasets: [COP27](datasets/youtube/cop27_youtube_id.csv), [IPCC](datasets/youtube/ipcc_youtube_id.csv), [Climate Refugees](datasets/youtube/refugees_youtube_id.csv) and [Doñana](datasets/youtube/donana_youtube_id.csv).

Each dataset includes the YouTube video ids identified in each network.

### Statistics summary

| Dataset             | IPCC | Doñana | Climate Refugees | COP27 |
|------------------|------|--------|----------------|-------|
| Number of videos  | 154  | 31     | 213            | 610   |
 


