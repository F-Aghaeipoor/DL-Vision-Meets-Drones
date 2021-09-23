# Vision Meets Drones
<p><br>
<div>
<img src="https://github.com/F-Aghaeipoor/DL-Vision-Meets-Drones/blob/master/Sources/1.png" />
</div>
<p><br>
  
The VisDrone2021 dataset is collected by the AISKYEYE team at Lab of Machine Learning and Data Mining , Tianjin University, China. The benchmark dataset consists of 400 video clips formed by 265,228 frames and 10,209 static images, captured by various drone-mounted cameras, covering a wide range of aspects including location (taken from 14 different cities separated by thousands of kilometers in China), environment (urban and country), objects (pedestrian, vehicles, bicycles, etc.), and density (sparse and crowded scenes). 
  
Note that, the dataset was collected using various drone platforms (i.e., drones with different models), in different scenarios, and under various weather and lighting conditions. These frames are manually annotated with more than 2.6 million bounding boxes or points of targets of frequent interests, such as pedestrians, cars, bicycles, and tricycles. Some important attributes including scene visibility, object class and occlusion, are also provided for better data utilization.

The challenge mainly focuses on four tasks:

**Task 1:** object detection in images challenge. The task aims to detect objects of predefined categories (e.g., cars and pedestrians) from individual images taken from drones.

**Task 2:** object detection in videos challenge. The task is similar to Task 1, except that objects are required to be detected from videos.

**Task 3:** single-object tracking challenge. The task aims to estimate the state of a target, indicated in the first frame, in the subsequent video frames.

**Task 4:** multi-object tracking challenge. The task aims to recover the trajectories of objects in each video frame.

**Task 5:** crowd counting challenge. The task aims to to count persons in each video frame.
