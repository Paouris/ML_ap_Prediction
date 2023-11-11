# ML_ap_Prediction

The scope of the tool “ap_predictions” is to forecast the values of the ap geomagnetic index for the next 3, 6, 9, 12, 24, 48 and 72 hours. 
The development of the tool is based on the state-of-the-art machine learning algorithms and especially the Long-Short Term Memory (LSTM). 
The training of the model performed on historical data of the 3-hour time intervals of ap index (Jan 1996 – July 2017) and the validation of the tool is performed on unseen data (July 2017 – Nov 2022), i.e. data out of the training interval.

There is no standard set of metrics used by geomagnetic index predictive-model developers to benchmark their models (see e.g. Liemohn et al., 2018). 
Nonetheless, our goal is to provide the most complete validation analysis performed to date for the ap geomagnetic index. 
To accomplish this task, we implement a set of variables that are used by various researchers (see e.g. Paouris et al., 2021 and references there in). 
Furthermore, a very comprehensive analysis of the various metrics can be found in the work of Jolliffe and Stephenson (2012). 

Our validation analysis is based and is in agreement with the “Guidelines for common validation in the SSA SWE Network”.
