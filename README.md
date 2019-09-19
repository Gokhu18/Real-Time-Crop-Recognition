# Real-time crop recognition

## Dateset

you can download our dataset here(https://pan.baidu.com/s/1gH1X_FXsP8ah2ehKGBiSOg)

## Usage

Please install Tensorflow and required package first

1.Download our code.

```python
git clone https://github.com/ZhangXG001/Real-Time-Crop-Recognition.git
```

2.Download the dataset and put them under the folder"Real-Time-Crop-Recognition".

You can run ``` python train.py ```to create .csv file of dataset(already existed in the folder"Real-Time-Crop-Recognition" for our dataset).


### Train

If you want to train the model,you can run

```python
cd .../Real Time Crop Recognition
python train.py
```
You can find the trained model in the folder"model"

### test

If you want to test the model,you can run

```python
python test.py
```
You can find the test result in the folder"result"

