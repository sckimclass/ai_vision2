# ai_vision2

1. Python 및 Colab 입문
https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l01c01_introduction_to_colab_and_python.ipynb

2. 섭씨를 화씨로 변환
https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l02c01_celsius_to_fahrenheit.ipynb

3. 패션 MNIST
https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l03c01_classifying_images_of_clothing.ipynb

4. CNN과 함께하는 패션 MNIST
https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l04c01_image_classification_with_cnns.ipynb

5. 고양이와 개
https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l05c01_dogs_vs_cats_without_augmentation.ipynb

6. 전이 학습이 있는 고양이와 개
https://colab.research.google.com/github/tensorflow/examples/blob/master/courses/udacity_intro_to_tensorflow_for_deep_learning/l06c01_tensorflow_hub_and_transfer_learning.ipynb


pip3 install https://dl.google.com/coral/python/tflite_runtime-2.1.0.post1-cp37-cp37m-linux_armv7l.whl


$ wget https://video.udacity-data.com/topher/2019/September/5d8e6a5f_image-classification/image-classification.zip

$ unzip image-classification.zip

$ cd image-classification

$ wget https://storage.googleapis.com/download.tensorflow.org/models/tflite/mobilenet_v1_1.0_224_quant_and_labels.zip

$ unzip mobilenet_v1_1.0_224_quant_and_labels

$ ls -l

total 7204
-rwxr-xr-x 1 pi pi    2396 Aug  6  2019 classify.py
-rw-r--r-- 1 pi pi   10484 Feb 27  2019 labels_mobilenet_quant_v1_224.txt
drwxrwxr-x 2 pi pi    4096 Feb 27  2019 __MACOSX
-rw-r--r-- 1 pi pi 3069250 Feb 27  2019 mobilenet_v1_1.0_224_quant_and_labels.zip
-rw-r--r-- 1 pi pi 4276352 Aug  3  2018 mobilenet_v1_1.0_224_quant.tflite
