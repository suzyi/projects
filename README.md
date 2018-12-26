# projects
It's Oct 5, 2018, Friday evening. I begin to make some projects to ensure I have something to talk about in future job hunting.
### Hand-writting digits recognition
I know how to achive digits recognition using Tensorflow on python. However, for real application, you got to make it work on your hand phone, with camera scan the digits on a paper and it can be recognized on your android phone.
### color transformation
color transformation to make photo look like old or artistic, e.g. [projects here](https://github.com/PacktPublishing/OpenCV-Computer-Vision-Projects-with-Python).
### face detection
Refer to [ageitgey's face recognition project](https://github.com/ageitgey/face_recognition). For tensorflow-based face detection tutorial, please refer to [tensorflow/model](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/running_pets.md). and [tensorflow/models/tree/master/research/object_detection](https://github.com/tensorflow/models/tree/master/research/object_detection).
+ [official quick start examples](https://github.com/tensorflow/models/blob/master/research/object_detection/object_detection_tutorial.ipynb). Unable to run in my single-gpu (geForce 1050 ti, 4GB) equiped computer, but a single geForce 1080 (with a memory of 8GB) is capable of running this program. However, by preventing tensorflow from using GPU, the computer has enough memory to support running the code.
+ [intro and tutorial](https://www.kdnuggets.com/2018/03/google-tensorflow-object-detection-api-the-easiest-way-implement-image-recognition.html) to tensorflow's object detection API, which is much easier than official guide described in last item. And the author's [video-based object detection](https://github.com/priya-dwivedi/Deep-Learning/blob/master/Object_Detection_Tensorflow_API.ipynb).
+ for many pre- and well-trained cocodataset-based model, see [here](https://github.com/tensorflow/models/blob/477ed41e7e4e8a8443bc633846eb01e2182dc68a/object_detection/g3doc/detection_model_zoo.md) for their information.
+ running well-trained model on android. [running_on_mobile_tensorflowlite](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/running_on_mobile_tensorflowlite.md)
+ A complete project should satisfy: First, could be installed on ubuntu and be called by python. Second, coulded be installed on android.
### counting the numbers of people in a given pictures (done at Dec 19, 2018.)
+ Refer to [Xiongfeng's ICML-2017 paper]
+ [github-implementaion](https://github.com/ahmetozlu/tensorflow_object_counting_api) using TensorFlow Object Counting API. Concretely, [tf-based vehicle counting](https://github.com/ahmetozlu/vehicle_counting_tensorflow).
+ [counting target object "person" in a given picture](https://github.com/ahmetozlu/tensorflow_object_counting_api/blob/master/real_time_counting_targeted_object.py)
+ One should note that the definition of `visualize_boxes_and_labels_on_image_array` is quite different between [official's](https://github.com/tensorflow/models/blob/master/research/object_detection/utils/visualization_utils.py) and [ahmetozlu's](https://github.com/ahmetozlu/tensorflow_object_counting_api/blob/master/utils/visualization_utils.py) such as the later has the input attribute of "targeted_objects".
### Play Breakout games
+ [Tensorflow deep q-learning of Breakout game](https://github.com/devsisters/DQN-tensorflow)
+ [Deepmind's code]() and [paper](https://www.nature.com/articles/nature14236)
### lasso solver (Dec 26, 108 - )
This project should be designed to implement lasso solver via sub-gradient descent.
