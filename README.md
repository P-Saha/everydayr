# Everyday R Workshop 1: Quarto and dplyr

Part of the Everyday R Workshop series by EBOSS, which introduces modern R programming tools for real-world data analysis.

This workshop is a step-by-step tutorial on Quarto (the next generation of R Markdown) and the dplyr package (pipes and other useful functions for data manipulation). If you use R and are unfamiliar with the `select()`, `filter()`, and `mutate()` functions, this workshop is for you.

## Before the workshop

Please install:

1. **R**: <https://cran.r-project.org/>
2. **RStudio Desktop**: <https://posit.co/download/rstudio-desktop/>. Quarto comes included with RStudio.

The template installs the tidyverse for you the first time you run it. To save time during the workshop, you can install it beforehand by running this in the RStudio console:

```r
install.packages("tidyverse")
```

## Download the template

Pick any one of these options.

**Option 1: From R (easiest).** Open RStudio and paste this into the console. The file is saved in your current working directory.

```r
download.file("https://raw.githubusercontent.com/P-Saha/everydayr/main/workshop_template.qmd", "workshop_template.qmd")
```

Run `getwd()` to see which folder that is.

**Option 2: Download button.** Click [`workshop_template.qmd`](workshop_template.qmd) above, then click the download icon ("Download raw file") at the top right of the file.

**Option 3: ZIP file.** Click the green **Code** button at the top of this page, then **Download ZIP**, and unzip it.

## Using the template

1. Open `workshop_template.qmd` in RStudio.
2. Run the **Setup** chunk first by clicking the green triangle in its top right corner.
3. Work through the exercises by writing your code in the empty chunks.
4. Click **Render** to turn your work into an HTML page.
