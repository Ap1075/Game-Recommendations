## BERT based game recommendations.

The system uses a semantic search approach using [Sentence-BERT](https://arxiv.org/abs/1908.10084).

### 2 step approach:

1. Scraping the data from Gamestop.
2. Semantic search on data using user queries.

Data scraping is handled by price_extractor and steam_dat notebooks while bert.ipynb contains the code and methodology for searching the data for games within a user specified budget. 
