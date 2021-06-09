# tf_data_nuscenes

## Prepare Nuscenes Dataset
1. Download the v1.0-mini dataset from "https://www.nuscenes.org" -> download (need to create a login before downloading dataset)

![image](https://user-images.githubusercontent.com/63090360/121436869-532d2900-c94f-11eb-8f6a-3cc0a9207767.png)

2. Unzip the dataset to the required folder. 

## Prepare virtual environment 
1. python3 -m venv --system-site-packages ./venv_1
2. source ./venv_1/bin/activate
3. pip install --upgrade pip
4. pip install nuscenes-devkit # install nuscenes-devkit from "https://github.com/nutonomy/nuscenes-devkit"
5. pip install tensorflow

## nuScenes data-format
https://www.nuscenes.org/nuscenes#data-format

## Running the program
1. Change the 'dataroot' to your v1.0-mini's root in the tf_dataset_loader.py
2. python tf_dataset_loader.py
