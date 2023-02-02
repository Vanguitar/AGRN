# AGRN
Code for "An asynchronous gated recurrent network for estimating critical transition of bearing deterioration''

## Requirements
- Python version : 3.7
- cuda==10.0
- cudnn
- tensorflow-gpu==1.14.0
- keras

## Basic Usage
- In forecast.py, 80% of the dchi are used as training datasets and the rest as testing datasets without LOO.
- The author computed each result predicted by LOO due to a high volume of calculations and limited computer configuration, then assembled them.
