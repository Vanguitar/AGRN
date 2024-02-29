# AGRN
Code for "An asynchronous gated recurrent network for estimating critical transition of bearing deterioration''

# Please cite this paper if the code is helpful
C. Li, Y. Wu, Y. Bai and S. Yang, "An Asynchronous Gated Recurrent Network for Estimating Critical Transition of Bearing Deterioration," in IEEE Transactions on Industrial Informatics, vol. 20, no. 2, pp. 1498-1507, Feb. 2024, doi: 10.1109/TII.2023.3278869.

# keywords
Feature extraction;
Logic gates;
Prognostics and health management;
Maintenance engineering;
Estimation;
Vibrations;
Degradation;
Asynchronous gated recursive network (AGRN);
bearing degradation;
critical transition;
feature extraction;
prognostics and health management (PHM).



## Requirements
- Python version : 3.7
- cuda==10.0
- cudnn
- tensorflow-gpu==1.14.0
- keras

## Basic Usage
* In forecast.py, 80% of the dchi are used as training datasets and the rest as testing datasets without LOO.

* The author computed each result predicted by LOO due to a high volume of calculations and limited computer configuration, then assembled them.

* You can find the mat file by Baidu Netdisk :
* link：https://pan.baidu.com/s/1HeqKi9x4SZvr9Mq_XLEB0g?pwd=mwq9 
* password：mwq9 
