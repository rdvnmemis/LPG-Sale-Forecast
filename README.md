# LPG_Sale_Forecast

# Libraries
argon2-cffi                   20.1.0
async-generator               1.10
attrs                         21.2.0
backcall                      0.2.0
backports.functools-lru-cache 1.6.4
bayesian-optimization         1.2.0
beautifulsoup4                4.10.0
bleach                        4.0.0
bs4                           0.0.1
catboost                      1.0.3
certifi                       2021.10.8
cffi                          1.15.0
charset-normalizer            2.0.10
colorama                      0.4.4
cycler                        0.11.0
debugpy                       1.5.1
decorator                     5.1.1
defusedxml                    0.7.1
docplex                       2.20.204
entrypoints                   0.3
et-xmlfile                    1.1.0
fonttools                     4.28.5
graphviz                      0.19.1
idna                          3.3
importlib-metadata            4.8.2
ipykernel                     6.6.1
ipython                       7.31.0
ipython-genutils              0.2.0
ipywidgets                    7.6.5
jedi                          0.18.1
Jinja2                        3.0.2
joblib                        1.1.0
jsonschema                    3.2.0
jupyter-client                7.1.0
jupyter-core                  4.9.1
jupyterlab-pygments           0.1.2
jupyterlab-widgets            1.0.2
kiwisolver                    1.3.2
MarkupSafe                    2.0.1
matplotlib                    3.5.1
matplotlib-inline             0.1.3
mistune                       0.8.4
nbclient                      0.5.3
nbconvert                     6.1.0
nbformat                      5.1.3
nest-asyncio                  1.5.4
notebook                      6.4.6
numpy                         1.22.0
openpyxl                      3.0.9
packaging                     21.3
pandas                        1.3.5
pandocfilters                 1.4.3
parso                         0.8.3
pickleshare                   0.7.5
Pillow                        9.0.0
pip                           21.3.1
plotly                        5.5.0
prometheus-client             0.12.0
prompt-toolkit                3.0.24
pyaml                         21.10.1
pycparser                     2.21
Pygments                      2.11.2
pyparsing                     3.0.4
pyrsistent                    0.18.0
python-dateutil               2.8.2
pytz                          2021.3
pywin32                       303
pywinpty                      0.5.7
PyYAML                        6.0
pyzmq                         22.3.0
requests                      2.27.1
scikit-learn                  1.0.2
scikit-optimize               0.9.0
scipy                         1.7.3
seaborn                       0.11.2
Send2Trash                    1.8.0
setuptools                    58.0.4
six                           1.16.0
sklearn                       0.0
soupsieve                     2.3.1
tenacity                      8.0.1
terminado                     0.9.4
testpath                      0.5.0
threadpoolctl                 3.0.0
tornado                       6.1
tqdm                          4.62.3
traitlets                     5.1.1
urllib3                       1.26.8
wcwidth                       0.2.5
webencodings                  0.5.1
wheel                         0.37.0
widgetsnbextension            3.5.2
wincertstore                  0.2
xlrd                          2.0.1
zipp                          3.6.0


# Project Motivation
In this peojext i will be analyzing LPG usage in each sub category and try to make a connection between each category and public holidays in Turkey. We hope to answer the following questions.
1.	Which holidays significantly effect the LPG consumption in each category?
2.	What is the relationship between number of Covid-19 cases and LPG usage in each category?
3.	Which features affect the LPG consumption and which machine learning model is the best fit to predict the LPG consumption in each category


# File Descriptions

In the DataAnalysis notebook we analysed the data and try to answer our conclusions about the LPG consumption.
In the SaleForecast notebook i arranged the data to be used in the machine learning model, i made hypterparameter tuning for ensemble models.

