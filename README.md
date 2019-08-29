# UCL_project_SLAMPART
These github folders includes the all codes in ORB-SLAM system. To make the code indictaion clear, the MATLAB code including the pre-processing method and trajectory alignment is shown in other github link.

To run the codes, first, the ORB-SLAM2 should be installed.
Then, the src and include folders in ORB-SLAM2 should be replaced by the folder2 here.

The main modified codes are ComputeKeyPointsOctTree() function in ORBextractor.cpp; ReconstructH() function in Initializer.cpp; And MonocularInitialization() function in Tracking.cpp. Other places including the source-files and head-files also have some changes.

The ProjectTUM.yaml file should be used for runing SLAM. 

Also, here is also a example image. Because in the programe, there are some code control the extraction area. And the intrinsic parameters is also rely on the size of the image. The size changing code is in the github which contains all Matlab codes. Besides, the image should also process the brightness equalization(also shown in another github link), otherwise the performance will not good.
