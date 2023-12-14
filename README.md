# Final Project: CS671 (Theory and Algorithms of Machine Learning)
## Professor Cynthia Rudin, Duke University

Necessary libraries are listed in spec-file.txt

This folder is also a git repository. The following folders have files that may be relevant for grading:
- report: PDFs of all notebooks and final report (Kaggle2023.pdf)
- src
    - predictions_v1.ipynb - Notebook containing initial/baseline models and hyperparameter tuning
    - predict.ipynb - Notebook containing final models used to generate predictions on test set and all associated data cleaning and feature engineering/extraction
- testing
    - eda.ipynb - Initial exploratory data analysis identifying important features from original data (and associated cleaning/extraction)
    - eda_advanced.ipynb - Next steps in exploratory data analysis experimenting with further feature extraction, aggregation, and clustering

The testing/EDA notebooks were actively being used to testing and tweaking, so they may not be reflective of the final models I used in my submissions. They are also going to be messy with errors in some places (due to my kernel crashing at random points and losing the local variables that took several minutes to generate). They also take a long time to run, so it may be advisable to leave these notebooks as is without running or editing (the key findings from them are summarized in the report).

Similarly, for the prediction notebooks, I was still making edits here and there to tweak my models and see what could be improved. As such, they may not be reflective of the final models and some variables and results may not be saved (again due to my kernel crashing and losing results like cross validation that took a long time to generate). My final models and results are all summarized in the report even if they are no longer in the notebook. That said, predict.ipynb should all set and ready to run without any changes. That was used to generate predictions and should process each dataset and train models correctly (although I may have changed the models away from the ones that generated my highest scores).

For both notebooks, pandas and sklearn throw an annoying number of errors and warnings, so I apologize for the hard-to-read text.

** For the purposes of having a nice-looking repo, I'll continue working on this project, at least cleaning up the notebooks if not also tweaking the models. The above is only applicable at the time of submission **

