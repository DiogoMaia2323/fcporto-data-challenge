⚽ FC Porto Data Challenge
Context-Aware Football Analytics using StatsBomb Event & 360 Data
📖 Project Overview

This project was developed for the FC Porto Data Challenge with the objective of transforming raw football event data into a contextual decision-support system capable of evaluating player actions beyond traditional statistics.

Using StatsBomb Event Data and StatsBomb 360 Freeze Frame Data, a complete analytical pipeline was built, covering:

Data extraction and validation
ETL processes
Star schema data modelling
Advanced feature engineering
Spatial football analytics
Context-aware player evaluation
Interactive Power BI dashboard development

The final solution combines event actions with player positioning data to quantify the difficulty and quality of football decisions in real match situations.

🎯 Business Objective

Traditional football metrics often measure what happened.

This project aims to understand why actions happened, by incorporating the surrounding context of every decision:

How much pressure was the player under?
How many passing options were available?
How much space was available?
How difficult was the decision itself?

The result is a richer and more realistic evaluation of player performance.

🏗️ Data Architecture
Data Sources
StatsBomb Event Data
StatsBomb 360 Freeze Frame Data
ETL Pipeline
1️⃣ Data Exploration & Extraction

The first notebook focuses on:

Match selection
Event extraction
Freeze-frame extraction
Data validation
Data preparation
2️⃣ Feature Engineering

The second notebook enriches events with contextual spatial information, generating advanced football intelligence metrics.

🗄️ Analytical Data Model

A Star Schema was designed to support analytical queries and dashboard performance.

Dimensions
DIM_MATCHES
DIM_PLAYERS
Fact Tables
FCT_EVENTS
FCT_FRAMES
FCT_PLAYER_STATS
FCT_TEAM_STATS
Data Model

📸 Insert Data Model Screenshot Here

![Data Model](images/data-model.png)
📊 Power BI Dashboard

The dashboard was developed around seven analytical perspectives.

🏟️ Match Information

Provides complete match context:

Starting lineups
Formations
Match events
xThreat momentum evolution
Team structures

📸 Insert Screenshot Here

![Match Overview](images/match-overview.png)
🔵 Team Analysis

Team-level comparison using both traditional and contextual metrics.

Includes:
Pass Networks
xG Comparison
Passing Success
Total Actions
Receptions
Spatial Difficulty Analysis
Novel Team Metrics
Receiver Pressure Difficulty
Passing Options Difficulty
Space Availability Difficulty
Decision Difficulty

📸 Insert Screenshot Here

![Team Analysis](images/team-analysis.png)
👤 Player Analysis

Individual player performance analysis.

Each player can be evaluated through:

Event timelines
Heatmaps
Passing maps
Reception maps
Contextual metric evolution
Example

Lionel Messi registered:

82% passing accuracy
74 receptions
Strong involvement in advanced areas
Consistently high contextual difficulty scores

📸 Insert Screenshot Here

![Player Analysis](images/player-analysis.png)
⚖️ Player Comparison

Direct comparison between players under the same contextual framework.

Example comparison:

Lionel Messi vs Kylian Mbappé

Comparing:

Pressure exposure
Passing difficulty
Space availability
Decision complexity
Traditional performance indicators

📸 Insert Screenshot Here

![Player Comparison](images/player-comparison.png)
📍 Spatial Context Analysis

One of the most important components of the project.

Each event can be explored alongside its freeze-frame context.

Metrics include:

Distance to nearest opponent
Nearby opponents (<5m)
Nearby opponents (<10m)
Pressure score
Space score
Passing score
Decision score

This allows every action to be evaluated according to its true difficulty.

📸 Insert Screenshot Here

![Spatial Context](images/spatial-context.png)
🧠 Decision Intelligence

A custom analytical layer designed to evaluate decision complexity.

Actions are mapped according to:

Receiver pressure
Available passing options
Space availability
Decision difficulty

This creates a contextual framework capable of distinguishing:

Easy actions
High-pressure situations
Limited-support decisions
High-risk executions

📸 Insert Screenshot Here

![Decision Intelligence](images/decision-intelligence.png)
🏆 Final Insights

The dashboard identifies players who stand out in specific contextual dimensions.

Most Received Pressure

🥇 Kolo Muani

Consistently operated under the highest pressure levels during possession phases.

Most Difficult Decisions

🥇 Kolo Muani

Frequently executed actions under constrained spatial and tactical conditions.

Most Complex Space Management

🥇 Olivier Giroud

Operated in situations with reduced spatial availability.

Highest Passing Difficulty

🥇 Marcos Acuña

Faced the most demanding passing environments throughout the match.

Pressure Resistant Player

🥇 Adrien Rabiot

Maintained high execution efficiency despite elevated pressure levels.

Best Decision Maker

🥇 Lionel Messi

Demonstrated the highest success rate when operating in difficult contextual scenarios.

Hidden Playmaker

🥇 Julián Álvarez

Created value despite limited support structures and constrained environments.

Context Efficiency Leader

🥇 Lionel Messi

Combined high involvement with strong execution quality under complex conditions.

📸 Insert Screenshot Here

![Final Insights](images/final-insights.png)
🔍 Key Findings
🧠 Context Matters More Than Raw Actions

Traditional event counts alone are insufficient to evaluate player performance accurately.

Adding spatial context significantly improves action interpretation.

🎯 Pressure Changes Decision Behaviour

Players operating under high pressure tend to reduce available passing choices and face more difficult decision-making scenarios.

⚽ Elite Players Thrive Under Contextual Difficulty

The analysis suggests that players such as Lionel Messi maintain high efficiency despite operating in demanding tactical environments.

📊 Football Performance Is Multi-Dimensional

Player evaluation should combine:

Technical execution
Spatial awareness
Pressure resistance
Decision quality
Team support structure

rather than relying exclusively on traditional football statistics.

🛠️ Technologies
Python
Pandas
NumPy
StatsBombPy
Jupyter Notebook
Power BI
DAX
👨‍💻 Author

Diogo Maia

FC Porto Data Challenge — Football Analytics & Data Science Project
