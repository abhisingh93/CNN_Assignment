# Melanoma Detection Assignment

## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Contact](#Contact)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Conclusions
- Conclusion 1 from the analysis(First Model) - There is clearly evidence of overfitting, with the difference between training accuracy and validation accuracy being greater than 0.5. In addition, as can be observed in the graphs above, as training proceeds, while training loss decreases, validation loss increases.
- Conclusion 2 from the analysis(Second Model) - As can be seen, the model with augmentation layers and dropouts does perform a better on the training data. The model still performs poorly during inference using the validation set. There is some improvement, but the model is still overfitting.
- Conclusion 3 from the analysis(Final Model) - The results with dataset augmentation have shown significant improvement over previous models, with training accuracy of 0.9523 at 30 epochs, and validation accuracy at 0.8092. Model is still overfitting but can be resolved with more hypertuning by adding layes and dropouts.

## Contact
Created by @abhisingh93 - feel free to contact me!

