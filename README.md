#### **Diamond Price Prediction ML project End to End**

## About Dataset

**Context**
This classic dataset contains the prices and other attributes of almost 54,000 diamonds. It's a great dataset for beginners learning to work with data analysis and visualization.

**Content**

- price: price in US dollars (\$326--\$18,823)

- carat: weight of the diamond (0.2--5.01)

- cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal)

- color: diamond colour, from J (worst) to D (best)

- clarity: a measurement of how clear the diamond is (I1 (worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF (best))

- x: length in mm (0--10.74)

- y: width in mm (0--58.9)

- z: depth in mm (0--31.8)

- depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)

- table: width of top of diamond relative to widest point (43--95)


This is a regression problem statement as price is a continuous variable.

Data was cleaned , transformed and fed to different regression algorithms and 
the r2 scores are as follows:

1. LinearRegression: 0.9362906819996049, 
2. Lasso: 0.9362869814082755,
3. Ridge: 0.9362900967491632,
4. ElasticNet: 0.8544967219374031, 
5. DecisionTree: 0.9542593157161697, 
6. **RandomForest**: 0.9769050054172058, 
7. KNN: 0.9718448407977691


Best model is  with R2 Score : 


💿 Installing
1. Environment setup.
```
conda create --prefix venv python==3.8 -y
```
```
conda activate venv/
````
2. Install Requirements and setup
```
pip install -r requirements.txt
```
5. Run Application
```
python application.py
```

🔧 Built with
- flask
- Python 3.8
- Machine learning
- Scikit learn
- 🏦 Industrial Use Cases

Best Model Name : **`RandomForest`** , r2 Score : 0.977<br>
Author: Dr. TEJAS. J<br>
email: tejasjacademics@gmail.com<br>