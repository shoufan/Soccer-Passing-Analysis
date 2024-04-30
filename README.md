# Soccer Passing Network Analysis Project

## Introduction

Welcome to the Football Passing Network Analysis Project! This project delves into the intricate world of football (soccer) by analyzing passing networks within a team during English Premier League (EPL) matches. By dissecting players' passing patterns and interactions, we aim to gain insights into team strategies, player roles, and the dynamics of football matches.

## Project Goals

The primary objective of this project is to construct and analyze passing networks to:

- Understand the passing characteristics of different playing positions.
- Evaluate the impact of playing formations on passing networks.
- Uncover patterns and trends in passing behavior over time during a match.
- Enhance our understanding of team dynamics and strategic decision-making in football.

## Key Components

### Data Collection
We collect passing-index data from assigned EPL matches and organize it into pass matrices for each 10-minute interval. This data includes pass interceptions, clinical passes, and player interactions.

### Data Analysis
Using Python, we compute various performance measures such as Closeness, Betweenness, PageRank, and Clustering Coefficients for each time interval. These metrics provide insights into players' performance and the overall passing network dynamics.

### Project Report
Each group will prepare a comprehensive report detailing the project methodology, findings, and analyses. The report will include graphical representations of passing networks, centrality measures, clustering effects, and comparative analyses between teams.

## Codebase Overview

The provided Python code contains functions for:
- Constructing passing networks based on passing-index data.
- Analyzing passing network metrics such as centrality measures and clustering coefficients.
- Interception functions to analyze intercepted passes and defensive strategies.

## Getting Started

To get started with this project, follow these steps:
1. Clone the repository to your local machine.
2. Install the required dependencies (NumPy, pandas, NetworkX) using pip.
3. Run the provided Python scripts to analyze passing networks and generate insights.

## License

This project is licensed under the MIT License.
