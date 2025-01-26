
# EDGAR GHG Emissions report exercise

This repository contains the **R Markdown** file used to generate a
detailed PDF report on greenhouse gases (GHG) emissions. The report
provides insights into global, regional, and country-level GHG trends,
including income group comparisons and visualizations.

## Features of the Report

-   Year-on-year GHG emission trends for EU27, Euro Area, and global
    totals.
-   Per capita GHG emissions across income groups.
-   Contributions of individual countries and continents to global GHG
    emissions.

## Getting Started

### Prerequisites

To replicate the analysis and render the report, you will need:

-   **RStudio**

    -   **R** (version 4.0 or higher)

-    The following R packages:

    -   `rmarkdown`

    -   `ggplot2`

    -   `dplyr`

    -   `tidyr`

-   `treemapify`

-   `renv`

### Instructions

1.  **Clone the repository**: \
    `bash     git clone git@github.com:a-dacko/EDGAR-GHG-Emissions-report.git     cd EDGAR-GHG-Emissions-report`

2.  **Restore the R environment**: The project uses `renv` to manage
     -   `ggplot2`
     -   `dplyr`
     -   `tidyr`
     -   `treemapify`
     -    `renv`
     -    `rmarkdown`


### Instructions

1.  **Clone the repository**: 
    ```{bash}
    git clone git@github.com:a-dacko/EDGAR-GHG-Emissions-report.git
    cd EDGAR-GHG-Emissions-report
    ```
3.  **Restore the R environment**: The project uses `renv` to manage
    dependencies. Run the following command in your R console to install
    the required packages:

    ```{r}
    renv::restore()
    ```

4.  **Render the report**:\
    Open the `EDGAR-GHG-Emissions-report.Rmd` file in RStudio and click
    the **Knit** button to generate the PDF report. Alternatively, you
    can use the following R code:

    ```{r}
    rmarkdown::render("EDGAR-GHG-Emissions-report.Rmd")
    ```

## Output

After rendering, the PDF report will be saved in the same directory as
the R Markdown file.
