# Image Sorting

This is a course project of Signal and System of Department of EE., Tsinghua University. The main topic is to sort out of order images (frames from news scene). There are two subtasks: indoor scene sorting and outdoor scenes sorting. 

Indoor scene sorting needs to pick indoor scenes out of all images and put them in order. There is only one scene in indoor images so it's respectively easier.

Outdoor scenes sorting needs to put the rest images in order. Outdoor images includes mutliple scenes, so the key point is how to put scenes in order after sorting images in every scene. More details can be found in ```report.pdf```.

### File list

- ```report.pdf```: the technical report of this project.
- ```OpenCV_config.pdf```: the document of configuring OpenCV in Visual Studio. If you are using other compilers, you can ignore this.
- ```src/indoor_scene_sorting```: indoor scene sorting source code, ```main.cpp``` is the main function.
- ```src/outdoor_scene_sorting```: outdoor scenes sorting source code, ```main.cpp``` is the main function.

### Dependencies

- [OpenCV 2.4.x](https://www.opencv.org)
- Visual Studio 2012 (Since there are only source codes, you can try it with any compiler)
