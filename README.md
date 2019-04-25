# 3D Object Detection for Indoor Scenes

## Introduction
The semantic understanding of the scene is expected to be very useful in many domains. In this work, we propose a method for indoor scene semantic segmentation and bounding box extraction. Instead of using raw 2D RGB and depth image as input like traditional methods. We combine the point cloud representation with the RGB-depth image and train the network directly using point cloud. Our method can produce semantic segmentation or instance bounding box with high accuracy and good efficiency. 

## Usage

### 1. Prepare the dataset

Download <a href="http://rgbd.cs.princeton.edu">SUNRGBD V1 dataset</a>. 

Using the data preprocessing script in the data folder to prepare the pickle file for training.

### 2. Training

Run 
```
python train.py --model YOURMODELNAME
```

### 3. Testing

Run the following script for testing.
```
python evaluate.py
```

### 4.visualization:
Run the following command to visualize the result:
```
python viz.py --data_path val_1002.zip.pickle --result_path test_results.pickle --viz
```

## Reference:

* <a href="http://stanford.edu/~rqi/pointnet" target="_blank">PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation</a> by Qi et al. (CVPR 2017 Oral Presentation). 
* <a href="http://stanford.edu/~rqi/pointnet2" target="_black">PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space</a> by Qi et al. (NIPS 2017).
