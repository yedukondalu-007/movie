# movie
import pandas as pd
ratings=pd.read_csv('/home/rgukt/Downloads/movie_data/ratings.csv')
movies=pd.read_csv('/home/rgukt/Downloads/movie_data/movies.csv')
df=pd.DataFrame(ratings)
movies.shape
#mov=df.loc[df['rating'].max()]
movdf=pd.DataFrame(movies)
#movdf.loc[movdf['movieId']==mov['movieId']]
matrix=movdf.loc[movdf['title']=='Matrix, The (1999)']
tg=matrix['movieId']
tags=pd.read_csv('/home/rgukt/Downloads/movie_data/tags.csv')
tdf=pd.DataFrame(tags)
ratings
import numpy as np
movdf=pd.DataFrame(movies)
md=movdf['movieId'].loc[movdf['title']=='Terminator 2: Judgment Day (1991)']
movdf.loc[movdf['title']=='The Shawshank Redemption (1994)']
df.groupby(['movieId'])['rating'].max()
