Metis Bootcamp - Unsupervised Learning

Project Proposal

Emily Lorenzen

06/16/2021

# Natural language processing of the Nootropic Subreddity

## Question/Need:
Nootropics are drugs or supplements that are claiemd to improve cognitive functions and performance. Use of nootropics are on the rise  amongst students and business professionals, particular those within silicon valley. However, very little information about their efficacy or safety is available about these drugs. To gleen information about different nootropics I will use natural language processing to analyze discussions on different nootropics.  

## Data:
Data will obtained from the subreddit r/nootropics. Post titles, body and comments will all be included.

A single unit of data will be a single post, that has a primary key of a post ID. 

## Tools:
PRAW - data acquisition from reddit
Pandas/numpy/python - data cleaning and EDA
NLKT, Scapy - data pre-processing, vectorization and tokenization
Sklearn - dimensionality reduction, modeling, evaluation
Seaborn/matplotlib - graphing

## Minimum Viable Product:
For the minimum viable product, I will create a word cloud after removing stop words. 