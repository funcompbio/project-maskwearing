# Project mask wearing - FCB 2020

## Summary

In this project you should analyse data to attempt answering the following question:

> Do political views influence wearing a mask in public to minimize transmission of COVID19?

## Data

You should use the following two datasets:

1. A recent survey conducted in the USA by the New York Times on wearing a mask in public
and available [here](https://github.com/nytimes/covid-19-data/tree/master/mask-use). The
dataset is in a CSV file called `mask-use-by-county.csv`.

2. Results of the recent 2020 USA general election presidential results by county and
available [here](https://github.com/tonmcg/US_County_Level_Election_Results_08-20). The
dataset is in a CSV file called `2020_US_County_Level_Presidential_Results.csv`.

## Deliverables

The GitHub repo for this project should contain, at least, the following files:

  * `index.Rmd`: R Markdown script with the R code doing the analysis of the data
    and the corresponding text explaining those analysis steps.
  * `index.html`: Resulting HTML output from processing (_knitting_) the file
    `index.Rmd`.
  * The CSV files employed during the analysis.
  * This `README.md` file.

The analysis of the data described in the HTML file should contain the following
sections:

  * **Abstract:** Summary of the question and the findings (max. 200 words).
  * **Introduction:** Description of the question and the data employed to answer it.
    Description of any steps taken, if any, previous to this R Markdown document,
    to prepare the data that is being analyzed.
  * **Results:** R code intertwined with text, descriping the analysis steps and the
    display items with the results, which should consist, **at least**, of one table
    and one plot.
  * **Conclusions:** summary of the findings, limitations of the study, ways in which
    this type of study could be improved in the future.
  * **References:** bibliographic references.

## Methodology

The analysis of the data should be carried out at least using R, but you can also
use shell or Python scripts to transform or prepare the data for the analysis with
R. If those prior steps using shell or Python scripts are included, they should be
described in the introduction section of the R Markdown document and, ideally,
made readily reproducible using a Makefile.

## Evaluation rubric

The rubric to evaluate this project consists of the following items:

* Have all members of the group made a sizeable number of commits to the GitHub repo?

* Does the GitHub repo contain at least the analysed CSV files along with the
  `index.Rmd` file and the resulting `index.html`?

* Does the R Markdown file `index.Rmd` run the analysis without errors and
  generates the expected `index.html` file?

* Does the analysis described in the resulting `index.html` file conform to
  the requested sectioning.

* Does the introduction explain clearly what is the question addressed, the
  data employed and the number of observations and variables involved?

* Do the plots show some meaningful summary of the data? Are axes in plots
  labeled in plain language and large enough to read?

* Does the GitHub repo include a _Makefile_ that automatizes the entire analysis
  pipeline and generation of the final report in the `index.html` file?
