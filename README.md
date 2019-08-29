# UCL_project
To run the ORB-SLAM codes, first, the ORB-SLAM2 should be installed.
Then, the src and include folders in ORB-SLAM2 should be replaced by the folder2 here.

The main modified codes are ComputeKeyPointsOctTree() function in ORBextractor.cpp; ReconstructH() function in Initializer.cpp; And MonocularInitialization() function in Tracking.cpp. Other place also have some changed including the head files in include folder.

The ProjectTUM.yaml file should be used for runing SLAM. 

Also, here is also a example image. Because in the programe, there are some code control the extraction area. And the intrinsic parameters is also rely on the size of the image. Besides, the image should also process the brightness equalization(ALso in the UCL_project), otherwise the performance will not good.
