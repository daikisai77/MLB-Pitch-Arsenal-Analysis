# Overview
This project analyzes Major League Baseball (MLB) pitch arsenals to identify the most effective pitch combinations using advanced statistics and R-based modeling. By combining velocity, spin rate, and sequencing data, I evaluated how different pitch mixes (pairs, trios, and five-pitch arsenals) impact run value and overall effectiveness.

# Data Pipeline
## Data Sources
- MLB Statcast data (2023 season).
- Pitch-arsenal-stats dataset for velocity, spin rate, and pitch usage.
## Preprocessing in R
- Cleaned and merged pitch-level data from multiple sources.
- Created new features (velocity differences, spin rate gaps, release point variability).
- Aggregated data by pitcher and pitch combinations.

## Analysis
- Calculated average run values by pitch type and mix.
- Evaluated sequencing effectiveness (e.g., fastball → slider → changeup).
- Compared arsenals with velocity and spin differentials.

## Visualization
- Heatmaps of pitch usage and effectiveness.
- Boxplots of run value distributions.
- Combination charts showing effectiveness of 2-, 3-, and 5-pitch mixes.

# Tools & Libraries
- **RStudio** (dplyr, ggplot2, tidyr, caret)
- **MLB Statcast data** via baseballr package
- **Data visualization** with ggplot2

# Results & Insights
- Velocity gaps between fastballs and off-speed pitches strongly correlate with run value reductions.
- Spin rate differentials enhance the deception of secondary pitches.
- Five-pitch mixes that include both a high-spin fastball and a changeup outperform limited arsenals in expected run value.
- Sequencing analysis suggests pitchers gain measurable advantage by alternating velocity ranges rather than repeating similar speeds.

# Author
## Daiki Sai
daikisai77@gmail.com | https://www.linkedin.com/in/daiki-sai/

