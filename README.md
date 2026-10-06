# Chat Gpt User Reviews Exploratory Analysis

An exploratory analysis of the dataset https://www.kaggle.com/datasets/alexandrakim2201/chatgpt-user-reviews using LinguaLoupe (https://github.com/OSCAR-CASALS/LinguaLoupe)

On the next weeks a document with a proper analysis of the report will be added, showing the insights that have been extracted from this exploration.

The command used to build this report was the following:

```
python LinguaLoupe.py -ti 'CHATGPT User Reviews' -dt test_datasets/CHATGPT_Reviews_Clean.csv -text_c Review -o results -lang english -col label -colors colors/chatgpr_user_reviews_colors.json -min_topic_size 24 -min_topic_size_global 50 -e_model sentence-transformers/all-MiniLM-L6-v2 -summarize mistralai/Mistral-7B-Instruct-v0.3
```
