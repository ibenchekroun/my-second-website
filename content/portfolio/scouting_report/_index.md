---
date: "2023-01-01T19:47:09+02:00"
designs:
- Decision-making   
jobDate: January 2023
techs:
- R shiny
thumbnail: decision-maker/Fleabag.jpeg
title: Automated NBA Player Scouting Report
work:
url: "analitty.shinyapps.io/UNdilemma/"
cover:
    #image: /Fleabag.jpeg/ # image path/url
    #imageUrl: https://analitty.shinyapps.io/Scouting_Report/

---

**[LINK TO DASHBOARD: https://analitty.shinyapps.io/Scouting_Report/](https://analitty.shinyapps.io/Scouting_Report/)**


This dashboard was made to facilitate any analysis of how certain player(s) perform against certain team(s). 
As of now it works by selecting any NBA player (say Player A) and basketball metric (Assists per Game), and one tab will show you historic performance of Player A with a combination of tables, plots and numbers. You can also input an opponent team (Team B) that the given player will go up against, and the second tab will show you the historic performance of all players *similar* to Player A when they have played against Team B. Similarity is determined using a combination of Principal Component Analysis and Hierarchical Clustering. 

I have many future plans to improve this dashboard:
- improve the similarity measure
- add a feature allowing us to compare performance of a player/team when specific teammate(s) or opposing player(s) are playing or not playing
- include data from past seasons
- include an actual forecasting model

