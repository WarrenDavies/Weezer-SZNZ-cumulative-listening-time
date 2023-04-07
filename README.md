# Weezer-SZNZ-cumulative-listening-time

Gets the cumulative listening time from the first date of each EP's release until the end of the season and displays it in a line chart.

Written in PySpark in a Jupyter notebook, you'll need Spark and Jupyter running.

To get the data you'll need to request your extended listening history from Spotify. You can't use the smaller exports you can get from them because these don't have album names (well you could, but you'd need to modify this to identify the EPs based on song names, and update the column names which are different in the two data sets).