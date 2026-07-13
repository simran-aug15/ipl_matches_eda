# 🏏 IPL Matches - Exploratory Data Analysis

An exploratory data analysis (EDA) of Indian Premier League (IPL) match data, uncovering trends, patterns, and insights across seasons, teams, players, and venues.

## 📂 Dataset

- **Source:** `ipl_matches.csv`
- **Description:** Match-level data including teams, venues, toss details, results, margins, and season information.
- **Columns:**

| Column | Description |
|---|---|
| `id` | Unique match identifier |
| `city` | City where the match was played |
| `date` | Match date |
| `season` | IPL season/year |
| `matchNumber` | Match number within the season |
| `team1` | First team |
| `team2` | Second team |
| `venue` | Stadium/venue name |
| `tossWinner` | Team that won the toss |
| `tossDecision` | Toss decision (bat/field) |
| `superOver` | Whether the match went to a Super Over (Y/N) |
| `winningTeam` | Team that won the match |
| `wonBy` | Margin type (runs/wickets) |
| `margin` | Margin value (runs or wickets) |
| `method` | Method used if applicable (e.g. D/L method) |
| `playerOfMatch` | Player of the Match award winner |
| `team1Players` | List of players for team1 |
| `team2Players` | List of players for team2 |
| `umpire1` | First on-field umpire |
| `umpire2` | Second on-field umpire |

## 🛠️ Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## 📁 Project Structure

```
ipl-matches-eda/
│
├── data/
│   └── ipl_matches.csv
├── notebooks/
│   └── ipl_eda.ipynb
├── images/
│   └── (saved plots/visualizations)
├── README.md
└── requirements.txt
```

## 🔍 Analysis Performed

- **Data Cleaning:** Handling missing values, correcting inconsistent team/venue names, fixing data types
- **Univariate Analysis:** Distribution of matches per season, venues, cities
- **Team Performance:** Wins by team, home vs away performance
- **Toss Analysis:** Toss decision trends and impact on match outcome
- **Venue Analysis:** Highest/lowest scoring venues, venue-wise win margins
- **Player Analysis:** Most Player of the Match awards, top performers by season
- **Season-wise Trends:** Performance evolution of teams across years

## 📊 Key Insights

> Replace these with your actual findings once analysis is complete.

- Team X has the highest overall win percentage across all seasons.
- Winning the toss and choosing to field has historically resulted in a higher win rate.
- Venue Y tends to favor high-scoring matches, while Venue Z favors bowlers.
- Player A holds the record for most Player of the Match awards.

## 🚀 How to Run

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/ipl-matches-eda.git
   cd ipl-matches-eda
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Launch the notebook
   ```bash
   jupyter notebook notebooks/ipl_eda.ipynb
   ```

## 📈 Sample Visualizations

_Add screenshots of your key plots here, e.g.:_
```
![Team Wins](images/team_wins.png)
![Toss Impact](images/toss_impact.png)
```

## ✅ Future Work

- Merge with ball-by-ball data for deeper insights (strike rates, economy rates)
- Build a predictive model for match outcomes
- Create an interactive dashboard (Streamlit/Power BI)

## 🤝 Contributing

Contributions, issues, and feature requests are welcome. 

