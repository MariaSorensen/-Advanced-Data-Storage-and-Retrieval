# Surfs Up!

![surfs-up.jpeg](Images/surfs-up.jpeg)

## Climate Analysis and Exploration

This program uses Python and SQLAlchemy ORM queries, Pandas, and Matplotlib to do basic climate analysis and data exploration of a climate database.

* SQLAlchemy `create_engine` to connect to your sqlite database.

* SQLAlchemy `automap_base()` to reflect tables into classes.

### Precipitation Analysis

* A query designed to retrieve the last 12 months of precipitation data.

* Query results are loaded into a Pandas DataFrame.

* Results are plotted using the DataFrame `plot` method.

* The program uses Pandas to print the summary statistics for the precipitation data.

### Station Analysis

* A query designed to calculate the total number of stations, find the most active stations, list the stations and observation counts.

* A query designed to retrieve the last 12 months of temperature observation data (tobs).
