# Supplementary Material

## Detailed prompts, data, and codes within individual experiment

Each folder (except for the `Fit Estimation/` folder, see `README.md` in `Fit Estimation/` folder for its contents) represents the respective agent experiment of the source paper.

### Contents in each folder

+ `.json` --- agent response data after post processing
+ `analysis_code.Rmd` --- R markdown for data analysis
+ `analysis_code.html` --- html knitted R markdown
+ `prompt_resource.md` --- prompts and resource
+ `experiment_code.ipynb` --- experiment code

### Experiment name (in alphabetical order)

| Folder Path                      | Paper Title (with link)                                                                                           | Authors   | Venue     | OSF Repo Link |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------|-----------|-----------|----------------|
| `Fit Estimation/`               | [Visual Model Fit Estimation in Scatterplots: Influence of Amount and Decentering of Noise](https://doi.org/10.1109/TVCG.2021.3051853)                     |Daniel Reimann , Christine Blech , Nilam Ram, and Robert Gaschler           |IEEE TVCG           |<https://osf.io/fbsh7/>                |
| `Imputation for Uncertainty/`   | [Evaluating the Use of Uncertainty Visualisations for Imputations of Data Missing At Random in Scatterplots](https://doi.org/10.1109/TVCG.2022.3209348)   |Abhraneel Sarma, Shunan Guo, Jane Hoffswell, Ryan Rossi, Fan Du, Eunyee Koh, and Matthew Kay           |IEEE TVCG           |<https://osf.io/q4y5r/>                |
| `Magnitude Judgement/`          | [Magnitude Judgements Are Influenced by the Relative Positions of Data Points Within Axis Limits](https://doi.org/10.1109/TVCG.2024.3364069)              |Duncan Bradley, Gabriel Strain, Caroline Jay, and Andrew J. Stewart           |IEEE TVCG           |<https://osf.io/3epm2/>                |
| `Texture/`                      | [Design Characterization for Black-and-White Textures in Visualization](https://doi.org/10.1109/TVCG.2023.3326941)                                        |Tingying He , Yuanyang Zhong , Petra Isenberg , Tobias Isenberg           |IEEE TVCG           |<https://osf.io/r4z2p>                |
| `Time Series/`                  | [Investigating Time Series Visualisations to Improve the User Experience](https://dl.acm.org/doi/10.1145/2858036.2858300)                                      |Muhammad Adnan, Mike Just, Lynne Baillie           |ACM CHI           |-                |
| `Timeline/`                     | [Evaluating the Effect of Timeline Shape on Visualization Task Performance](https://dl.acm.org/doi/10.1145/3313831.3376237)                                    |Sara Di Bartolomeo , Aditeya Pandey , Aristotelis Leventidis , David Saffo , Uzma Haque Syeda , Elin Carstensdottir , Magy Seif El-Nasr , Michelle A. Borkin , Cody Dunne           |ACM CHI           |<https://osf.io/qr5yu/>                |

## Other supplemental materials

+ `prompt_summary.md` --- a structured summary of all the prompts used in our experiments
+ `expert_confidence_coding.md` --- a recording of confidence codings by five external experts

## Run our codes and replicate our experiments

### For R code
Steps for new users to install R, RStudio and necessary packages used in our code to reproduce the statistical analyses.
Newest version of the installations is always OK due to the simplicity of the analyses code.

Step 1: Install R
   - Visit the [CRAN R Project website](https://cran.r-project.org/).
   - Choose your operating system and then choose the "base" subdirectory.
   - download R
   - Run the downloaded installer and follow the on-screen instructions to complete the installation.

Step 2: Install RStudio
   - Visit the [RStudio website](https://www.rstudio.com/).
   - Navigate to the "Products" section and select "RStudio".
   - Click on "Download RStudio" and choose the free RStudio Desktop version.
   - Download the installer for your operating system.
   - Run the downloaded installer and follow the on-screen instructions to complete the installation.
Note: When you install RStudio after installing R, RStudio should automatically detect the R installation and associate itself with it.

Step 3: Install Necessary Packages
   - You can install dependencies in either of the following two ways:
     1) In the RStudio console, run the following commands to install the necessary packages, all packages used in our code is listed below:
       ```r
       install.packages("rmarkdown")
       install.packages("markdown")
       install.packages("jsonlite")
       install.packages("dplyr")
       install.packages("ggplot2")
       install.packages("ggpattern")
       install.packages("boot")
       install.packages("tidyr")
       install.packages("patchwork")
       install.packages("knitr")
       install.packages("kableExtra")
       ```
     2) Or you can follow the message on the top and click to install missing packages in this Rmarkdown file when you open Rmarkdown files in Rstudio.

Step 4: Running RMarkdown Chunks
   - Open ".Rmd" files with Rstudio.
   - Similar to using python jupyter notebook, run the chunks by clicking the "run current chunk" button on the topright of each chunk.


## For Python code
Due to differences in experimental methods and nature, the code organization of different experiments is slightly different. Please refer to the README.md in each subfolder and the text description in the .ipynb file.