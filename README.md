Data Journalism in R (storybench.org)
================
Martin Frigaard
compiled on 2019-05-25

  - [Welcome to `StorybenchR`](#welcome-to-storybenchr)
      - [1) Getting Started With R in RStudio
        Notebooks](#getting-started-with-r-in-rstudio-notebooks)
      - [2) Getting Started with tidyverse in
        R](#getting-started-with-tidyverse-in-r)
      - [3) How to explore and manipulate a dataset from the
        fivethirtyeight package in
        R](#how-to-explore-and-manipulate-a-dataset-from-the-fivethirtyeight-package-in-r)
      - [4) How to manipulate data with dplyr in
        R](#how-to-manipulate-data-with-dplyr-in-r)
      - [5) Getting started with data visualization in R using
        ggplot2](#getting-started-with-data-visualization-in-r-using-ggplot2)
      - [6) Welcome to Data Journalism in
        R](#welcome-to-data-journalism-in-r)
      - [7) Twitter + R](#twitter-r)
      - [8) Sentiment analysis of (you guessed it\!) Donald Trump’s
        tweets](#sentiment-analysis-of-you-guessed-it-donald-trumps-tweets)
      - [9) How to merge and clean up multiple CSVs using
        R](#how-to-merge-and-clean-up-multiple-csvs-using-r)
      - [10) Working with The New York Times API in
        R](#working-with-the-new-york-times-api-in-r)
      - [11) Getting started with stringr for textual analysis in
        R](#getting-started-with-stringr-for-textual-analysis-in-r)
      - [12) How to plot state-by-state data on a map of the U.S. in
        R](#how-to-plot-state-by-state-data-on-a-map-of-the-u.s.-in-r)
      - [13) How to build an animated map of tweets about the NBA finals
        in
        R](#how-to-build-an-animated-map-of-tweets-about-the-nba-finals-in-r)
      - [14) Using French wine reviews to understand TF-IDF, a measure
        of how unique a word is to a
        document](#using-french-wine-reviews-to-understand-tf-idf-a-measure-of-how-unique-a-word-is-to-a-document)
      - [15) Mapping search data from Google Trends in
        R](#mapping-search-data-from-google-trends-in-r)
      - [16) Exploring Beto O’Rourke and Ted Cruz ads on Facebook using
        R](#exploring-beto-orourke-and-ted-cruz-ads-on-facebook-using-r)
      - [17) How to get Twitter data with rtweet in
        R](#how-to-get-twitter-data-with-rtweet-in-r)
      - [18) How to install R on a Jupyter
        notebook](#how-to-install-r-on-a-jupyter-notebook)
      - [19) A Data History of Popular
        Hip-Hop](#a-data-history-of-popular-hip-hop)
      - [20) How to map point data and polygon shapefiles in
        R](#how-to-map-point-data-and-polygon-shapefiles-in-r)
      - [21) Bringing textual analysis tools to Judge Brett Kavanaugh’s
        latest
        opinion](#bringing-textual-analysis-tools-to-judge-brett-kavanaughs-latest-opinion)
      - [22) Scraping HTML tables and downloading files with
        R](#scraping-html-tables-and-downloading-files-with-r)
      - [23) From deep learning to `clean_names()`, resources from Data
        Journalism in
        R](#from-deep-learning-to-clean_names-resources-from-data-journalism-in-r)
      - [24) Why Sharon Machlis wrote a book on R for
        journalists](#why-sharon-machlis-wrote-a-book-on-r-for-journalists)
      - [25) Pivoting data from columns to rows (and back\!) in the
        tidyverse](#pivoting-data-from-columns-to-rows-and-back-in-the-tidyverse)
      - [26) Exploring bike rental behavior using
        R](#exploring-bike-rental-behavior-using-r)
      - [27) How to model with gradient boosting machine in
        R](#how-to-model-with-gradient-boosting-machine-in-r)
      - [28) How to access APIs in R](#how-to-access-apis-in-r)
      - [29) How to build a bubble chart of individuals mentioned in the
        Mueller
        report](#how-to-build-a-bubble-chart-of-individuals-mentioned-in-the-mueller-report)
      - [30) How to build a website with Blogdown in
        R](#how-to-build-a-website-with-blogdown-in-r)
      - [31) Exploring Chicago rideshare data in
        R](#exploring-chicago-rideshare-data-in-r)

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
these tutorials might be different from what is in the Storybench post.

## 1\) Getting Started With R in RStudio Notebooks

Slug: 01-getting-started-with-r-in-rstudio-notebooks

Storybench post: [Getting Started With R in RStudio
Notebooks](http://www.storybench.org/getting-started-r-rstudio-notebooks/)

nothing to change on this

Updates: NA

    ## 01.0-getting-started-with-r-in-rstudio-notebooks.Rmd
    ## 01.1-getting-started-with-r-in-rstudio-notebooks.Rmd

## 2\) Getting Started with tidyverse in R

slug: 02-getting-started-with-tidyverse-in-r

Storybench post: [Getting Started with tidyverse in
R](http://www.storybench.org/getting-started-with-tidyverse-in-r/)

This has been changed a lot with the new `tidyr` functions

Updates: [Data Journalism with R - Storybench tidyr
pivoting](https://github.com/mjfrigaard/storybenchR/tree/master/02.1-data-in-tidyverse)

    ## 02-getting-started-with-tidyverse-in-r.Rmd
    ## 02-getting-started-with-tidyverse-in-r.md

## 3\) How to explore and manipulate a dataset from the fivethirtyeight package in R

Slug:
03-how-to-explore-and-manipulate-a-dataset-from-the-fivethirtyeight-package-in-r

Storybench post: [How to explore and manipulate a dataset from the
fivethirtyeight package in
R](http://www.storybench.org/how-to-explore-a-dataset-from-the-fivethirtyeight-package-in-r/)

changes were made to expand these functions and examples

Updates: [How to explore and manipulate a dataset from the
fivethirtyeight package in
R](https://github.com/mjfrigaard/storybenchR/tree/master/03.1-tidyr-separate-unite-spread-gather)

    ## 02-getting-started-with-tidyverse-in-r.Rmd
    ## 02-getting-started-with-tidyverse-in-r.md
    ## 02.1-tidydata-pipes-vars-obs-spread-gather-qplot.Rmd
    ## 02.1-tidydata-pipes-vars-obs-spread-gather-qplot.md
    ## 02.2-tidydata-group-pivot-long-wide.Rmd
    ## 02.2-tidydata-group-pivot-long-wide.md
    ## 02.3-tidydata-group-pivot-long-wide.Rmd
    ## 02.4-tidydata-group-pivot-long-wide.Rmd
    ## 02.4-tidydata-group-pivot-long-wide.md

## 4\) How to manipulate data with dplyr in R

Slug: 04-how-to-manipulate-data-with-dplyr-in-r

Storybench post: [How to manipulate data with dplyr in
R](http://www.storybench.org/how-to-manipulate-data-with-dplyr-in-r/)

Nothing has changed on this tutorial.

Updates: NA

    ## 05.1-manipulate-variables-with-dplyr.Rmd
    ## 05.2-manipulate-cases-with-dplyr.Rmd

## 5\) Getting started with data visualization in R using ggplot2

Slug: 05-getting-started-with-data-visualization-in-r-using-ggplot2

Storybench post: [Getting started with data visualization in R using
ggplot2](http://www.storybench.org/getting-started-data-visualization-r-using-ggplot2/)

This is now a two-part intro. Part one is on Github (expanded a bit).

updates(s):

    ## 04-ggplot2-for-viz.Rmd
    ## 04-ggplot2-for-viz.md
    ## 04.1-ggplot2-qplot.Rmd
    ## 04.1-ggplot2-qplot.md
    ## 04.2-ggplot2-extras.Rmd
    ## 04.2-ggplot2-extras.md
    ## 04.3-ggplot2-intro-to-visualizations.Rmd
    ## 04.3-ggplot2-intro-to-visualizations.md

Part 1: [Getting started with data visualization in R using ggplot2
(part 1)](https://github.com/mjfrigaard/storybenchR/tree/master/04.1-ggplot2-intro)

Part 2: is still coming…

## 6\) Welcome to Data Journalism in R

Slug: 06-welcome-to-data-journalism-in-r

Storybench post: [Welcome to Data Journalism in
R](http://www.storybench.org/welcome-to-data-journalism-in-r-2/)

Post announcing official section on Storybench.

Updates:

## 7\) Twitter + R

Slug: 07-twitter-plus-r

Storybench post: [Twitter + R](http://www.storybench.org/twitter-r/)

Accessing twitter with old twitter package. Now we use `rtweet`

Updates:

## 8\) Sentiment analysis of (you guessed it\!) Donald Trump’s tweets

Slug: 08-sentiment-analysis-of-donald-trump’s-tweets

Storybench post: [Sentiment analysis of (you guessed it\!) Donald
Trump’s
tweets](http://www.storybench.org/sentiment-analysis-of-you-guessed-it-donald-trumps-tweets/)

Updates:

## 9\) How to merge and clean up multiple CSVs using R

Slug: 09-how-to-merge-and-clean-up-multiple-csvs-using-r

Storybench post: [How to merge and clean up multiple CSVs using
R](http://www.storybench.org/merge-clean-multiple-csvs-using-r/)

This is the intro to `for` loops and iteration.

Updates:

## 10\) Working with The New York Times API in R

Slug: 10-working-with-the-new-york-times-api-in-r

Storybench post: [Working with The New York Times API in
R](http://www.storybench.org/working-with-the-new-york-times-api-in-r/)

Updates:

## 11\) Getting started with stringr for textual analysis in R

Slug: 11-getting-started-with-stringr-for-textual-analysis-in-r

Storybench post: [Getting started with stringr for textual analysis in
R](http://www.storybench.org/getting-started-stringr-textual-analysis-r/)

Updates:

## 12\) How to plot state-by-state data on a map of the U.S. in R

12-how-to-plot-state-by-state-data-on-a-map-of-the-us-in-r

Storybench post: [How to plot state-by-state data on a map of the U.S.
in R](http://www.storybench.org/plot-state-state-data-map-u-s-r/)

Updates:

## 13\) How to build an animated map of tweets about the NBA finals in R

13-how-to-build-an-animated-map-of-tweets-about-the-nba-finals-in-r

Storybench post: [How to build an animated map of tweets about the NBA
finals in
R](http://www.storybench.org/build-animated-map-tweets-nba-finals-r/)

Updates:

## 14\) Using French wine reviews to understand TF-IDF, a measure of how unique a word is to a document

SLug:
14-using-french-wine-reviews-to-understand-tf-idf-a-measure-of-how-unique-a-word-is-to-a-document

Storybench post: [Using French wine reviews to understand TF-IDF, a
measure of how unique a word is to a
document](http://www.storybench.org/using-french-wine-reviews-understand-tf-idf-measure-unique-word-document/)

Updates:

## 15\) Mapping search data from Google Trends in R

SLug: 15-mapping-search-data-from-google-trends-in-r

Storybench post: [Mapping search data from Google Trends in
R](http://www.storybench.org/mapping-search-data-from-google-trends-in-r/)

Updates:

## 16\) Exploring Beto O’Rourke and Ted Cruz ads on Facebook using R

Slug: 16-exploring-beto-o’rourke-and-ted-cruz-ads-on-facebook-using-r

Storybench post: [Exploring Beto O’Rourke and Ted Cruz ads on Facebook
using
R](http://www.storybench.org/exploring-beto-orourke-ted-cruz-ads-facebook-using-r/)

Updates:

## 17\) How to get Twitter data with rtweet in R

Slug: 17-how-to-get-twitter-data-with-rtweet-in-r

Storybench post: [How to get Twitter data with rtweet in
R](http://www.storybench.org/get-twitter-data-rtweet-r/)

Updates:

## 18\) How to install R on a Jupyter notebook

Slug: 18-how-to-install-r-on-a-jupyter-notebook

Storybench post: [How to install R on a Jupyter
notebook](http://www.storybench.org/install-r-jupyter-notebook/)

Updates:

## 19\) A Data History of Popular Hip-Hop

Slug: 19-a-data-history-of-popular-hip-hop

Storybench post: [A Data History of Popular
Hip-Hop](http://www.storybench.org/a-data-history-of-popular-hip-hop/)

Updates:

## 20\) How to map point data and polygon shapefiles in R

Slug: 20-how-to-map-point-data-and-polygon-shapefiles-in-r

Storybench post: [How to map point data and polygon shapefiles in
R](http://www.storybench.org/how-to-map-point-data-and-polygon-shapefiles-in-r/)

Updates:

## 21\) Bringing textual analysis tools to Judge Brett Kavanaugh’s latest opinion

Slug:
21-bringing-textual-analysis-tools-to-judge-brett-kavanaugh’s-latest-opinion

Storybench post: [Bringing textual analysis tools to Judge Brett
Kavanaugh’s latest
opinion](http://www.storybench.org/bringing-textual-analysis-tools-to-judge-brett-kavanaughs-latest-opinion/)

Updates:

## 22\) Scraping HTML tables and downloading files with R

Slug: 22-scraping-html-tables-and-downloading-files-with-r

Storybench post: [Scraping HTML tables and downloading files with
R](http://www.storybench.org/scraping-html-tables-and-downloading-files-with-r/)

Updates:

## 23\) From deep learning to `clean_names()`, resources from Data Journalism in R

23-from-deep-learning-to-clean\_names-resources-from-data-journalism-in-r

Storybench post: [From deep learning to clean\_names(), resources from
Data Journalism in
R](http://www.storybench.org/from-deep-learning-to-clean_names-resources-from-data-journalism-in-r/)

Updates:

## 24\) Why Sharon Machlis wrote a book on R for journalists

24-why-sharon-machlis-wrote-a-book-on-r-for-journalists

Storybench post: [Why Sharon Machlis wrote a book on R for
journalists](http://www.storybench.org/why-sharon-machlis-wrote-a-book-on-r-for-journalists/)

Updates:

## 25\) Pivoting data from columns to rows (and back\!) in the tidyverse

25-pivoting-data-from-columns-to-rows-in-the-tidyverse

Storybench post: [Pivoting data from columns to rows (and back\!) in the
tidyverse](http://www.storybench.org/pivoting-data-from-columns-to-rows-and-back-in-the-tidyverse/)

Updates:

## 26\) Exploring bike rental behavior using R

Slug: 26-exploring-bike-rental-behavior-using-r

Storybench post: [Exploring bike rental behavior using
R](http://www.storybench.org/exploring-bike-rental-behavior-using-r/)

Updates:

## 27\) How to model with gradient boosting machine in R

27-how-to-model-with-gradient-boosting-machine-in-r

Storybench post: [How to model with gradient boosting machine in
R](http://www.storybench.org/tidytuesday-bike-rentals-part-2-modeling-with-gradient-boosting-machine/)

Updates:

## 28\) How to access APIs in R

Slug: 28-how-to-access-apis-in-r

Storybench post: [How to access APIs in
R](http://www.storybench.org/how-to-access-apis-in-r/)

Updates:

## 29\) How to build a bubble chart of individuals mentioned in the Mueller report

Slug:
29-how-to-build-a-bubble-chart-of-individuals-mentioned-in-the-mueller-report

Storybench post: [How to build a bubble chart of individuals mentioned
in the Mueller
report](http://www.storybench.org/how-to-build-a-bubble-chart-of-individuals-mentioned-in-the-mueller-report/)

Updates:

## 30\) How to build a website with Blogdown in R

Slug: 30-how-to-build-a-website-with-blogdown-in-r

Storybench post: [How to build a website with Blogdown in
R](http://www.storybench.org/how-to-build-a-website-with-blogdown-in-r/)

Updates:

## 31\) Exploring Chicago rideshare data in R

Slug: 31-exploring-chicago-rideshare-data-in-r

Storybench post: [Exploring Chicago rideshare data in
R](http://www.storybench.org/exploring-chicago-rideshare-data/)

Updates:
