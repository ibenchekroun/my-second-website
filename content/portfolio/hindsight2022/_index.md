---
date: "2022-01-13"
designs:
- NBA   
jobDate: January 2022
projectUrl: https://analitty.shinyapps.io/fantasycrib/
techs:
- R shiny
thumbnail: hindsight2022/AD.png
title: Hindsight 2022 - NBA Fantasy Dashboard
work:
cover:
    image: /AD.png/ # image path/url

---
**[LINK TO DASHBOARD: https://analitty.shinyapps.io/2021-2022-Fantasy-calculator/](https://analitty.shinyapps.io/2021-2022-Fantasy-calculator/)**

This dashboard calculates your NBA fantasy team's performance against an opposing team, given the players you input for both teams and given the week of performance. 
It's purely historical data; the performance shows you how your team would have faired in a past week.
I found it useful personally for deciding whether I should drop a specific player to pick up another specific player, in preparation for my next week's matchup. 
If, historically, my next week matchup would have beaten me most weeks in the past with my current team but not if I had picked up the other player, then that could be motivation to pick up the new player.

All the data used for this dashboard was scraped from [basketball-reference.com](basketball-reference.com) in R using the rvest library.

The design is a work in progress, but it's functional. 
When I have the time I hope to add new features such as "Team MVP" where, based on historical performance, the dashboard provides you with your team's most valuable player for a given week. 
