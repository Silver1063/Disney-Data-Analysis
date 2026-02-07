<img width="1000" height="419" alt="image" src="https://github.com/user-attachments/assets/e0bc6d4a-cf22-41e1-a235-fde02b724a9e" />
(Disney please don't sue me 🥲)

To view results select one of the three options above, pdf provided for ease of viewing, rmd for local inspection.\
## The pdf reader on github is a bit challenging, feel free to download it and read it wherever pdfs like to find you 😤
<img width="775" height="215" alt="image" src="https://github.com/user-attachments/assets/d39286af-65be-4eae-9240-817f636abe63" />

## Project Overview
This project focuses on Analyzing Disney Movie Box Office Performance by examining historical revenue trends spanning nearly 80 years. The goal is to identify the key drivers of commercial success such as genre popularity and MPAA ratings and to understand how the financial "value" of a Disney film has evolved from the hand drawn classics of the 1930s to the modern day blockbuster era.

The analysis utilizes a comprehensive dataset of 579 Disney movies released between 1937 and 2016. By comparing raw total gross against inflation adjusted figures, this project seeks to uncover whether the "Golden Age" of animation truly holds the crown for profitability or if modern franchise driven cinema has set a new standard for the studio.

## Key Features
- Data Cleaning & Feature Engineering
- Inflation-Adjusted Analysis: Stripping away the "Inflation Illusion" by comparing nominal gross against inflation-adjusted figures to identify the true commercial impact of early classics like Snow White.
- Exploratory Data Analysis (EDA)
  - Trend Visualization: Tracking the "rise and fall" production cycles and the shift from Comedy led growth to Adventure led dominance.
  - Seasonal Heatmaps: Identifying "Dump Months" versus peak family vacation windows to reveal Disney’s release calendar strategy.
- Statistical Modeling & Inference
  - ANOVA Testing: Proving the statistically significant impact of MPAA ratings on box office yields.
  - Correlation Analysis: Discovering a "Dilution Effect" (r = -0.30) where high release volume negatively correlates with average per film gross.
  - Predictive Linear Modeling: Quantifying the value of specific genre/rating combinations, identifying the G-rated Musical as Disney's "North Star" for revenue.

# Results
The project identifies a clear trade off between quantity and quality, suggesting a "Boutique Strategy" is more efficient for Disney than market saturation. The findings culminate in a predictive tier list of performance, confirming that while Adventure films provide modern stability, Musicals remain the studio's highest value competitive advantage, adding an estimated $366.9M in value over standard action titles.

# Tools Used
- Language: R
- Libraries: tidyverse, ggplot2, patchwork, scales, collapse, ggeffects, lubridate
- Environment: RStudio / R Markdown
