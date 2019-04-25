# 3D Object Detection for Indoor Scenes

## Introduction
The semantic understanding of the scene is expected to be very useful in many domains. In this work, we propose a method for indoor scene semantic segmentation and bounding box extraction. Instead of using raw 2D RGB and depth image as input like traditional methods. We combine the point cloud representation with the RGB-depth image and train the network directly using point cloud. Our method can produce semantic segmentation or instance bounding box with high accuracy and good efficiency. 

## Usage

### 1. Prepare the dataset

Download <a href="http://rgbd.cs.princeton.edu">SUNRGBD V1 dataset</a>. 

### 2. Training
Run train_one_hot.py.

### 3. Testing

## Reference:


[1] Qi, Charles R., et al. "Pointnet: Deep learning on point sets for 3d classification and segmentation." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2017.

[2] Qi, Charles Ruizhongtai, et al. "Pointnet++: Deep hierarchical feature learning on point sets in a metric space." Advances in Neural Information Processing Systems. 2017.

[3] Song, Shuran, and Jianxiong Xiao. "Deep sliding shapes for amodal 3d object detection in rgb-d images." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2016.

[4] Dai, Angela, et al. "Scannet: Richly-annotated 3d reconstructions of indoor scenes." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2017.

[5] Song, Shuran, Samuel P. Lichtenberg, and Jianxiong Xiao. "Sun rgb-d: A rgb-d scene understanding benchmark suite." Proceedings of the IEEE conference on computer vision and pattern recognition. 2015.

[6] He, Kaiming, et al. "Mask r-cnn." Proceedings of the IEEE international conference on computer vision. 2017.

[7] Qi, Charles R., et al. "Frustum pointnets for 3d object detection from rgb-d data." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2018.

[8] Wu, Zhirong, et al. "3d shapenets: A deep representation for volumetric shapes." Proceedings of the IEEE conference on computer vision and pattern recognition. 2015.

[9] Su, Hang, et al. "Multi-view convolutional neural networks for 3d shape recognition." Proceedings of the IEEE international conference on computer vision. 2015.

[10] Song, Shuran, and Jianxiong Xiao. "Deep sliding shapes for amodal 3d object detection in rgb-d images." Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2016.

[11] D. Z. Wang and I. Posner. Voting for voting in online point cloud object detection. Proceedings of the Robotics: Science and Systems, Rome, Italy, 1317, 2015.

[12] Ren, Shaoqing, et al. "Faster r-cnn: Towards real-time object detection with region proposal networks." Advances in neural information processing systems. 2015.