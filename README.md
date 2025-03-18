# SPHERE-PPL Forecasting Contest Example - Mpox

> [!note]
> This is an example contest repo for the SPHERE-PPL forecasting events. It will have all of the information sections you will find in active contests and will mostly follow the same rules/timelines. We have included example analysis and outputs to help guide new entrants.

## Introduction [^readme-1]

[^readme-1]: Adapted from WHO Mpox Dashboard (<https://worldhealthorg.shinyapps.io/mpx_global/>)

Mpox is an infectious disease that can cause a painful rash, enlarged lymph nodes, fever, headache, muscle ache, back pain and low energy. Most people fully recover, but some get very sick. 

Mpox is caused by the monkeypox virus (MPXV). It is an enveloped double-stranded DNA virus of the *Orthopoxvirus* genus in the *Poxviridae* family, which includes variola, cowpox, vaccinia and other viruses. There are two distinct clades of the virus: clade I (with subclades Ia and Ib) and clade II (with subclades IIa and IIb).

A global outbreak of clade IIb began in 2022 and continues to this day, including in some African countries. There are also growing outbreaks of clades Ia and Ib affecting the Democratic Republic of the Congo and other countries in Africa. As of August 2024, clade Ib has also been detected beyond Africa.

The natural reservoir of the virus is unknown, but various small mammals such as squirrels and monkeys are susceptible.

The dataset included in this forecasting contest covers the period from Jan 2022 to July 2024.

## Forecasting Outputs

This contest has its own repository with pre-prepared data (found in the data folder) and a template report (mpox_report.qmd) which showcases how to load the data, perform analyses and then export results into the correct format. There is also be a folder for any additional scripts that are required.

For this example contest, we are looking to forecast monthly regional case numbers for the 6 WHO regions (African, Eastern Mediterranean, European, Region of the Americas, South-East Asia, Western Pacific) for the remainder of 2024 (August-December).

## Joining the contest & Getting Started

In order to join the contest, you will need to fork or download the repo.

To fork the repo, simply press the "fork" button, which can be found at the top of this github page. A step-by-step guide can be found [here](https://scribehow.com/shared/Forking_a_SPHERE-PPL_Forecasting_Contest_Repository_on_GitHub__o_bLCyQlTsO0o5YCmGsk8Q).

To download the data without a github account, click the code box dropdown and download a zip of the data directly to your computer.

![Fork or Download](https://github.com/SPHERE-PPL/forecasting-contest-template/blob/main/contest_media/fork_button.png)

## Rules

-   Any coding languages are allowed but all analyses must be reproducible by the panel.
-   All entries must be loaded into a public Github repo.
-   All entries must follow the submission formats outlined below.
-   All entries must include a max 1000 word report to accompany the forecast analyses. This can be as a separate PDF/hmtl or incorporated into a quarto/jupyter notebook.

## How to Win!

Awards will be given across two categories:

1. The team with the closest forecast, as measured by Root Mean Squared Error.  

2. The team with the most interesting report.

The winners will be selected by the SPHERE-PPL Team and will be invited to present their forecasts at the next Annual Meeting, with travel covered by the project.

## How to Submit

If you forked the repo, congratulations, you have already entered the contest. We will run the [Forecast AggregatoR](https://github.com/SPHERE-PPL/Forecast-AggregatoR) the day following the close of the contest and your repo will be collated with the entries.

If you did not fork the repo, please send an email to [contest\@sphere-ppl.org](mailto:contest@sphere-ppl.org) with a link to your public github repo where your forecast and report are stored. These will then be collated with the other entries.

## Connect with the Community

You can join our Zulip [here](https://sphereppl.zulipchat.com/join/olwtpi7g3wbyh5mxv4uwipaw/) and check out our events page to see the next online catch-up.

## License

![CC-BYNCSA-4](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)

Unless otherwise noted, the content in this repository is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-nc-sa/4.0/).

For the data sets in the *data/* folder, please see [*data/README.md*](data/README.md) for the applicable copyrights and licenses.
