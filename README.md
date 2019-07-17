# Safety_inspection 工地工人穿戴服装和安全帽检测-跟踪
Thanks for these projects, this work now is support tiny_yolo v3 but only for test, if you want to train you can either train a model in darknet or in the second following works. It also can tracks many objects in coco classes, so please note to modify the classes in yolo.py. besides, you also can use camera for testing.

  https://github.com/nwojke/deep_sort
  
  https://github.com/qqwweee/keras-yolo3
  
  https://github.com/Qidian213/deep_sort_yolov3
  
  # Download
  Download YOLOv3 or tiny_yolov3 weights from [YOLO website](http://pjreddie.com/darknet/yolo/).Then convert the Darknet YOLO model to a Keras model. 
  Or use what i had converted https://drive.google.com/file/d/1uvXFacPnrSMw6ldWTyLLjGLETlEsUvcE/view?usp=sharing (yolo.h5 model file with tf-1.4.0) , put it into model_data folder

  # Dependencies
  The code is compatible with Python 2.7 and 3. The following dependencies are needed to run the tracker:

    NumPy
    sklean
    OpenCV
    Pillow

  Additionally, feature generation requires TensorFlow-1.4.0.
  
  # Note 

  Model file model_data/mars-small128.pb need by deep_sort had convert to tensorflow-1.4.0
