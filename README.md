# SOUP: A new approach in handling Imbalanced Multi-class problems

<p align="justify">Up to now many specialized methods for improving the classification of imbalanced data have been introduced. However, most of the current research concerns binary classification problems. Moreover, multiclass imbalanced classification problems are more difficult than their binary counterparts. The most well-known resampling technique for imbalanced multi-class problems is SMOTE, which stands for Synthetic Minority Over-sampling TEchnique. SMOTE is an oversampling approach that creates synthetic minority class samples.</p>

<p align="justify">However, class imbalances are often accompanied by data difficulty factors. Factors include the overlapping between the classes or the presence of many minority class examples inside the majority class region. As a result, examples from these overlapped regions, which belong to different classes and have similar attribute descriptions, usually negatively influence predictive accuracy. The need for richer modeling complex relations between classes, which is missed by current approaches led the proposal of SOUP.</p>

<p align="justify">Lango et al.(2017) proposed a hybrid resampling technique SOUP which stands for Similarity Oversampling and Undersampling Preprocessing. The concept behind this proposed technique is first removing the most harmful majority class examples and then oversampling the most important minority ones according to their safe levels which had resulted from analyzing their neighborhood.</p>

<b>Highlights</b>
<ul>
	<li>Safety coefficients can be efficiently exploited in resampling techniques to improve classifiers.</li>
	<li>SOUP looks at the complex relations between classes and proposed a dataset with reasonable size.</li>
	<li>SOUP works significantly better than SMOTE if samples from different classes are overlapping.</li>
</ul>

Open <a href="https://github.com/jazeljayme/SOUP-A-new-approach-in-handling-Imbalanced-Multi-class-problems/blob/master/SOUP%20Final%20Report.ipynb">SOUP Final Report.ipynb</a> to view the full report.
ML2
