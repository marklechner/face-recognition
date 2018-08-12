# face-recognition
Face recognition with OpenCV, Python, and deep learning - based on pyimagesearch tutorial

## reference
This test is based on the tutorial provided by [pyimagesearch]

## setup
  - Did not enable CUDA while installing dlib - used "hog" detection model at both encoding and recognition
  - Used custom image dataset and samples for both encoding and runing the recognition piece
  - modified the resulting image via cv2.resize and adjusted the rectangles

## run
```sh
$ ./encode_faces.py --dataset dataset --encodings encodings.pickle -d hog
$ ./recognize_faces_image.py --encodings encodings.pickle --image examples/one.JPG -d hog
```

[pyimagesearch]: https://www.pyimagesearch.com/2018/06/18/face-recognition-with-opencv-python-and-deep-learning/
