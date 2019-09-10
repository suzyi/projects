# Projects-Focus on Just One Thing: Face Detection, no playing games, no color transform etc.
It's Oct 5, 2018, Friday evening. I begin to make some projects to ensure I have something to talk about in future job hunting.
### face detection->视频人脸跟踪
Refer to [ageitgey's face recognition project](https://github.com/ageitgey/face_recognition). For tensorflow-based face detection tutorial, please refer to [tensorflow/model](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/running_pets.md). and [tensorflow/models/tree/master/research/object_detection](https://github.com/tensorflow/models/tree/master/research/object_detection).
+ [official quick start examples](https://github.com/tensorflow/models/blob/master/research/object_detection/object_detection_tutorial.ipynb). Unable to run in my single-gpu (geForce 1050 ti, 4GB) equiped computer, but a single geForce 1080 (with a memory of 8GB) is capable of running this program. However, by preventing tensorflow from using GPU, the computer has enough memory to support running the code.
+ [intro and tutorial](https://www.kdnuggets.com/2018/03/google-tensorflow-object-detection-api-the-easiest-way-implement-image-recognition.html) to tensorflow's object detection API, which is much easier than official guide described in last item. And the author's [video-based object detection](https://github.com/priya-dwivedi/Deep-Learning/blob/master/Object_Detection_Tensorflow_API.ipynb).
+ for many pre- and well-trained cocodataset-based model, see [here](https://github.com/tensorflow/models/blob/477ed41e7e4e8a8443bc633846eb01e2182dc68a/object_detection/g3doc/detection_model_zoo.md) for their information.
+ running well-trained model on android. [running_on_mobile_tensorflowlite](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/running_on_mobile_tensorflowlite.md)
+ A complete project should satisfy: First, could be installed on ubuntu and be called by python. Second, coulded be installed on android.
### counting the numbers of objects in a given picture
| Date | codes |
| ----- | ----- |
| Dec 19, 2018 | [Simple demo of object-counting using well-trained model](https://github.com/suzyi/projects/blob/master/object-counting/object-counting.ipynb) |
