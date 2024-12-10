# Case study dog breeds

This repo contains a data analysis of dog breed data from TidyTuesday.

## Structure

- `scripts`: python scripts for collecting and cleaning data.
- `report`: a beautiful table of dog breed information.
- `raw-data`: data on [dog breed traits](https://github.com/rfordatascience/tidytuesday/tree/main/data/2022/2022-02-01) collected from tidytuesday.

## Data

Raw data from tidytuesday is as follows:

- `raw-data/breed_traits.csv`: each row is a dog breed, with columns for traits.
- `raw-data/trait_description.csv`: each row is a trait, with a column describing the trait, and columns describing the low and high trait scores.
- `raw-data/breed_rank.csv`: popularity of dog breeds from 2013-2020.

Moreover, the scripts pull breed images and descriptions from wikipedia (https://en.wikipedia.org/wiki/List_of_dog_breeds):

- `data/wiki_breed_descriptions.csv`: each row is a dog breed, with the path to a thumbnail and a description pulled from wikipedia.

## Report

- `report/index.qmd`: Generates an html with the dog breeds data, using reactable.
