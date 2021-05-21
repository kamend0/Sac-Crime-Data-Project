# Sac-Crime-Data-Project
Exploration of crime data made available through the City of Sacramento's Open Data Portal: https://data.cityofsacramento.org/search?tags=Public%20Safety

The goals of this project are currently the following:
  1. Explore the data: discover trends over the entire time period available; see the effects of the pandemic on crime in the city; and ask and answer any remaining interesting questions about crime in Sacramento that we can answer with this data.
  2. Visualize the data: using Seaborn plots to see numerical trends; and a combination of Folium, Matplotlib, and GeoPandas to see what crime happens where in the City.
  3. Predict future crime: using a machine learning model based on the scrubbed data, as well as other datasets (e.g. Census data) to find what, where, and when future crime will occur.

See the "Crime Data Exploration" notebook for a "guided tour" of the data (which addresses the first two goal items); and the assorted "(x)year" CSV files for the raw data. To view the notebook, I really suggest using nbviewer: https://nbviewer.jupyter.org/github/kamend0/Sac-Crime-Data-Project/blob/main/Crime%20Data%20Exploration.ipynb

NOTE ON THE NOTEBOOK: It references all data being in a directory called CrimeData, which is leftover from running locally. If running yourself, either toss the raw data into a directory named CrimeData or remove the reference to that directory in the initial data-pulling loop.

I also aim to create a MySQL database locally on my machine once I begin pulling in Census (and/or other) data to support the ML model. I have one set up now, but it's a little redundant given the relatively small amount of and non-disparate data we have now.
