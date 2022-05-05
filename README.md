Tune the Baseline Trading Algorithm
Step 6: Use an Alternative ML Model and Evaluate Strategy Returns


In this section, you’ll tune, or adjust, the model’s input features to find the parameters that result in the best trading outcomes. You’ll choose the best by comparing the cumulative products of the strategy returns.


![](images/svm_small_training_baseline.png)  

![]('images/svm_80_20_training_baseline.png')  

![]('images/svm_golden_cross_dmac.png')  

![]('images/svm_15_30_dmac.png')  

![]('images/lr_5_10_dmac.png')  

![]('images/svm_5_10_dmac.png')  






Step 1: Tune the training algorithm by adjusting the size of the training dataset.

To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your README.md file.

Answer the following question: What impact resulted from increasing or decreasing the training window?

There was a 
Step 2: Tune the trading algorithm by adjusting the SMA input features.

Adjust one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results in your README.md file.

Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?
Step 3: Choose the set of parameters that best improved the trading algorithm returns.

Save a PNG image of the cumulative product of the actual returns vs. the strategy returns, and document your conclusion in your README.md file.
