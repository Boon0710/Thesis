# Vietnamese Financial News Sentiment Classification

This bachelor’s thesis project fine-tunes `vinai/phobert-base-v2` to classify Vietnamese financial news as negative, neutral, or positive.

- [Fine_tune_phoBert.ipynb](Fine_tune_phoBert.ipynb) contains the training and evaluation code.
- [V5_data.csv](V5_data.csv) contains the labeled dataset.

To reproduce the results, open the notebook in Jupyter or Google Colab, place the CSV in the notebook’s working directory, and run the setup, training, and evaluation cells in order.

The saved evaluation reports **85.71% accuracy** and a **macro F1 score of 0.8549** on 658 test examples.
