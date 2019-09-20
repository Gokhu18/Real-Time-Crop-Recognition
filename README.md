# Real-time crop recognition in transplanted fields with prominent weed growth: a visual-attention-based approach

## Dateset

you can download our dataset with the resolution of 400x300[here](https://pan.baidu.com/s/1FloZQhICkibRxh-2GJTwyg
)and with the resolution of 512x384[here](https://pan.baidu.com/s/1CPi_BXXDQiOiryMDegZz8Q
)

## Usage

Please install Tensorflow and required packages first

### Download our code.

```python
git clone https://github.com/ZhangXG001/Real-Time-Crop-Recognition.git
```

### Download the dataset with the resolution of 400x300(as for dataset with the resolution of 512x384,you should rename dataset folder "dataset1" to "dataset" first) and directly put them under the folder"Real-Time-Crop-Recognition-master".

You can run ``` .../python csv_generator.py ```to create .csv files of dataset(already existed under the folder"Real-Time-Crop-Recognition-master" for our dataset).


### Train

If you want to train the model,you can run

```python
cd .../Real-Time-Crop-Recognition-master
python train-aaf.py
```
You can get the well-trained model under the folder"model".

### Test

If you want to test the model,you can run

```python
python test.py
```
You can get the test result under the folder"result".

About the CRF code we used, you can find it [here](https://github.com/Andrew-Qibin/dss_crf). Notice that please provide a link to the original code as a footnote or a citation if you plan to use it.

## Citation

If you think this work is helpful, please cite

Nan Li, Xiaoguang Zhang,Chunlong Zhang,Huiwen Guo,Zhe Sun, and Xinyu Wu."Real-time crop recognition in transplanted fields with prominent weed growth: a visual-attention-based approach."IEEE Access, 2019, Early Access, DOI:10.1109/ACCESS.2019.2942158


## Acknowledgements

We would like to especially thank GaoBin（[github](https://github.com/gbyy422990/salience_object_detection)）,QiBin（[github](https://github.com/Andrew-Qibin/DSS)) and Ke([github](https://github.com/twke18/Adaptive_Affinity_Fields)) for the use of part of their code.
