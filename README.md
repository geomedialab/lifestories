This repository contains a series of python-based adaptations of the Geomedialab's (Concordia U) Lifestory data which can be understood and executed in the following order:
- a data cleaning, formatting and transformation pipeline (dataframe_processing_and_export.ipynb) that takes data* from '/documents_place_mentions' and '/documents_story_units' and outputs .csv files into the '/EXPORT' directory.
- another data transformation pipeline that takes .csv files in the '/EXPORT' directory as inputs, executes more transformations, and generates several statistical analyses of these data.
- a time-based visualization of the spatial dimensions of oral life stories (generate_graphs.ipynb). The visualizations can be run and viewed in mybinder.org.

---

* data under '/documents_place_mentions' and '/documents_story_units' are stripped-down versions of the cleaned, original data located on the geomedialab's private servers.
