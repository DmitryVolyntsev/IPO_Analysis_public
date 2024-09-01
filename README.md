# IPO_Analysis_public

There is public version of my research on USA tech startups and their funding rounds.
It includes several approaches in data preprocessing and ML model development for future funding rounds prediction based on features such as previous fundings, valuation, market conditions, startup age and time between rounds, investors, industry, founders "pedegree" and many other. Each model includes DataPrep notebook with data filtering, preprocessing, adding new features and other manipulations, and PredictionModel with further data transformation into a form suitable for machine learning and several ML approaches with results and their comparison. Official version of the model is located in the subfolder **wave2**

## model_ver_based_on_2019

Folder model_ver_based_on_2019 includes my Jupyter notebooks and DEMO datasets based on data until the 2019.
1) Categories - research on industries and fields of activity startup belongs to the most, that can be used as feature in the model.
2) valuation prediction - early version of my regression model. It predicts post-money valuation of the startup in next funding round. Сonsidered insufficiently accurate for use, requires further development.
3) wave1 - first version of my classification model that predicts if the startup will have next funding round/exit or it will be closed. It includes big research on founders and people work in the startup, their education, previous jobs and experience, position in the company. This data is transormed into one-hot vectors for future processing in the model. The accuracy of the model around 68%.
4) **wave2** - second version of my classification model that predicts if the startup will have next funding round/exit or it will be closed. It includes research on market conditions based on NASDAQ index, money supply (M2), inflation and other factors that affect startup funding and unicorn appearance. The accuracy of the model around 72-77%.

## model_ver_based_on_2022

Folder model_ver_based_on_2022 based on previous research with updated datasets and regression model. Сonsidered insufficiently accurate for use, requires further development.
1) Categories - research on industries and fields of activity startup belongs to the most, that can be used as feature in the model.
2) Investors - research on investors "pedegree" based on previous big and successful rounds and exits, that can be used as feature in the model.
3) html preprocessing - testing parsers for new data about startups
4) Regression model for predicting, how much money will startup rise in the next round.

## research_2020

Folder research_2020 includes testing parser that takes S-1 forms from SEC website and finds IPOs based on conditions. It wasn't used in the research and models above.
