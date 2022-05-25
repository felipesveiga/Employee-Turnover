# Employee-Turnover
A Machine Learning project for employee turnover prediction.

It had begun with an exploratory analysis on the dataset. Next, a transformation pipeline was built so that the data could be properly handled by the models.

The modelling phase was comprised of four stages:
<ul style='list-style-type:decimal'> 
    <li> 
        Initial Validations with simpler models.
    </li>
    <li> 
        Removal of non-important features with the use of the Random Forests algorithm.
    </li>
    <li> 
        Further validations without the irrelevant features & selection of the deployment contenders. 
    </li>
    <li> 
        Using the chosen models on the test set and defining the deployment one.
    </li>
</ul>

After this strict and extensive process, a Neural Network was selected for deployment with a ROC-AUC index of over 96%.