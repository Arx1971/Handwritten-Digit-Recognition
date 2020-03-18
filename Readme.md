## Hand Written Digit Recognition Using Supervised Machine Learning

#### Stratified Sampling

Population are devide into K-groups and then use random sampling to select Individual from Group.

#### K-Fold Cross Validation

	<ol>
		<li> Split the dataset into K equal partitions (or "folds").</li>
		<li> Use fold 1 as the testing set and the union of the other folds as the training set.</li>
		<li> Calculate testing accuracy.</li>
		<li> Repeat steps 2 and 3 K times, using a different fold as the testing set each time.</li>
		<li> Use the average testing accuracy as the estimate of out-of-sample accuracy.</li>
	</ol>

##### Diagram For K-Fold cross Validation
<img src="https://github.com/Arx1971/Handwritten-Digit-Recognition/blob/master/TPR_vs_FPR.png"
     alt="TPR_VS_FPR"
     style="float: left; margin-right: 10px;" />
     
#### AUC - ROC

AUC - ROC curve is a performance measurement for classicication problem. a varuous thresholds setting.s ROC is probability curve and AUC represetns degree of measure of separability. It tells how much model is capable of distinghuishing between classes. Higher the AUC, btter the model is at predictiong 0s as 0s and 1s as 1s. The ROC curve is plotted with TPR against the DPR where TPR is on y-axis and FPR is on the x-axis.
<img src="https://github.com/Arx1971/Handwritten-Digit-Recognition/blob/master/TPR_vs_FPR.png"
     alt="TPR_VS_FPR"
     style="float: left; margin-right: 10px;" />