
# PharmaOptiMix: Pharmaceutical Sales Optimization Project

## Table of Content
  * [Demo](#Demo)
  * [Introduction](#Introduction)
  * [Methodology](#Methodology)
  * [Data Analysis](#Data-Analysis)
  * [Forecasting Approaches](#Forecasting-Approaches)
  * [Forecasting Models](#Forecasting-Models)
  * [Conclusion](#Conclusion)
  * [Bug / Feature Request](#bug---feature-request)
  * [Technologies Used](#Technologies-Used)
  * [Future-Work](#Future-Work)
  * [Project Contributors](#Project-Contributors)


## Demo
Link: [https://huggingface.co/spaces/Shubhankar9934/PharmaOptiMix/](https://huggingface.co/spaces/Shubhankar9934/PharmaOptiMix/)

[![](https://i.imgur.com/CMPuWod.png)](https://huggingface.co/spaces/Shubhankar9934/PharmaOptiMix)

[![](https://i.imgur.com/cgXpFDw.png)](https://huggingface.co/spaces/Shubhankar9934/PharmaOptiMix)

[![](https://i.imgur.com/zfGMhV5.png)](https://huggingface.co/spaces/Shubhankar9934/PharmaOptiMix)

## Introduction

"PharmaOptiMix" is a pharmaceutical sales optimization project that aims to enhance forecasting methodologies for improved sales and marketing strategies. The project involves the exploration of modern time-series forecasting methods in the pharmaceutical industry, benchmarking against traditional approaches such as Naïve, Seasonal Naïve, and Average methods.

## Methodology

### Data Analysis
- Conducted annual, weekly, and daily data analyses for insights into sales and marketing strategies.
- Analyzed stationarity, autocorrelation, and predictability in individual time series groups to inform forecasting parameters.

### Forecasting Approaches
- Utilized weekly-scale forecasting with rolling forecast and long-term forecast methodologies.
- Validated with a train-test split using the last year of data, employing Mean Squared Error (MSE) as the key performance indicator.

### Forecasting Models
- Implemented ARIMA, Auto ARIMA, Prophet, and various LSTM architectures (Vanilla, Stacked, Bi-Directional).
- Optimized hyper-parameters through manual tuning, Python's statsmodels, and grid search.

## Conclusion

Conducted comprehensive time-series analyses and forecasts, achieving a notable 17% Mean Absolute Percentage Error (MAPE). Demonstrated proficiency in both traditional and modern forecasting methods. Recommendations include exploring multivariate time series forecasting and incorporating explanatory variables, such as drug prices, for further improvements in accuracy.

## Bug / Feature Request

If you find a bug (the website couldn't handle the query and / or gave undesired results), kindly open an [issue](https://github.com/Shubhankar9934/-PharmaOptiMix-Pharmaceutical-Sales-Optimization-Project/issues) here by including your search query and the expected result

## Technologies Used

![](https://forthebadge.com/images/badges/made-with-python.svg)

[<img target="_blank" src="https://i.imgur.com/Bo2XzCb.png" width=170>](https://flask.palletsprojects.com/en/1.1.x/) [<img target="_blank" src="https://i.imgur.com/3VKfajN.png" width=280>](https://gunicorn.org) [<img target="_blank" src="https://scikit-learn.org/stable/_static/scikit-learn-logo-small.png" width=200>](https://scikit-learn.org/stable/) 

## Future Work
- Consider increasing data volume, exploring different accuracy metrics, and optimizing hyper-parameters for LSTM models.
- Test other architectures, such as CNN LSTM and ConvLSTM.
- Expand to multivariate time series forecasting for reduced model uncertainty.
## Project Contributors

This project is built and maintained by:

- [Shubhankar](https://github.com/Shubhankar9934)
- [Siddhesh](https://github.com/siddheshsakpal)
- [Sikender](https://github.com/wenja1)

Feel free to check out their GitHub profiles for more information about each contributor.
---


