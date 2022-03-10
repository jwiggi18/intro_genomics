# intro_genomics

Undergraduate intro genomics course

Lessons are in development and will use:

## Data 

[Broad Institute GDAC Firehose](http://firebrowse.org/)

## Language 

[R](https://www.r-project.org/about.html) - primarily [BioConductor](https://www.bioconductor.org/)

## Analysis Platform 

[CyVerse](https://cyverse.org/) and its Discovery Environment data science workbench: [https://de.cyverse.org/de](https://de.cyverse.org/de)

[Course Enrollment](https://user.cyverse.org/workshops/91) -- register and get faster access to CyVerse's interactive workbench.

Quick Launch (must log into CyVerse): <a href="https://de.cyverse.org/apps/de/3548f43a-bed1-11e9-af16-008cfa5ae621/launch" target="_blank"><img src="https://img.shields.io/badge/Verse-latest-blue?style=plastic&logo=rstudio"></a>

[CyVerse Learning Center](https://learning.cyverse.org) -- Guides and Manuals for using CyVerse.

---
**NOTE**

*It is strongly recommended that you use an institutional email address (`.edu`, `.org`, or `.gov`) if possible. This will speed up the approval process for access to certain CyVerse platforms. Also, please add your [ORCID](https://orcid.org) to your CyVerse User Profile. If you don't have an ORCID get one today!*

*Check your email for an account confirmation link and follow the confirmation instructions.*

*Once you have confirmed your email address, you can start using your CyVerse account right away!*

---

# Steps

1. Create a [CyVerse account](https://user.cyverse.org) using the [Course Enrollment Form](https://user.cyverse.org/workshops/91) and log into the [Discovery Environment](https://de.cyverse.org)

2. Launch an [RStudio Verse Latest App] - leave the default fields blank and go to Step 4: Launch Analysis. 

The App should launch within one minute. It will be available under the Analyses section (See left side table of content 'Analyses'). Click on 'Rocker RStudio Verse' to open a new browser tab with the running Application.

3. Create a new R Project using `git` version control

4. Clone this repository by selecting its URL `https://github.com/jwiggi18/intro_genomics`

5. Leave the directory name as `intro_genomics`

6. Set the subdirectory working path to the home folder `/home/rstudio/` 

7. Load the .Rproj file and open the .Rmd, select 'Run All' to install the BioConducter `BiocManager` and `librarian` packages.

**IMPORTANT** -- when you are done using the RStudio, please go to 'Analyses' and click the three dot icon on the right side and 'Terminate' the analyses.
