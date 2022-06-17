# VSA project Team 3 repository

## Milestone 1: Simple VSA and Jetson Nano Orientation

### Part A: Simple VSA (05.19.22 ~ 05.25.22)

* Run activity recognition model
    * [X] Pytorch (ONNX): ResNet34
    * [X] Pytorch (pre-trained): TSN [(colab link)](https://colab.research.google.com/github/open-mmlab/mmaction2/blob/master/demo/mmaction2_tutorial.ipynb)

* Run face recognition model
    * [X] Pytorch: MTCNN [(face-recogntion)](https://github.com/timesler/facenet-pytorch)

### Part B: Jestson Nano Orientation (05.26.22 ~ 06.02.22)

* Setup Jetson Nano
    * [X] Connecting Jetson Nano to WIFI.
    * [X] Attaching Raspberry Pi Camera to Jetson Nano.
    * [X] NVIDIA DLI course: [https://courses.nvidia.com/courses/course-v1:DLI+S-RX-02+V2/about](https://courses.nvidia.com/courses/course-v1:DLI+S-RX-02+V2/about)
    * [X] Running DL task on the Jetson Nano usin DeepStream.

## Milestone 2: Experiment with Transfer Learning (06.03.22 ~ 06.17.22)

* Transfer Learning
    * [X] Baseline: [https://github.com/kenshohara/3D-ResNets-PyTorch](https://github.com/kenshohara/3D-ResNets-PyTorch)
    * [X] Choose Model: 3D ResNets for Action Recognition
    * [X] Dataset: [UCF-101](https://www.crcv.ucf.edu/data/UCF101.php)
    * [X] Transfer Learning with UCF-101

* Setting up TAO (Train, Adapt, and Optimize)
    * [X] Environment Setup: [https://docs.nvidia.com/tao/tao-toolkit/text/tao_toolkit_quick_start_guide.html](https://docs.nvidia.com/tao/tao-toolkit/text/tao_toolkit_quick_start_guide.html)
    * [X] Dataset: [UCF-101](https://www.crcv.ucf.edu/data/UCF101.php)
    * [X] Data Preprocessing: [https://github.com/NVIDIA-AI-IOT/tao_toolkit_recipes](https://github.com/NVIDIA-AI-IOT/tao_toolkit_recipes)
    * [X] Transfer Learning with TAO for action recognition [link](https://developer.nvidia.com/blog/developing-and-deploying-your-custom-action-recognition-application-without-any-ai-expertise-using-tao-and-deepstream/)