# Zoo Elastic Search

## Description

This project is divided into 4 parts:
- [Zoo Data API](https://github.com/msuddin/zoo-data-api) (Java Rest API) -> Talks to Zoo Elastic Search
- [Zoo Elastic Search](https://github.com/msuddin/zoo-elastic-search) (dockerized Elasticsearch instance)
- [Zoo Search API](https://github.com/msuddin/zoo-search-api) (Java Rest API) -> Pulls from Zoo Elastic Search
- [Zoo UI](https://github.com/msuddin/zoo-ui) (React APP) -> Pulls data from Zoo Search API

Zoo Elastic Search is a dockerized Elasticsearch instance.
It is only responsible for providing a running instance of Elasticsearch.

## Instructions

To run the docker container (from command line):

```
docker compose up
```

## Learning Outcomes

Here are the learning outcomes of this project.

- [x] To use Docker to run an instance of Elasticsearch
- [ ] More to follow