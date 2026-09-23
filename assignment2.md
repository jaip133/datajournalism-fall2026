# Assignment 2: Build onto an Existing Database

Comparing Best Picture Oscar winners and Highest Domestic Grossing films since 1975, have Oscar winners become more or less profitable compared to blockbusters?

## Original Links

- [Best Picture winners since 1975](https://awardsdatabase.oscars.org/search/getresults?query=%7B%22Sort%22%3A%223-Award%20Category-Chron%22%2C%22AwardCategory%22%3A%5B%2219%22%5D%2C%22AwardShowNumberFrom%22%3A98%2C%22AwardShowNumberTo%22%3A48%2C%22Search%22%3A30%2C%22IsWinnersOnly%22%3Atrue%7D)
- [Highest Grossing Films in the USA](https://en.wikipedia.org/wiki/List_of_highest-grossing_films_in_the_United_States_by_year#By_in-year_release)

## Original Databases

The database of Oscar winners was taken from the Oscar's website and includes the winner for Best picture for every year from 1975-2025 and the director. There aren't really any limitations for this as it's just a list of award winners. The other database I used is a list of the highest grossing films in the US from Wikipedia. The source used by Wikipedia was Box Office Mojo, which is reputable for reporting film profits. This set could be limited because it doesn't account for inflation, it also is reporting domestic profits, while some Oscar winners can be international films. The Wikipedia list also only started in 1977, so I used Box Office Mojo to find the highest grossing films for 1975 and 1976.

## My Question

I wanted to compare the profits of Best Picture winners to the highest grossing films of the last 50 years and see how the difference has changed. Have Oscar winning films gotten more or less profitable over time?

## Methods

I found the domestic gross for every Best Picture winner from 1975-2025 (excluding 2022 because the Best Picture Winner, "CODA," did not have a domestic release. I added a column for the difference between the profits of each pair of movies by dividing the profit of the highest grossing film by the profit of the Best Picture winner. I used division for this and not a difference in dollars because I wanted to avoid inflation skewing things too much. I also added a column averaging this difference for each 10 year period to easily compare how the trend has changed.

## Results

The results I found are that overall, the gap in profit between Best Picture winning films and the biggest blockbusters of the year has gotten wider over the decades.

## Expanded Dataset

[Link to expanded dataset](https://github.com/jaip133/datajournalism-fall2026/blob/main/Best%20Picture%20%2B%20Highest%20Grossing.csv)

## AI Disclosure

I used Claude AI to help brainstorm ideas for movie related datasets and questions to ask, but ultimately went in my own direction.
