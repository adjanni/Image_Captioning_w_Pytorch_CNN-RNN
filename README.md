# Image_Captioning_w_Pytorch_CNN-RNN (on going)
In this project, I create a neural network architecture to automatically generate captions from images.  After using the Microsoft Common Objects in COntext (MS COCO) dataset to train your network, I test my network on novel images!

## Step 1 - Installation of pycocotools
There are lot of threads where users faced isues installing pycocotools [for example](https://github.com/cocodataset/cocoapi/issues/272)

You should note that pycocotools requires Visual C++ 2019 Build Tools (the latest version at the time I am writing this).

1. visit this [page](https://visualstudio.microsoft.com/downloads/). Then scroll down to "Tools for Visual Studio 2019" and download "Build Tools for Visual Studio 2019". Follow the installation procedure and it should be about 4.1 GB.

2. Clone this repository: `git clone https://github.com/cocodataset/cocoapi.git`

3. Use pip to install pycocotools: `pip install git+https://github.com/cocodataset/cocoapi.git#subdirectory=PythonAPI`

4. If done properly, you should see "pycocotools-2.0".

5. It should work!!!

