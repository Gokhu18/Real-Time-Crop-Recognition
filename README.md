# Real-time crop recognition in transplanted fields with prominent weed growth: a visual-attention-based approach

## Dateset

you can download our dataset [here](https://pan.baidu.com/s/1gH1X_FXsP8ah2ehKGBiSOg)

## Usage

Please install Tensorflow and required package first

1.Download our code.

```python
git clone https://github.com/ZhangXG001/Real-Time-Crop-Recognition.git
```

2.Download the dataset and put them under the folder"Real-Time-Crop-Recognition".

You can run ``` python csv_generator.py ```to create .csv files of dataset(already existed in the folder"Real-Time-Crop-Recognition" for our dataset).


### Train

If you want to train the model,you can run

```python
cd .../Real Time Crop Recognition
python train.py
```
You can get the well-trained model in the folder"model".

### Test

If you want to test the model,you can run

```python
python test.py
```
You can get the test result in the folder"result".

About the CRF code we used, you can find it [here](https://github.com/Andrew-Qibin/dss_crf). Notice that please provide a link to the original code as a footnote or a citation if you plan to use it.

### Citation

If you think this work is helpful, please cite

NAN LI,XIAOGUANG ZHANG,CHUNLONG ZHANG,HUIWEN GUO,ZHE SUN,AND XINYU WU."Real-time crop recognition in transplanted fields with prominent weed growth: a visual-attention-based approach."IEEE ACESS.will be published in the future.

### Acknowledgements

We would like to especially thank GaoBin（[github](https://github.com/gbyy422990/salience_object_detection)）,QiBin（[github](https://github.com/Andrew-Qibin/DSS)) and Ke([github](https://github.com/twke18/Adaptive_Affinity_Fields)) for the use of part of their code.
