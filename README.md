## Data Science with R

### Disclaimer

This repository is build on the work of [Garrett
Grolemund](https://www.linkedin.com/in/garrett-grolemund-49328411/) from
[posit](https://posit.co). In particular, it reuses an important part of the
material he developed for [tidyverse](https://www.tidyverse.org)-related
workshops, which is available at
<https://github.com/rstudio-education/remaster-the-tidyverse> under the
[Creative Commons BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
copyright.

### Material

The main webpage is at <https://astamm.github.io/data-science-with-r/>.

### Outline

#### Data wrangling with R

The class is organised in 9 parts each of which has its own set of slides and
exercises. The slides are available in the above *Data Wranging - Slides* tab
and the exercises in the above *Data Wranging - Labs* tab. The slides are
written partly with Keynote (exported as PDFs) and partly in Quarto reveajs
slides. The exercises are written in [Quarto](https://quarto.org).

| Part | Title | Slides | Exercises | Suppl. Material |
|------|-------|--------|-----------|-----------------|
| 1    | Introduction | [PDF](01_Introduction/01-Introduction-Slides.pdf) | [Quarto](01_Introduction/01-Introduction-Exercises.qmd) | |
| 2    | Visualize Data | [PDF](02_Visualize/02-Visualize-Slides.pdf) | [Quarto](02_Visualize/02-Visualize-Exercises.qmd) | |
| 3    | Transform Data | [PDF](03_Transform/03-Transform-Slides.pdf) | [Quarto](03_Transform/03-Transform-Exercises.qmd) | [CSV](03_Transform/babynames.csv) |
| 4    | Model Data | [PDF](04_Model/04-Model-Slides.pdf) | [Quarto](04_Model/04-Model-Exercises.qmd) | [ZIP](04_Model/04-Model-Data.zip) |
| 5    | Communicate Data | [PDF](05_Report/05-Report-Slides.pdf) | [Quarto](05_Report/05-Report-Exercises.qmd) | [Quarto](05_Report/05-Report-Parameters.qmd) |
| 6    | Tidy Data | [PDF](06_Tidy/06-Tidy-Slides.pdf) | [Quarto](06_Tidy/06-Tidy-Exercises.qmd) | |
| 7    | Join Data | [PDF](07_Join/07-Join-Slides.pdf) | [Quarto](07_Join/07-Join-Exercises.qmd) | |
| 8    | Manipulate Data Types | [PDF](08_Types/08-Types-Slides.pdf) | [Quarto](08_Types/08-Types-Exercises.qmd) | |
| 9    | Manipulate Lists | [PDF](slides/09-manipulate-lists.pdf) | [Quarto](labs/09-manipulate-lists.Rmd) | |

#### Exploratory Data Analysis with R

The class is organised in 4 parts each of which has its own set of slides and
exercises. The slides are available in the above *Exploratory Data Analysis -
Slides* tab and the exercises in the the above *Exploratory Data Analysis -
Labs* tab. The slides are written in Quarto *revealjs* slides. The exercises are
written in [Quarto](https://quarto.org).

| Part | Title | Slides | Exercises | Suppl. Material |
|------|-------|--------|-----------|-----------------|
| 1    | Hypothesis Testing | [Quarto](10_Hypothesis_Testing/10-Hypothesis-Testing-Slides.qmd) | [Quarto](10_Hypothesis_Testing/10-Hypothesis-Testing-Exercises.qmd) | |
| 2    | Linear Regression | [Quarto](11_Linear_Modeling/11-Linear-Modeling-Slides.qmd) | [Quarto](11_Linear_Modeling/11-Linear-Modeling-Exercises.qmd) | [ZIP](11_Linear_Modeling/11-Linear-Modeling-Data.zip) |
| 3    | Principal Component Analysis | [RMarkdown](12_PCA/12-PCA-Slides.Rmd) | [Quarto](12_PCA/12-PCA-Exercises.qmd) | [ZIP](12_PCA/12-PCA-Data.zip) |
| 4    | Clustering | [Quarto](13_Clustering/13-Clustering-Slides.qmd) | [Quarto](13_Clustering/13-Clustering-Exercises.qmd) | |

### Requirements

- R: <https://www.r-project.org>
- RStudio: <https://posit.co/download/rstudio-desktop/>
- Quarto: <https://quarto.org/docs/get-started/>
- Tidyverse: <https://www.tidyverse.org>
- Specific R packages by theme: 

    - Data sets:
        
        - [{babynames}](https://hadley.github.io/babynames/): a data set of frequency of baby names in the US from 1880 to 2017.
    
    - Data visualization:
        
        - [{ggplot2}](https://ggplot2.tidyverse.org): a package that implements the grammar of graphics.
        - [{plotly}](https://plotly.com/r/): an interactive plotting library.
        - [{gt}](https://gt.rstudio.com/index.html)
    
    - Model summaries:
        
        - [{broom}](https://broom.tidymodels.org): a package that provides tidy summaries of model outputs.
        - [{modelr}](https://modelr.tidyverse.org): a package that provides functions for modelling within the tidyverse.
        - [{jtools}](https://jtools.jacob-long.com): a package that provides functions for summarizing and visualizing model outputs and main effects.
        - [{interactions}](https://interactions.jacob-long.com): a package that provides functions for visualizing the effect of interactions in regression models.
      
    - PCA:
    
        - [{FactoMineR}](http://factominer.free.fr): a package that provides ready-to-use implementations of standard statistical methods for data analysis.
        - [{factoextra}](https://rpkgs.datanovia.com/factoextra/): a package that provides functions for extracting and visualizing the results of multivariate data analyses.
        - [{corrplot}](https://cran.r-project.org/package=corrplot): a package that provides functions for visualizing correlation matrices.
        - [{viridis}](https://sjmgarnier.github.io/viridis/): a package that provides color palettes that are perceptually uniform in both color and black-and-white.
        - [{huxtable}](https://hughjonesd.github.io/huxtable/): a package that provides functions for creating tables in HTML documents.
