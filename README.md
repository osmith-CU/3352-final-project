# 3352-final-project
  This is the final project for CSCI 3352: Biological Networks. We will essentially be compiling a wide array of food networks, gathering their network statistics, 
and seeing if we can use a machine learning algorithm to predict the mean annual temperature of the region in which the food web was observed.
  One directory will contain all the network data which will read using the networkX library. Once network statistics are gathered, we will
load these into a PD dataframe wherein one row represents one network. We will then train a regression tree ML algorithm against ~90% of our data
at random, ultimately calculating an accuracy statistic of predicted temperature to observed temperature.
