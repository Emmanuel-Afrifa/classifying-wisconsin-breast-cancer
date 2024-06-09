# Breast Cancer Prediction

The aim of this project is to build a classification model capable of classifying whether a given cell is malignant (cancerous) or benign (non-cancerous).

- [Information about Dataset](#info)
- [Tools Used](#tool-used)
- [Procedure](#procedure)
- [Challenges and Recommendations](#challenges-and-recommendations)
- [Data Source](#data-sources)
- [References](#references)
- [About Author](#author)


## Info
The dataset consists of 33 features and 569 observations. These features were computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.  They describe characteristics of the cell nuclei present in the image. Some of the images can be found at http://www.cs.wisc.edu/~street/images/ .

Ten real-valued features are computed for each cell nucleus:

	- radius (mean of distances from center to points on the perimeter)
	- texture (standard deviation of gray-scale values)
	- perimeter
	- area
	- smoothness (local variation in radius lengths)
	- compactness (perimeter^2 / area - 1.0)
	- concavity (severity of concave portions of the contour)
    - concave points (number of concave portions of the contour)
	- symmetry 
	- fractal dimension ("coastline approximation" - 1)

The mean, standard error and "worst" or largest (mean of the three largest values) of these features were computed for each image, resulting in 30 features. For instance, field 3 is Mean Radius, field 13 is Radius SE, field 23 is Worst Radius.

## Tool Used
I used the Python programming language (version 3.10.8) to carry out this project. In particular, I use the following libraries:
    - Numpy (1.26.2): For numerical computations.
    - Pandas (2.1.4): For the Dataframe and some analysis thereof.
	- Matplotlib (3.8.2): For visualizations
	- Seaborn (0.13.0): For visualizations
	- Scikit-Learn (1.4.0): For data preprocessing, model building and metrics checking.

## Procedure
- Inspected the dataset for missing values and removed some clear irrelevant columns
- Carried out the exploratory data analysis to gain an insight into the dataset
- Through the EDA, I was able to select some important features for the model
- Built a Logistic regression model for classifying the cells as benign or malignant.
- Checked the accuracy and other metrics of the model. 

## Data Sources
- [UCI Machine learning library](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
- [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data)

## References
- [Feature selection and data visualization](https://www.kaggle.com/code/kanncaa1/feature-selection-and-data-visualization)
- [Logistic Regression](https://jovian.com/aakashns/python-sklearn-logistic-regression)
- [Breast Cancer Prediction](https://www.kaggle.com/code/buddhiniw/breast-cancer-prediction)

## Author
- Emmanuel Afrifa
- [emmaquame9@gmail.com](mailto:emmaquame9@gmail.com)
- [Frontend-Mentor](https://www.frontendmentor.io/profile/Emmanuel-Afrifa)
- [Twitter](https://twitter.com/Emma33712365)
- [Linkedin](https://www.linkedin.com/in/emmanuel-afrifa-840674214/)
