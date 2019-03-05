# Machine Learning Engineer Nanodegree Capstone Project
## Gender classification

## [Project report](https://github.com/magdy-hasan/Machine-Learning-Engineer-Nanodegree-Program/blob/master/Capstone%20Project/report.pdf)

## How to use:
- Download the dataset from [here](https://www.openu.ac.il/home/hassner/Adience/data.html), the "aligned.tar.gz" file
- untar the file, images will be extracte to aligned folder
- labels are in txt from fold_0_data.txt to fold_4_data.txt, i mereged all of them into one txt file
- First run "pre_data.ipynb" to load data from text 
- "benchmark.ipynb" is the benchmark model i used
- Then run "pre_data_inc2.ipynb" to extract features from InceptionResNetV2 pretrained model ( "pre_data_v16.ipynb" use VGG16 model )
- Then run "i2_train.ipynb" to train the model ( again "v16_train.ipynb" uses VGG16 as pretrained model )
- I managed to get 0.889 validation accuracy with InceptionResNetV2
