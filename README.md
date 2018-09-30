# depthchart

To update these codes: Firstly, add test matches' game id's and Secondly, edit the query page used to get the number of caps for each player out of the matches concerned.

Step 1: Run the "GetCommentaryTimeline.Rmd" to get the timeline data

Step 2: Run the "CapsOfTimelineMatches.Rmd" to get which players played how many games of the 11 matches with commentary data.

Step 3 (Run GetPlayerPlayingminutesPositions.Rmd): Integrate the two data frames created to get the number of minutes each player played for the 11 matches with commentary data.
Assumption: All players have different surnames

Step 4: Manually impute each player's position.

Step 5 (Run JapanDepthFrontend.Rmd): Use the PlayerPlayingminutesPosition data with the "JapanDepthFrontend.Rmd" to build the full-scale depth chart.

Step 6: Upload the chart on plotly (deliberately not coded on front end code)

The final plot: https://plot.ly/~kaitogoto7/5/
