## AI for Improving Road Safety in Bangladesh (An Omdena Project)

### [Demo](https://youtu.be/AAYv1Abv7gk)

A demo video of the Streamlit implementation of the portion of the whole project done by me is included here. Please feel free to watch. 

[![Watch Demo Here](https://github.com/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/steamlit.JPG)](https://youtu.be/AAYv1Abv7gk)

### About the project

Road safety is a major concern in Bangladesh. An estimate states that 55 people are killed in road crashes every day, and that vulnerable road users including walkers, motorcyclists, and unsafe and informal public transportation users account for more than 80% of road traffic deaths. 

The goal of the project was to:

- Collect road accident-related data from public databases, newspapers, web pages, etc.
- Analyze the data following a systematic methodology
- Perform exploratory data analysis
- Outline an AI-driven solution to improve road safety (Time-Series Forecast and Classification)

I was able to contribute by data collection (webscraped two newspapers: [Prothom Alo](https://en.prothomalo.com/) and [Dhaka Tribune](https://www.dhakatribune.com/) and Google News), exploratory data analysis and creating dashboards (see links below), time-series forecast and time-series classification (see the repo notebooks) and wrap up the whole pipeline on Streamlit to be deployed on cloud. 

### What's inside the notebooks?

#### Time-Series Forecast

- [CNN-LSTM](https://github.com/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Time%20Series%20Forecast/Cnn-LSTM%20for%20TS%20Forecast.ipynb)
- [LSTM](https://github.com/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Time%20Series%20Forecast/LSTM%20for%20TS%20Forecast.ipynb)
- [Greykites](https://nbviewer.jupyter.org/github/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Time%20Series%20Forecast/Greykites%20for%20TS%20Forecast.ipynb)
- [Kats: SARIMA & Prophet](https://github.com/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Time%20Series%20Forecast/Kats-SARIMA%20%26%20Prophet.ipynb)
- [PyCaret TS Analysis](https://github.com/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Time%20Series%20Forecast/PyCaret%20TS.ipynb)

#### Times-Series Classification

- [HyperOpt Optimized QDA](https://github.com/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Time%20Series%20Classification/HypertOpt%20QDA.ipynb)
- [MLJar: Ensemble](https://github.com/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Time%20Series%20Classification/MLJar%20Ensemble.ipynb)
- [SkTime Multivariate Analysis](https://github.com/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Time%20Series%20Classification/SkTime%20Multivariate%20Analysis.ipynb)
- [TPOT Optimized MLP Classifier](https://github.com/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Time%20Series%20Classification/TPOT%20MLP%20Classifier.ipynb)
- [PyCaret: QDA](https://github.com/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Time%20Series%20Classification/PyCaret%20QDA.ipynb)

#### Text Analytics

- [Topic Modelling](https://nbviewer.jupyter.org/github/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Topic%20Modelling%20Accident%20News.ipynb)

#### Folium Heatmaps

- [Dhaka Tribune](https://nbviewer.jupyter.org/github/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Folium%20Heatmap%20with%20Time/omdena-dhaka-tribune-map.ipynb), [Daily Observer](https://nbviewer.jupyter.org/github/SumaiaParveen/Omdena-AI-for-Road-Safety-In-Bangladesh/blob/main/Folium%20Heatmap%20with%20Time/omdena-daily-observer-map.ipynb)

#### Flourish Visualizations

- [Bar chart race showing top 15 days with most death cause by road accidents](https://public.flourish.studio/visualisation/6687631/)
- [Complete statistical analysis dashboard](https://public.flourish.studio/story/941600/)







