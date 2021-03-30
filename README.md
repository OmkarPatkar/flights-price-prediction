# flights-price-prediction

## Table of Content
  * [Demo](#demo)
  * [Overview](#overview) 
  * [Directory Tree](#directory-tree)
  * [Installation](#installation)
  * [Future scope of project](#future-scope)


## Demo
![flight](https://user-images.githubusercontent.com/40171054/112961339-e8978a00-9162-11eb-8f1c-eed738d71a40.png)


## Overview
This is an end-to-end machine learning project, to predict flight fare prices.

## Directory Tree 
```
├── static 
│   ├── css
│     ├── style.css
├── templates
│   ├── index.html
├── Procfile
│── Data_Train.xlsx
│── Test_set.xlsx
├── README.md
├── app.py
├── flights-price-prediction.ipynb
├── flights_requirements.txt
│── procfile
│── runtime.txt
```

## Installation
The Code is written in Python, If you don't have Python installed you can find it [here](https://www.python.org/downloads/). 

```bash
git clone https://github.com/OmkarPatkar/flights-price-prediction.git
cd flights-price-prediction-main
```

Then run the flights-price-prediction.ipynb file to generate the model file, once we have the model(pkl) file we can move forward.

```bash
pip install -r flights_requirements.txt
python app.py
```

## Future Scope

* Use multiple Algorithms
* Optimize Flask app.py
* Front-End 
* Deploy the web app
