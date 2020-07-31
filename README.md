# In-depth Analysis of Breast Cancer Dataset

<hr>

The datset has been obtained from Kaggle, the link is privided <a href="https://www.kaggle.com/uciml/breast-cancer-wisconsin-data/version/2">HERE</a>. The dataset contains the information for the patients in Wisconsin suffering from Breast Cancer. 

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
n the 3-dimensional space is that described in: K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34.

## Attribute Information are as follows:
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