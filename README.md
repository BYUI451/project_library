# The Seattle Public Library Model

[The Seattle Public Library](https://www.spl.org/) provides two data sets with millions of rows that we can leverage for analytics. They also offer a [Integrated Library System (ILS) Data Dictionary](https://data.seattle.gov/Community/Integrated-Library-System-ILS-Data-Dictionary/pbt3-ytbc).  We want to build a data analytics tool that leverages this data source.

## Data description

### Library Collection Inventory

- [Library Collection Inventory](https://data.seattle.gov/Community/Library-Collection-Inventory/6vkj-f5xf)

This dataset includes monthly snapshots of all of the physical items in the Seattle Public Library’s collection. Consistent monthly data begins with a snapshot taken August 1, 2016, continuing to the present. Additionally, this dataset contains snapshots taken on: January 1 in the years 2012, 2013, 2014, and 2016. [ref](https://data.seattle.gov/api/views/6vkj-f5xf/files/61a7279a-85fb-4061-8a65-6c09bb63ecbe?download=true&filename=Library%20Collection%20Inventory%20FAQs.pdf)

### Checkouts by Title

- [Checkouts by Title](https://data.seattle.gov/Community/Checkouts-by-Title/tmmm-ytt6)

This dataset consists of monthly counts by title of checkout for all physical and digital items from 2005 to the present. It’s, of course, a hefty dataset with more than 25 million. Checkout data comes from multiple current and historical sources. For digital items, the media vendors: Overdrive, hoopla, Freegal, and RBDigital provide usage data. For historical physical item checkouts from April 2005 to September 30, 2016, this data source is the Legrady artwork data archives. From October 1, 2016, to the present, the source is the Horizon ILS.

## Data challenge

### Descriptive Analytics and Dashboarding

1. Use Pyspark and your [all-spark-notebook](https://hub.docker.com/r/jupyter/all-spark-notebook) to complete your investigation.
2. Use [streamlit](https://streamlit.io/) and [docker](https://www.docker.com/) to build your interactive dashboard.
3. Potentially [connect to their API](https://dev.socrata.com/foundry/data.seattle.gov/6vkj-f5xf) for auto-updates.

### Predictive Modeling

1. Use one of the Spark ML models with a predictive idea of your team's creation to assist the library or library users.
2. Incorporate that predictive model into your dashboard.


