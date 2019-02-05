# Build a Custom Search Engine with Node.js and Elasticsearch

## Requirements

* [Node.js](http://nodejs.org/) (min version v0.11.0)
* [Java Runtime Environment](https://java.com/en/) (min version 1.8)
* [Elasticsearch](https://www.elastic.co/)

## Installation Steps

1. Clone repo
2. Run `npm install`
3. Start Elasticsearch

## List of files in this repo:

1. `data.json`: sample data file
2. `index.js`: script for indexing the data in elasticsearch
3. `indices.js`: script to check indexing was successful
4. `search_all.js`: return all documents in one or more indices
5. `search_match.js`: match documents that contain specific values in a field
6. `search_multi_match.js`: search within multiple fields
7. `search_match_phrase.js`: match a complete phrase
8. `search_bool.js`: combining multiple queries
9. `filter.js`: basic filter functionality
10. `aggregations.js`: demonstration of how aggregations work
11. `suggest_term.js`: generate suggestions for search terms
12. `suggest_phrase.js`: generate suggestions for search phrases

