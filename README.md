# R-Ladies SB x Central Coast Python Collab - Data Wrangling and Viz 

**NOTE:** This README is currently under construction

## Meetup Details

- **Event Description:** Mark you calendars for a first-of-its-kind [R-Ladies SB](https://www.meetup.com/rladies-santa-barbara/) x [Central Coast Python](https://www.meetup.com/central-coast-python) introductory workshop on December 15th! This hybrid event with online and in-person attendees will be an opportunity to celebrate two unique communities by coming together and analyzing one dataset. You may choose to follow along on our screens or download the required software and packages to code along on your own machines. If you do not already have R and Python installed, please be sure to do so before the event on December 15th (see **[Software Installation Instructions](https://github.com/samanthacsik/RLadiesSB-RvsPython/blob/main/README.md#software-installation-instructions)** below). We will be available to help troubleshoot any errors the week before (exact date TBD). 

- **Event Date:** December 15, 2021 at 17:30-19:00PT, office hours 1 week before TBD.

- **Event Location:** Zoom link available upon RSVP and optional in-person attendance at National Center for Ecological Analysis & Synthesis (NCEAS) 1021 Anacapa St. Paid parking is available nearby at city lot #8. The first 75min are free to park and then it’s $1.50 per hour after that. Street parking at the crossroads is also an option, especially after 6pm.

- **RSVP:** [R-Ladies SB Meetup Event](link here) (Python allies can RSVP at [Central Coast Python Meetup Event](link here))

## Software Installation Instructions

### Install R & RStudio and the `tidyverse` (expected install/test time: ~10-15 minutes)
1) If you have not yet installed R and/or RStudio (you will need both), follow the steps outlined [here](https://docs.google.com/document/d/1KLYC_GcDLYeczSjJmZ5h4y525XILJbbL6r2-MxGCdtw/edit?usp=sharing)
2) We will be using the [{tidyverse}](https://www.tidyverse.org/) (a collection of packages designed for data science, particularly useful for data wrangling and visualization). If you do not yet have the {tidyverse} installed, run the following line of code in your RStudio Console: `install.packages("tidyverse")`
3) We encourage you to test that your installations are working as expected. Follow [these instructions](https://docs.google.com/document/d/1ItQy91G6QfKaX1-26lracpSbJ52JUie1HZb54LCa9sM/edit?usp=sharing) to ensure a smooth workshop ahead!

### Install Python & Anaconda (expected install/test time: ~10-15 minutes)
1) Install Conda following [these instructions](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html). If you aren't sure whether to choose Miniconda or Anaconda, we would reccommend Miniconda.
2) Run `jupyter notebook` to start coding in the browser.

** Alternatives to Conda **
For R users who are new to Python, we are reccommending Conda above for this Meetup, so that everyone is on the same page. If you would prefer to use pip though, please feel free to explore independently or use [this great repo](https://github.com/L4R5m/sb-python-meetup) from Lars to get started. There are also great online tools like [Colab](https://colab.research.google.com) which you can use to get up and running in a browser.

### Install git/GitHub (expected install time: ~5 minutes)  
1) If you are not already using git/GitHub for version control, we recommend you get set up by following the steps outlined [here](https://docs.google.com/document/d/1AQ4zAYxPHOObq-snnnRtEdwCC8TwIJsTHwpaKyvEyoA/edit?usp=sharing). Doing so will allow you to clone (i.e. copy to your computer) the GitHub repositories containing all the data and scripts that you need to follow along with us (steps for cloning a GitHub repository can be found [below](https://github.com/samanthacsik/RLadiesSB-RvsPython/blob/main/README.md#clone-workshop-repos-to-your-computer)).

## Clone workshop repositories to your computer

## Data

We will be using ugly holiday sweater data crowdsourced from R-Ladies (and friends) in November/December 2020. If you would like to contribute your own ugly holiday sweater info to this dataset, please fill out this [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSd37uWHUgp-Gd5833ECGXdszKLBV6kpdpigT-yIMTXkCwyKXg/viewform)! See a summary of the data attributes here:

* `sweater`: entry number
* `hs_tf`: Do you have a holiday sweater? (Yes/No/NA)
* `sparkly`: is it sparkly? (Yes/No/NA)
* `noise`: does it make noise? (Yes/No/NA)
* `lights`: does it light up? (Yes/No/NA)
* `objects`: does it have anything attached to it? (Yes/No/NA)
* `colors`: What colors does it have? 
* `image_tf`: Does it have an image on it? (Yes/No/NA)
* `image_desc`: User-provided image description

## Objective

We will use both R's [tidyverse](https://www.tidyverse.org/) packages and Python's **XYZ** libraries to demonstrate how you might wrangle the [ulgy sweater data](https://github.com/samanthacsik/RLadiesSB-RvsPython/blob/main/holiday_sweaters_2020_clean.csv) and create this plot: 

![Rplot](https://user-images.githubusercontent.com/43836046/139956835-7af0e1c4-ea85-4266-9821-9dca101b053f.png)

