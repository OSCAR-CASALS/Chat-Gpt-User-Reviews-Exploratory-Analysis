# Chat Gpt User Reviews Exploratory Analysis

An exploratory analysis of the dataset https://www.kaggle.com/datasets/alexandrakim2201/chatgpt-user-reviews using LinguaLoupe (https://github.com/OSCAR-CASALS/LinguaLoupe)

In the following weeks a document with a proper analysis of the report will be added, showing the insights that have been extracted from this exploration.

The command used to build this report was the following:

```
python LinguaLoupe.py -ti 'CHATGPT User Reviews' -dt test_datasets/Final_Dataset.csv -text_c Review -o results -lang english -col label -colors colors/chatgpr_user_reviews_colors.json -min_topic_size 10 -min_topic_size_global 20 -e_model sentence-transformers/all-mpnet-base-v2
```

Since the original dataset was already divided  by sentiment, for this dataset only topic analysis was performed.
