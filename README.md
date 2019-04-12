# YOLO object detection with OpenCV

Poject Structure:
<pre>
│
├── yolo-coco
│   ├── coco.names
│   ├── yolov3.cfg
│   └── yolov3.weights
│
├── output
│
└── pyolo.py
</pre>

While running the code you can pass Minimum probability of detection as *confidence* and non-maxima suppression threshold as *threshold*. However they have default values of 0.5 and 0.3 respectively.

If you provide an image path as *image* argument, the result will be saved in output folder.
Otherwise the code will use your webcam and its real-time stream.

The main idea is from a tutorial by **Adrian Rosebrock** and I got to know that thanks to my dear friend **Vahidreza**

[Link](https://www.pyimagesearch.com/2018/11/12/yolo-object-detection-with-opencv/) to tutorial.
[link](https://github.com/vrkh1996/yolo) to the repository.

You can also download the weights from this [link](https://pjreddie.com/media/files/yolov3.weights).

