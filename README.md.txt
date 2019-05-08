Este Projeto consiste de :

Main.html = arquivo compilado em html do projeto
Main_code.ipynb = arquivo do codigo do projeto em ipynb
Relatório_Anime_sistema_recomendação = Arquivo sem nenhum código, apenas as descobertas e visualizações  




Benchmark deste projeto : https://www.kaggle.com/tanetboss/user-clustering-for-anime-recommendation/notebook

Data set deste projeto : https://www.kaggle.com/azathoth42/myanimelist

Arquivos utilizados:
Animelist.csv
users_cleaned.csv
animelists_filtered.csv

Bibliotecas e Imports utilizados:

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import itertools
import collections
from datetime import date
from sklearn.decomposition import PCA
from mpl_toolkits.mplot3d import Axes3D
from sklearn import mixture
from sklearn.metrics import silhouette_score
from sklearn.cluster import KMeans
from sklearn.preprocessing import MinMaxScaler
from sklearn.metrics import mean_squared_error
from wordcloud import WordCloud

%matplotlib inline


Outras informações Pertinentes:

O projeto demora por volta de 40 min para ser executado, 
você pode encontrar erros de memoria durante a execução,
 este projeto rodou no computar com 16gb ram DDR4, GPU Intel i5-6600k.
