# CIKM AnalytiCup 2017 challenge entry


Rough unedited code used in data science contest - CIKM AnalytiCup 2017 challenge - to predict short-term rainfall. 

This solution used a convolutional recurrent neural network (convLSTM) analysing sequential radar maps. Maps were provided at 4 different altitudes, and a separated model was built for each, with predictions averaged.

Final score (RMSE) was 14.8 (top 100), relative to top 5 accuracies ranging 11.0 to 13.3.

(https://tianchi.aliyun.com/competition/information.htm?raceId=231596&_lang=en_US)

"Short-term precipitation forecasting such as rainfall prediction is a task to predict a short-term rainfall amount based on current observations. It has been a very important problem in the field of meteorological service. An accurate weather prediction service can support casual usages such as outdoor activity and even provide early warnings of floods or traffic accidents. To predict short-term rainfall amount, we usually make use of radar data, rain gauge data and numerical weather outputs. In this challenge, we focus on the first type of data - radar data, more specifically radar echo extrapolation data. Our target is to build a rainfall prediction model by solely using the radar data."



