# Opencv-prebuilt-with-extra-modules
As OpenCV does not comes with extra modules like face recognition,etc we need to built them which takes lots of time .This repository will have the whole library ready to use for python (Opencv 3.2 dev)
**Install instructions :-**
1) Extract the DLLs folder in c:\Python27\ or the root directory of python
2) copy cv.pyd file in Python27\Lib\site-packages\
3) You are ready to go with Opencv 3.2 dev version, import cv2 and check whether its working or not.

    import cv2
    print cv2.__version__
