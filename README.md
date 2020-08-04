# In-depth Analysis of Breast Cancer Dataset

<hr>

## Breast Cancer in US.

In 2019, an estimated 268,600 new cases of invasive breast cancer will be diagnosed in women in the U.S. as well as 62,930 new cases of non-invasive (in situ) breast cancer. 62% of breast cancer cases are diagnosed at a localized stage, for which the 5-year survival rate is 99%. This year, an estimated 41,760 women will die from breast cancer in the U.S. Although rare, men get breast cancer too. The lifetime risk for U.S. men is about 1 in 1,000. An estimated 2,670 men will be diagnosed with breast cancer this year in the United States and approximately 500 will die. 1 in 8 women in the United States will develop breast cancer in her lifetime. Breast cancer is the most common cancer in American women, except for skin cancers. There are over 3.5 million breast cancer survivors in the United States. On average, every 2 minutes a woman is diagnosed with breast cancer in the United States. Female breast cancer represents 15.2% of all new cancer cases in the U.S.

Source : <a href="https://www.nationalbreastcancer.org/breast-cancer-facts#:~:text=In%202019%2C%20an%20estimated%20268%2C600,year%20survival%20rate%20is%2099%25." style="text-decoration: none;">NationalBreastCancer.org</a>

<hr>

## About Data Set

The datset has been obtained from Kaggle, the link is privided <a href="https://www.kaggle.com/uciml/breast-cancer-wisconsin-data/version/2" style="text-decoration: none;">HERE</a>. The dataset contains the information for the patients in Wisconsin suffering from Breast Cancer.

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34.

## Attribute Information

<ul>
    <li>ID Number</li>
    <li>Diagnosis (M = malignant, B = benign)</li>
    <li>Columns 3 - 32 Contains (The calulations have been performed using three metrics : Mean, Standard Error and Worst. Each section contains 10 columns, in total resulting in 30 columns.) : </li>
    <ol>
        <li>radius (mean of distances from center to points on the perimeter)</li>
        <li>texture (standard deviation of gray-scale values)</li>
        <li>perimeter</li>
        <li>area</li>
        <li>smoothness (local variation in radius lengths)</li>
        <li>compactness (perimeter^2 / area - 1.0)</li>
        <li>concavity (severity of concave portions of the contour)</li>
        <li>concave points (number of concave portions of the contour)</li>
        <li>symmetry</li>
        <li>fractal dimension ("coastline approximation" - 1)</li>
    </ol>
    
</ul>

The mean, standard error and "worst" or largest (mean of the three
largest values) of these features were computed for each image,
resulting in 30 features. For instance, field 3 is Mean Radius, field
13 is Radius SE, field 23 is Worst Radius.

<hr>

All feature values are recoded with four significant digits.

Missing attribute values: none

Class distribution: 357 benign, 212 malignant

<hr>
