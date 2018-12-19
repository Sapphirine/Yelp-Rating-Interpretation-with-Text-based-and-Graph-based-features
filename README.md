# Yelp-Rating-Interpretation-with-Text-based-and-Graph-based-features
Group 201812-46

[The Yelp Dataset](https://www.yelp.com/dataset)

Our experiment can be reproduced with the following steps:
+ Run `filter_jsons.py` to select only those reviews involving restaurants in Phoenix;
+ Run `json2txt.py` to do review text preprocessing and convert data into text format;
+ Run `extract_text_features.py` to extract text features and convert data into csv format;
+ Run scripts in `graph_scripts` to produce graph features;
+ Run `add_graph_features.py` to combine text features and graph features;
+ Run `run.py` to run all groups of experiments.

[Youtube Video](https://www.youtube.com/watch?v=NwBog99CCNg)