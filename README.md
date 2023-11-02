Multi-View 3D Human Pose Estimation
=============

#### - Multi-view 3d human pose estimation

  - A computer vision task that aims to estimate the three-dimensional pose of a human subject from multiple camera views
  - This task is essential in various applications, such as motion capture, human-computer interaction, virtual reality, and surveillance
  - Camera Calibration, Epipolar Geometry, Triangulation, GCN, Volumetric Representation, Direct Regression methods etc are mainly used.

#### - Backgrounds

  - 3D Human Pose Estimation: The term "pose" refers to the spatial configuration of a human body, including the positions and orientations of body parts (e.g., joints and limbs). 3D pose estimation seeks to infer the three-dimensional coordinates of these body parts in a common reference frame.

  - Multi-View Approach: Multi-view 3D human pose estimation leverages multiple cameras or viewpoints to capture a person from different angles. Each camera provides a 2D projection of the person, and by combining these projections, the 3D pose can be estimated. Using multiple views helps mitigate ambiguities and occlusions present in a single view.

  - [Camera Calibration](https://github.com/qbxlvnf11/camera-calibration): To estimate 3D pose accurately, it's crucial to know the intrinsic and extrinsic parameters of each camera, which is known as camera calibration. Intrinsic parameters include focal length, principal point, and lens distortion, while extrinsic parameters specify the camera's position and orientation in 3D space.

  - Multi-View Geometry: Techniques from multi-view geometry, such as epipolar geometry, essential matrices, and fundamental matrices, are often employed to establish correspondences between 2D points in different camera views. These correspondences help in triangulating 3D points.

  - Joint Detection: The first step in multi-view 3D pose estimation is to detect and localize the body joints or key points in 2D for each camera view. These 2D keypoints can be detected using techniques like Convolutional Neural Networks (CNNs), which are trained on labeled data.

  - Triangulation: Once the 2D keypoints are detected in multiple views, triangulation is used to estimate the 3D positions of these keypoints in a common world coordinate system. Triangulation calculates the intersection point of the rays originating from the camera centers and passing through the corresponding 2D keypoints.

  - Pose Optimization: Multi-view 3D pose estimation often involves optimization techniques to refine the estimated 3D pose. This can include minimizing the reprojection error, which measures the difference between the projected 3D points and the detected 2D keypoints.

  - Challenges: Multi-view 3D human pose estimation is challenging due to occlusions, self-occlusions, lighting variations, and the need for accurate camera calibration. Additionally, handling cases where cameras have limited or non-overlapping views is more complex.

#### - Goals of this repository
  - Various multi-view 3d human pose estimation methods implementation/test/customization etc.


Model List
=============

#### - Faster-VoxelPose

```
@article{Faster-VoxelPose,
  title={Faster VoxelPose: Real-time 3D Human Pose Estimation by Orthographic Projection},
  author={Hang Ye, Wentao Zhu, Chunyu Wang, Rujie Wu, Yizhou Wang},
  journal = {ECCV, 2022},
  year={2022}
}
```

#### - VoxelPose

```
@article{VoxelPose,
  title={VoxelPose: Towards Multi-Camera 3D Human Pose Estimation in Wild Environment},
  author={Hanyue Tu, Chunyu Wang, Wenjun Zeng},
  journal = {ECCV, 2020},
  year={2020}
}
```

#### - Multi-view Pose Transformer (MvP)

```
@article{MvP,
  title={Direct Multi-view Multi-person 3D Pose Estimation},
  author={Tao Wang, Jianfeng Zhang, Yujun Cai, Shuicheng Yan, Jiashi Feng},
  journal = {NIPS, 2021},
  year={2021}
}
```

#### - PlaneSweepPose

```
@article{PlaneSweepPose,
  title={Multi-View Multi-Person 3D Pose Estimation with Plane Sweep Stereo},
  author={Jiahao Lin, Gim Hee Lee},
  journal = {CVPR, 2021},
  year={2021}
}
```

#### - GCNs-Based Multi-View 3D Human Pose Estimation

```
@article{GCNs-Based Multi-View 3D Human Pose Estimation,
  title={Graph-Based 3D Multi-Person Pose Estimation Using Multi-View Images},
  author={Size Wu, Sheng Jin, Wentao Liu, Lei Bai, Chen Qian, Dong Liu, Wanli Ouyang},
  journal = {ICCV, 2021},
  year={2021}
}
```


Datasets
=============

#### - Panoptic

#### - Shelf

#### - Campus
