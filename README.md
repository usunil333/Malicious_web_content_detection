
###To create virtual environment, run th following command:
```bash
virtualenv myvenv
```
```bash
myvenv\Scripts\activate
```
###After creating virtual environment, install the requirements:
```bash
pip install -r requirements.txt
```
###Once all the requirements are installed, we can directly run app.py
```bash
python app.py
```

## Directory Tree 
```
├── pickle
│   ├── model.pkl
├── static
│   ├── styles.css
├── templates
│   ├── index.html
├── Phishing URL Detection.ipynb
├── Procfile
├── README.md
├── app.py
├── feature.py
├── phishing.csv
├── requirements.txt


```
## Result

Accuracy of various model used for URL detection
<br>

<br>

||ML Model|	Accuracy|  	f1_score|	Recall|	Precision|
|---|---|---|---|---|---|
0|	Gradient Boosting Classifier|	0.974|	0.977|	0.994|	0.986|
1|	Random Forest|	                0.967|	0.971|	0.992|	0.991|
2|	XGBoost Classifier| 	        0.970|	0.973|	0.993|	0.984|
3|	Decision Tree|      	        0.958|	0.962|	0.991|	0.993|
4|	Naive Bayes Classifier|     	0.605|	0.454|	0.292|	0.997|











