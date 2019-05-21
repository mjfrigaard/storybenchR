Data Journalism in R (storybench.org)
================
Martin Frigaard
compiled on 2019-05-21

  - [Welcome to `StorybenchR`](#welcome-to-storybenchr)
      - [01-getting-started-with-r-in-rstudio-notebooks](#getting-started-with-r-in-rstudio-notebooks)
      - [02-getting-started-with-tidyverse-in-r](#getting-started-with-tidyverse-in-r)
      - [03-how-to-explore-and-manipulate-a-dataset-from-the-fivethirtyeight-package-in-r](#how-to-explore-and-manipulate-a-dataset-from-the-fivethirtyeight-package-in-r)
      - [04-how-to-manipulate-data-with-dplyr-in-r](#how-to-manipulate-data-with-dplyr-in-r)
      - [05-getting-started-with-data-visualization-in-r-using-ggplot2](#getting-started-with-data-visualization-in-r-using-ggplot2)
      - [06-welcome-to-data-journalism-in-r](#welcome-to-data-journalism-in-r)
      - [07-twitter-plus-r](#twitter-plus-r)
      - [08-sentiment-analysis-of-donald-trump’s-tweets](#sentiment-analysis-of-donald-trumps-tweets)
      - [09-how-to-merge-and-clean-up-multiple-csvs-using-r](#how-to-merge-and-clean-up-multiple-csvs-using-r)
      - [10-working-with-the-new-york-times-api-in-r](#working-with-the-new-york-times-api-in-r)
      - [11-getting-started-with-stringr-for-textual-analysis-in-r](#getting-started-with-stringr-for-textual-analysis-in-r)
      - [12-how-to-plot-state-by-state-data-on-a-map-of-the-us-in-r](#how-to-plot-state-by-state-data-on-a-map-of-the-us-in-r)
      - [13-how-to-build-an-animated-map-of-tweets-about-the-nba-finals-in-r](#how-to-build-an-animated-map-of-tweets-about-the-nba-finals-in-r)
      - [14-using-french-wine-reviews-to-understand-tf-idf-a-measure-of-how-unique-a-word-is-to-a-document](#using-french-wine-reviews-to-understand-tf-idf-a-measure-of-how-unique-a-word-is-to-a-document)
      - [15-mapping-search-data-from-google-trends-in-r](#mapping-search-data-from-google-trends-in-r)
      - [16-exploring-beto-o’rourke-and-ted-cruz-ads-on-facebook-using-r](#exploring-beto-orourke-and-ted-cruz-ads-on-facebook-using-r)
      - [17-how-to-get-twitter-data-with-rtweet-in-r](#how-to-get-twitter-data-with-rtweet-in-r)
      - [18-how-to-install-r-on-a-jupyter-notebook](#how-to-install-r-on-a-jupyter-notebook)
      - [19-a-data-history-of-popular-hip-hop](#a-data-history-of-popular-hip-hop)
      - [20-how-to-map-point-data-and-polygon-shapefiles-in-r](#how-to-map-point-data-and-polygon-shapefiles-in-r)
      - [21-bringing-textual-analysis-tools-to-judge-brett-kavanaugh’s-latest-opinion](#bringing-textual-analysis-tools-to-judge-brett-kavanaughs-latest-opinion)
      - [22-scraping-html-tables-and-downloading-files-with-r](#scraping-html-tables-and-downloading-files-with-r)
      - [23-from-deep-learning-to-clean\_names-resources-from-data-journalism-in-r](#from-deep-learning-to-clean_names-resources-from-data-journalism-in-r)
      - [24-why-sharon-machlis-wrote-a-book-on-r-for-journalists](#why-sharon-machlis-wrote-a-book-on-r-for-journalists)
      - [25-pivoting-data-from-columns-to-rows-in-the-tidyverse](#pivoting-data-from-columns-to-rows-in-the-tidyverse)
      - [26-exploring-bike-rental-behavior-using-r](#exploring-bike-rental-behavior-using-r)
      - [27-how-to-model-with-gradient-boosting-machine-in-r](#how-to-model-with-gradient-boosting-machine-in-r)
      - [28-how-to-access-apis-in-r](#how-to-access-apis-in-r)
      - [29-how-to-build-a-bubble-chart-of-individuals-mentioned-in-the-mueller-report](#how-to-build-a-bubble-chart-of-individuals-mentioned-in-the-mueller-report)
      - [29-how-to-build-a-website-with-blogdown-in-r](#how-to-build-a-website-with-blogdown-in-r)
      - [30-exploring-chicago-rideshare-data-in-r](#exploring-chicago-rideshare-data-in-r)

# Welcome to `StorybenchR`

This is a series of tutorials from Data Journalism in R from
[Storybench.org](http://www.storybench.org/category/data-journalism-in-r/)
using the `tidyverse`.

    ## Registered S3 methods overwritten by 'ggplot2':
    ##   method         from 
    ##   [.quosures     rlang
    ##   c.quosures     rlang
    ##   print.quosures rlang

    ## ⬢ __  _    __   .    ⬡           ⬢  . 
    ##  / /_(_)__/ /_ ___  _____ _______ ___ 
    ## / __/ / _  / // / |/ / -_) __(_-</ -_)
    ## \__/_/\_,_/\_, /|___/\__/_/ /___/\__/ 
    ##      ⬢  . /___/      ⬡      .       ⬢

All tutorials are listed below (in order). Some of these posts have been
updated with current package usage/functions. In this case, the code for
these tutorials might be different from what is in the original post.

## 01-getting-started-with-r-in-rstudio-notebooks

Original post: [Getting Started With R in RStudio
Notebooks](http://www.storybench.org/getting-started-r-rstudio-notebooks/)

Changes: nothing to change on this

Current post: NA

## 02-getting-started-with-tidyverse-in-r

Original post: [Getting Started with tidyverse in
R](http://www.storybench.org/getting-started-with-tidyverse-in-r/)

Changes: This has been changed a lot with the new `tidyr` functions

Current post: [Data Journalism with R - Storybench tidyr
pivoting](https://github.com/mjfrigaard/storybenchR/tree/master/02.1-data-in-tidyverse)

## 03-how-to-explore-and-manipulate-a-dataset-from-the-fivethirtyeight-package-in-r

Original post: [How to explore and manipulate a dataset from the
fivethirtyeight package in
R](http://www.storybench.org/how-to-explore-a-dataset-from-the-fivethirtyeight-package-in-r/)

Changes: changes were made to expand these functions and examples

Current post: [How to explore and manipulate a dataset from the
fivethirtyeight package in
R](https://github.com/mjfrigaard/storybenchR/tree/master/03.1-tidyr-separate-unite-spread-gather)

## 04-how-to-manipulate-data-with-dplyr-in-r

Original post: [How to manipulate data with dplyr in
R](http://www.storybench.org/how-to-manipulate-data-with-dplyr-in-r/)

Changes: Nothing has changed on this tutorial.

Current post: NA

## 05-getting-started-with-data-visualization-in-r-using-ggplot2

Original post: [Getting started with data visualization in R using
ggplot2](http://www.storybench.org/getting-started-data-visualization-r-using-ggplot2/)

Changes: This is now a two-part intro. Part one is on Github (expanded a
bit).

Current post(s):

Part 1: [Getting started with data visualization in R using ggplot2
(part 1)](https://github.com/mjfrigaard/storybenchR/tree/master/04.1-ggplot2-intro)

Part 2: is still coming…

## 06-welcome-to-data-journalism-in-r

Original post: [Welcome to Data Journalism in
R](http://www.storybench.org/welcome-to-data-journalism-in-r-2/)

Changes: Post announcing official section on Storybench.

Current post:

## 07-twitter-plus-r

Original post: [Twitter + R](http://www.storybench.org/twitter-r/)

Changes: Accessing twitter with old twitter package. Now we use `rtweet`

Current post:

## 08-sentiment-analysis-of-donald-trump’s-tweets

Original post: [Sentiment analysis of (you guessed it\!) Donald Trump’s
tweets](http://www.storybench.org/sentiment-analysis-of-you-guessed-it-donald-trumps-tweets/)

Changes:

Current post:

## 09-how-to-merge-and-clean-up-multiple-csvs-using-r

Original post: [How to merge and clean up multiple CSVs using
R](http://www.storybench.org/merge-clean-multiple-csvs-using-r/)

This is the intro to `for` loops and iteration.

Changes:

Current post:

## 10-working-with-the-new-york-times-api-in-r

Original post: [Working with The New York Times API in
R](http://www.storybench.org/working-with-the-new-york-times-api-in-r/)

Changes:

Current post:

## 11-getting-started-with-stringr-for-textual-analysis-in-r

Original post: [Getting started with stringr for textual analysis in
R](http://www.storybench.org/getting-started-stringr-textual-analysis-r/)

Changes:

Current post:

## 12-how-to-plot-state-by-state-data-on-a-map-of-the-us-in-r

Original post: [How to plot state-by-state data on a map of the U.S. in
R](http://www.storybench.org/plot-state-state-data-map-u-s-r/)

Changes:

Current post:

## 13-how-to-build-an-animated-map-of-tweets-about-the-nba-finals-in-r

Original post: [How to build an animated map of tweets about the NBA
finals in
R](http://www.storybench.org/build-animated-map-tweets-nba-finals-r/)

Changes:

Current post:

## 14-using-french-wine-reviews-to-understand-tf-idf-a-measure-of-how-unique-a-word-is-to-a-document

Original post: [Using French wine reviews to understand TF-IDF, a
measure of how unique a word is to a
document](http://www.storybench.org/using-french-wine-reviews-understand-tf-idf-measure-unique-word-document/)

Changes:

Current post:

## 15-mapping-search-data-from-google-trends-in-r

Original post: [Mapping search data from Google Trends in
R](http://www.storybench.org/mapping-search-data-from-google-trends-in-r/)

Changes:

Current post:

## 16-exploring-beto-o’rourke-and-ted-cruz-ads-on-facebook-using-r

Original post: [Exploring Beto O’Rourke and Ted Cruz ads on Facebook
using
R](http://www.storybench.org/exploring-beto-orourke-ted-cruz-ads-facebook-using-r/)

Changes:

Current post:

## 17-how-to-get-twitter-data-with-rtweet-in-r

Original post: [How to get Twitter data with rtweet in
R](http://www.storybench.org/get-twitter-data-rtweet-r/)

Changes:

Current post:

## 18-how-to-install-r-on-a-jupyter-notebook

Original post: [How to install R on a Jupyter
notebook](http://www.storybench.org/install-r-jupyter-notebook/)

Changes:

Current post:

## 19-a-data-history-of-popular-hip-hop

Original post: [A Data History of Popular
Hip-Hop](http://www.storybench.org/a-data-history-of-popular-hip-hop/)

Changes:

Current post:

## 20-how-to-map-point-data-and-polygon-shapefiles-in-r

Original post: [How to map point data and polygon shapefiles in
R](http://www.storybench.org/how-to-map-point-data-and-polygon-shapefiles-in-r/)

Changes:

Current post:

## 21-bringing-textual-analysis-tools-to-judge-brett-kavanaugh’s-latest-opinion

Original post: [Bringing textual analysis tools to Judge Brett
Kavanaugh’s latest
opinion](http://www.storybench.org/bringing-textual-analysis-tools-to-judge-brett-kavanaughs-latest-opinion/)

Changes:

Current post:

## 22-scraping-html-tables-and-downloading-files-with-r

Original post: [Scraping HTML tables and downloading files with
R](http://www.storybench.org/scraping-html-tables-and-downloading-files-with-r/)

Changes:

Current post:

## 23-from-deep-learning-to-clean\_names-resources-from-data-journalism-in-r

Original post: [From deep learning to clean\_names(), resources from
Data Journalism in
R](http://www.storybench.org/from-deep-learning-to-clean_names-resources-from-data-journalism-in-r/)

Changes:

Current post:

## 24-why-sharon-machlis-wrote-a-book-on-r-for-journalists

Original post: [Why Sharon Machlis wrote a book on R for
journalists](http://www.storybench.org/why-sharon-machlis-wrote-a-book-on-r-for-journalists/)

Changes:

Current post:

## 25-pivoting-data-from-columns-to-rows-in-the-tidyverse

Original post: [Pivoting data from columns to rows (and back\!) in the
tidyverse](http://www.storybench.org/pivoting-data-from-columns-to-rows-and-back-in-the-tidyverse/)

Changes:

Current post:

## 26-exploring-bike-rental-behavior-using-r

Original post: [Exploring bike rental behavior using
R](http://www.storybench.org/exploring-bike-rental-behavior-using-r/)

Changes:

Current post:

## 27-how-to-model-with-gradient-boosting-machine-in-r

Original post: [How to model with gradient boosting machine in
R](http://www.storybench.org/tidytuesday-bike-rentals-part-2-modeling-with-gradient-boosting-machine/)

Changes:

Current post:

## 28-how-to-access-apis-in-r

Original post: [How to access APIs in
R](http://www.storybench.org/how-to-access-apis-in-r/)

Changes:

Current post:

## 29-how-to-build-a-bubble-chart-of-individuals-mentioned-in-the-mueller-report

Original post: [How to build a bubble chart of individuals mentioned in
the Mueller
report](http://www.storybench.org/how-to-build-a-bubble-chart-of-individuals-mentioned-in-the-mueller-report/)

Changes:

Current post:

## 29-how-to-build-a-website-with-blogdown-in-r

Original post: [How to build a website with Blogdown in
R](http://www.storybench.org/how-to-build-a-website-with-blogdown-in-r/)

Changes:

Current post:

## 30-exploring-chicago-rideshare-data-in-r

Original post: [Exploring Chicago rideshare data in
R](http://www.storybench.org/exploring-chicago-rideshare-data/)

Changes:

Current post:
