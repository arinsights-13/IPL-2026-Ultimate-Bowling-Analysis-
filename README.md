# IPL-2026-Ultimate-Bowling-Analysis-
**Project Overview**
IPL 2026 Bowling Ultimate Analysis using **Power BI** and **Microsoft Excel**. T20 cricket isn't always about mere metrics but about hidden measures such as control, sustained output, applying pressure , etc. Using statistical modleling and powerful visualisation I tried to bring forth some hidden analysis.

**Key Questions to be Asked❗**
➡️Is the highest wicket-taker the best bowler of the tournament?
➡️What about Players who perform well but they have played less matches #due to injury, late bolster in performance, late addition, etc)
➡️Should the bowlers be credited for applying pressure? #Often few bowlers' role is to apply pressure and some other bowler gets the reward. 
➡️Should bowlers be credited for Phase-wise performance? #some bowlers could be good in only powerplay or in slog overs, its important to know the specialist for maximum optimisation of resources.

**UNDERSTANDING THE MODEL** 
Traditional bowling analysis in T20 cricket often revolves around wickets and economy rate. While these metrics are important, they fail to capture a bowler's overall influence on the game. One of the key aspects of our model is that we have utilised **Z scores to standardise the numbers of the bowlers. Also, I have used certain constraints or filters in certain visuals based on the relevance. For eg. Travis Head bowled 66 balls and picked one wicket, but his sample size is too small to be involved. Similarly, when it comes to Pressure index and BIS score, Saurabh Dubey did come around the list. There's no denying that he bowled well, but he came at the back end of the tournament for the Kolkata Knight Riders, and the sample size was too short.**

This project introduces a **Bowling Impact Score (BIS)** framework designed to evaluate bowlers holistically using IPL 2026 data. Other interesting metrics used are Pressure Index and Ph 

The model incorporates multiple dimensions of bowling performance:

**Objectives**
1. _Measure Overall Bowling Impact_
2. _Quantify Match Pressure_
3. _Evaluate Phase-Specific Excellence_
   Analyze bowling performance across:
   Powerplay Overs
   Middle Overs
   Death Overs
   using a custom Phase Impact Index.
4. _Classify Bowlers by Performance Archetypes_
   Segment bowlers into performance categories such as:
   Elite
   Top Guns
   Foot Soldiers
   Misfires
   based on their impact and pressure profiles.

**Key Metrics Developed👇**

_Bowling Impact Score (BIS)👇_
Composite metric built using:

Wicket Rate Z-Score
Dot Ball % Z-Score
Boundary Prevention Z-Score
Economy Rate Z-Score

_Pressure Index_👇
_Composite metric measuring a bowler's ability to:_
Frequency of picking up wickets
Generate dot balls
Restrict boundaries
Control scoring opportunities

_Phase Impact Index_👇
_Measures bowler effectiveness in:_
Powerplay
Middle Overs
Death Overs

using phase-level wicket-taking and pressure generation.

Key Findings
**Overall Impact Leaders**

🏆 Corbin Bosch emerged as the highest-impact bowler in IPL 2026 with a BIS of 1.44, indicating strong all-round bowling performance across multiple dimensions.

🏆 Jason Holder (1.29) and Bhuvneshwar Kumar (1.16) also ranked among the most complete bowlers of the season.

**Pressure Specialists**

🏆Sunil Narine recorded the highest Pressure Index (1.81) in the tournament.
_
Despite not leading the BIS rankings, Narine's ability to create sustained pressure made him one of the most influential bowlers in IPL 2026._

**Dot Ball Dominance**

🎯 Mohammed Siraj generated the highest Dot Ball Percentage (46.24%), consistently forcing batters into defensive situations.

**Strike Bowling**

⚡ Corbin Bosch also led the tournament in Wicket Rate among qualified bowlers, highlighting his ability to convert pressure into breakthroughs.

**Phase Specialists**
Powerplay👇
AJ Hosein
Mohammed Shami
Bhuvneshwar Kumar

emerged as the most effective new-ball bowlers.

Middle Overs👇
Ashok Sharma
K Rabada
JC Archer

showed strong control and wicket-taking ability.

Death Overs👇
Mohammed Siraj
Mohammed Shami
Mohsin Khan

performed strongly during the highest-pressure overs of the innings.

Tools Used
Power BI
DAX
Statistical Modelling
Z-Score Standardization
Data Visualization
Cricket Analytics

