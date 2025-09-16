Code execution:
To run the code from scratch
- First execute 1_computation, then 2_models to obtain the main test results. 
- Then execute 5_comput_uk, followed by 6_models_uk to obtain the results on the UK dataset.
All Excel files are already pushed on Github, so running 2_models and 7_models_uk directly also works.

Required environment: 
- Python 3.12 (using a newer version may cause compatibility issues with PyTorch → only needed for test_nn2)
- Package: numpy, pandas, openpyxl, scikit-learn, xgboost, statsmodels, scipy, matplotlib, tqdm
- Additionally: torch et skorch (only required for test_nn2.ipynb, which currently does not converge)