# COVID-19-Visualization
### COVID-19 Analystic and visulization
* Using data API from rappid API and data from opensource in Github<br />
* Using libraries (detail: reqirement.txt) processing data, visualization and interaction with data<br />

### Image of dashboard COVID-19
![COVID-19 DASHBOARD](https://github.com/thoadao0301/COVID-19-Visualization/blob/main/Final_report_COVID19.png)


### Installation 

To run this project you must have python 3 with virtual enviroment package

To install virtualenv run:
```
pip install virtualenv
```

Then
```
cd my-project/
virtualenv venv
```

To activate your virtual env

```
source venv/bin/activate # on mac
venv\Scripts\activate.bat # on window
```

To leave the virtual environment run:
```
deactivate
```

To install packages (Must in virutal env)

```
pip install -r requirements.txt
```

To run jupyter notebook as dashboard we can use voila

```
pip install voila
voila ./Notebook/Final_report_COVID19.ipynb 
```


* Ref link https://github.com/duarteocarmo/interactive-dashboard-post