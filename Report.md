# Football Data Analysis and Visualization — Premier League 2024/25 Season

## Project Overview
This project analyzes and visualizes detailed statistics from the Premier League 2024/25 season. Using match-level data, team statistics, and referee card data, the analysis provides insights into team performance, disciplinary records, and match outcomes, supported by dynamic visualizations.

## Data Sources
- Match results and statistics, including goals, fouls, cards, and shots.
- Aggregated team-level statistics such as league points, goals for/against, fouls committed and suffered.
- Referee card issuance records to interpret disciplinary tendencies.
- The raw data was cleaned, structured, and saved in CSV and pickle formats to enable modular analysis and efficient visualization.

## Analysis Highlights

### Team Performance Metrics
- Computed cumulative points progression for each team across match weeks to track performance trends.
- Calculated goal statistics: goals scored (GF), goals conceded (GA), and goal difference (GD).
- Summarized fouls committed and fouls suffered to assess teams' playing style and physicality.

### Disciplinary Analysis
- Analyzed yellow and red cards issued by referees, identifying the strictest and most lenient referees.
- Investigated distribution of fouls committed and fouls suffered across teams to recognize aggressive or disciplined play.

### Visualization Approach
- Interactive bar charts compare team goals scored vs conceded.
- Line graphs trace points accumulation over the season, highlighting momentum shifts.
- Radar charts compare teams across multiple metrics simultaneously for multidimensional insights.
- Box plots visualize distribution and variability in fouls committed and suffered.
- All visualizations use Plotly for interactive exploration and detailed hover information.

## Project Structure and Reproducibility
- Cleaned datasets and detailed statistics are stored as CSV and pickle files in the `data/` folder for modular reuse.
- Analysis and visualization code is organized into separate Jupyter notebooks for clarity and scalability.
- Utilities to load, process, and plot data are included to facilitate extension or modification.

## Getting Started
1. Clone the repository.
2. Ensure dependencies (`pandas`, `numpy`, `plotly`, `kaleido`) are installed.
3. Run the notebooks sequentially:
   - Data cleaning and preparation (`file_cleaning.ipynb`).
   - Data exploration and statistics generation (`data_exploration.ipynb`).
   - Analysis and visualization (`data_analysis_vizualization.ipynb`).
4. Generate interactive plots and export static images for reports or presentations.

## Conclusions
The multi-faceted statistical approach provides deep insights into team dynamics, referee behavior, and match outcomes, enabling richer understanding of the season beyond just points tables. Interactive plots empower users to explore specific teams, referees, or metrics in detail.

## Future Work
- Incorporate expected goals (xG) and advanced player-level stats for deeper tactical analysis.
- Add automatic report generation with narrative summaries based on data findings.
- Create a web dashboard using Dash or Streamlit for broader accessibility.
