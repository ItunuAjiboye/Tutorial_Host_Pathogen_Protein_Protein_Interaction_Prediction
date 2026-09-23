# Notebooks

This folder contains the six sequential Colab notebooks for the HP-PPI prediction tutorial. Run them in order.

| # | Notebook | Purpose |
|---|----------|---------|
| 1 | Dataset preparation | Compiles positive HP-PPI pairs, generates negative pairs, and performs the train/hold-out split. |
| 2 | Data preprocessing | Cleans and filters host and pathogen protein sequences. |
| 3 | Feature extraction | Computes AAC and PAAC_CTriad feature representations. |
| 4 | Machine learning | Trains and evaluates six classifiers via train/test evaluation and 10-fold cross-validation, across three imbalance ratios. |
| 5 | Hyperparameter tuning & LOPO validation | Tunes the top 3 classifiers, selects the best by cross-validation MCC, and evaluates generalization via host-disjoint Leave-One-Pathogen-Out validation. |
| 6 | Deployment | Refits the best model on the full dataset and applies it to predict new, unlabelled HP-PPI pairs. |
