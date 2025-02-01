# **Short-term wind power forecasting using integrated boosting approach**
## Abstract
Rapidly increasing global energy demand and environmental concerns have shifted the attention of policymakers toward the large-scale integration of renewable energy resources (RERs). Wind energy is a type of RERs with vast energy potential and no environmental pollution is associated with it. The sustainable development goals: affordable and clean energy, climate action, and industry, innovation and infrastructure, can be achieved by integrating wind energy into the existing power systems. However, the integration of wind energy will bring instability challenges due to its intermittent nature. Mitigating these challenges necessitates the implementation of effective wind power forecasting models. Therefore, we have proposed a novel integrated approach, Boost-LR, for hour-ahead wind power forecasting. The Boost-LR is a multilevel technique consisting of non-parametric models, extreme gradient boosting (XgBoost), categorical boosting (CatBoost), and random forest (RF), and parametric approach, linear regression (LR). The first layer of the Boost-LR uses the boosting algorithms that process the data according to their tree development architectures and pass their intermediary forecast to LR which is deployed in layer two and processes the intermediary forecasts of layer one models to provide the final predicted wind power. To demonstrate the generalizability and robustness of the proposed study, the performance of Boost-LR is compared with the individual models of CatBoost, XgBoost, RF, deep learning networks: long short-term memory (LSTM) and gated recurrent unit (GRU), Transformer and Informer models using root mean square error (RMSE) mean square error (MSE), mean absolute error (MAE) and normalized root mean square error (NRMSE). Findings demonstrate the effectiveness of the Boost-LR as its forecasting performance is superior to the compared models. The improvement in MAE of Boost-LR is recorded as to be 31.42%, 32.14%, and 27.55% for the datasets of Bruska, Jelinak, and Inland wind farm, respectively as compared to the MAE of CatBoost which is revealed as the second-best performing model. Moreover, the proposed study also reports a literature comparison that further validates the effectiveness of Boost-LR performance for short-term wind power forecasting.
## Image

![Boost-LR](image.png)
# Getting Started
Follow the steps below to set up and run the code for short-term global horizontal irradiance forecasting.

## Prerequisites
Ensure you have the following software installed:<br>
- Python 3.10.9 or above<br>

Required libraries: <br>
 -  NumPy<br>
 -  Pandas<br>
 -  Scikit-learn<br>
 -  CatBoost<br>
 -  XgBoost<br>
 -  Matplotlib<br>
 -  Seaborn<br>
 -  TensorFlow<br>
 -  Keras<br>
 -  RandomForest<br>

# Running the Code
- Run the Boost-LR.ipynb script to simulate the proposed technique.<br>
- Run LSTM.ipynb, GRU.ipynb, catoost.ipynb, xgboost.ipynb, rf.ipynb and informer.ipynb scripts comparative analysis.<br>
- Run the bar_plot.ipynb, and graph.ipynb scripts to visualize the forecasting results and compare the model's performance.<br>


BoostLR-Wind-Power-Forecasting/ <br>
├── Datasets/                   # Folder for datasets <br>
├── Models/                     # Folder containing scripts for model training and evaluation <br>
├── Graphs                      # Folder containing scripts for result visualization <br>
├── README.md                   # Project README file <br>

## Reference
Please cite this work as:
@ARTICLE{10.3389/fenrg.2024.1401978,
AUTHOR={Ahmed, Ubaid  and Muhammad, Rasheed  and Abbas, Syed Sami  and Aziz, Imran  and Mahmood, Anzar },
TITLE={Short-term wind power forecasting using integrated boosting approach},
JOURNAL={Frontiers in Energy Research},
VOLUME={12},
YEAR={2024},
URL={https://www.frontiersin.org/journals/energy-research/articles/10.3389/fenrg.2024.1401978},
DOI={10.3389/fenrg.2024.1401978},
ISSN={2296-598X}}
