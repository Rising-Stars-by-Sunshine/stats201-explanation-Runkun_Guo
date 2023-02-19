# PS2: Explanation
## Table of Contents

| Contents| URL |
| :---         |     :---     |
| Data | https://github.com/Rising-Stars-by-Sunshine/stats201-explanation-Haowen/tree/main/data |
| Code | https://github.com/Rising-Stars-by-Sunshine/stats201-explanation-Haowen/tree/main/code |
| Spotlight | https://github.com/Rising-Stars-by-Sunshine/stats201-explanation-Haowen/tree/main/spotlight |

## Data
### Data Source: 
- [Collected Data](https://github.com/Rising-Stars-by-Sunshine/stats201-explanation-Haowen/blob/main/data/references.csv)

### Meta Data Information
| Data files| Data Content | Type|
| :---         |     :---     | :---: |
|references.csv| Literatures collected to do the explanation | collected data |

### Data Dictionary 
| variable name | description | frequency     |  unit.    | range| type|
| :---         |     :---     |          ---: |---:        |---: |---: |
| Item type | Represents the type of the collected literature |\|\|\|Object|
| Titles | Contains the authors of the collected lieratures |\|\|\|Object|
| Titles | Contains the titles of the collected lieratures |\|\|\|Object|
| Abstract | Contains the abstracts of the collected lieratures |\|\|\|Object|



## Code
- [Query Ethereum Data](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/blob/main/code/Query_Data_Ethereum_Data.ipynb)
- [Process Regression Data](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/blob/main/code/Process_Data_Prepare_X_and_Y_for_Regressions.ipynb)
- [Analyze Data](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/blob/main/code/Analyze_Data_Machine_Learning_for_Predicting.ipynb)
### Table of Code
| Code files| Description | Type|
| :---         |     :---:     | ---: |
| Query_Data_Ethereum_Data.ipynb  | This code deals with the read and preprocessing of the original dataset | .ipynb |
| Process_Data_Prepare_X_and_Y_for_Regressions.ipynb | This code processed the X and Y dataset from Ethereum_value.csv for regression  | .ipynb |
| Analyze_Data_Machine_Learning_for_Predicting.ipynb | This code applied machine learning method for open price regression| .ipynb |

## Spotlight
![image](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/blob/main/spotlight/figures/Linear_Regression_Result.png)
*Figure 1: The prediction result of ethereum open price by linear regression*
- [Code source](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/blob/main/code/Analyze_Data_Machine_Learning_for_Predicting.ipynb)
- [Data source](https://github.com/Rising-Stars-by-Sunshine/stats201-prediction-Haowen/tree/main/data/Processed_data)
- Description: from figure 1, it is obvious that the predicted result is very close to the real open price value. The result is evaluated by R2 score, which is 0.984. The R-squre determines the proportion of variance, which shows how well the data fit the regression mode(Chicco, Warrens, and Jurman 2021). The closer the r-squared value is to 1, the better the fit. Thus, the linear regression reached a high accuracy regarding the r-squared value.

# References

## Data Source
- [Ethereum Historical Dataset](https://www.kaggle.com/datasets/abhimaneukj/ethereum-historical-dataset)
## Code Source
- [Rising-Stars-by-Sunshine/stats201-tutorial-prediction](https://github.com/Rising-Stars-by-Sunshine/stats201-tutorial-prediction/tree/main/code)
## Literature

Chen, Zhengmao, Dongyue Guo, and Yi Lin. 2020. “A Deep Gaussian Process-Based Flight Trajectory Prediction Approach and Its Application on Conflict Detection.” Algorithms 13 (11): 293. https://doi.org/10.3390/a13110293.

Ghosh, Indranil, Esteban Alfaro-Cortés, Matías Gámez, and Noelia García. 2023. “Prediction and Interpretation of Daily NFT and DeFi Prices Dynamics: Inspection through Ensemble Machine Learning & XAI.” International Review of Financial Analysis, February, 102558. https://doi.org/10.1016/j.irfa.2023.102558.

Kireyev, Pavel. 2022. “NFT Marketplace Design and Market Intelligence.” SSRN Electronic Journal. https://doi.org/10.2139/ssrn.4002303.

Ko, Hyungjin, Bumho Son, Yunyoung Lee, Huisu Jang, and Jaewook Lee. 2022. “The Economic Value of NFT: Evidence from a Portfolio Analysis Using Mean–Variance Framework.” Finance Research Letters 47 (June): 102784. https://doi.org/10.1016/j.frl.2022.102784.

Nadini, Matthieu, Laura Alessandretti, Flavio Di Giacinto, Mauro Martino, Luca Maria Aiello, and Andrea Baronchelli. 2021. “Mapping the NFT Revolution: Market Trends, Trade Networks, and Visual Features.” Scientific Reports 11 (1). https://doi.org/10.1038/s41598-021-00053-8.

Rai, Rishi Deo, Janmaijay, Chintu Kumar, and Asst. Prof. Kajol Dahiya. 2023. “Blockchain and NFT-Based Decentralize Version of Social Media.” International Journal for Research in Applied Science and Engineering Technology 11 (1): 722–26. https://doi.org/10.22214/ijraset.2023.48681.

Urom, Christian, Gideon Ndubuisi, and Khaled Guesmi. 2022. “Dynamic Dependence and Predictability between Volume and Return of Non-Fungible Tokens (NFTs): The Roles of Market Factors and Geopolitical Risks.” Finance Research Letters 50 (December): 103188. https://doi.org/10.1016/j.frl.2022.103188.

Yousaf, Imran, and Larisa Yarovaya. 2022. “Static and Dynamic Connectedness between NFTs, Defi and Other Assets: Portfolio Implication.” Global Finance Journal 53 (August): 100719. https://doi.org/10.1016/j.gfj.2022.100719.

Zhu, Huiming, Yiwen Chen, Yinghua Ren, Zhanming Xing, and Liya Hau. 2022. “Time-Frequency Causality and Dependence Structure between Crude Oil, EPU and Chinese Industry Stock: Evidence from Multiscale Quantile Perspectives.” The North American Journal of Economics and Finance 61 (July): 101698. https://doi.org/10.1016/j.najef.2022.101698.

Zhang, Luyao (Sunshine). 2022. “Machine Learning for Predictions.” Machine Learning for Social Science, November. https://ms.pubpub.org/pub/ml-prediction/release/4.
