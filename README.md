# YoloV4-ncnn-Raspberry-Pi-4
![output image]( https://qengineering.eu/images/Mumbai_YoloV4.jpg )

## YoloV4 with the ncnn framework. <br/><br/>
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)<br/><br/>
The frame rate is about 3 FPS (RPi 64 bit OS, overclocked to 1950 MHz)<br/>
Paper: https://arxiv.org/pdf/2004.10934.pdf <br/>
Size: 608x608 <br/><br/>
Special made for a bare Raspberry Pi see [Q-engineering deep learning examples](https://qengineering.eu/deep-learning-examples-on-raspberry-32-64-os.html) <br/>
## Dependencies.
To run the application, you have to:
- A raspberry Pi 4 with a 32 or 64-bit operating system. It can be the Raspberry 64-bit OS, or Ubuntu 18.04 / 20.04. [Install 64-bit OS](https://qengineering.eu/install-raspberry-64-os.html) <br/>
- The Tencent ncnn framework installed. [Install ncnn](https://qengineering.eu/install-ncnn-on-raspberry-pi-4.html) <br/>
- OpenCV 64 bit installed. [Install OpenCV 4.3](https://qengineering.eu/install-opencv-4.3-on-raspberry-64-os.html) <br/>
- Code::Blocks installed. (```$ sudo apt-get install codeblocks```)
## Running the app.
To extract and run the network in Code::Blocks <br/>
$ mkdir *MyDir* <br/>
$ cd *MyDir* <br/>
$ wget https://github.com/Qengineering/YoloV4-ncnn-Raspberry-Pi-64-bit/archive/master.zip <br/>
$ unzip -j master.zip <br/>
Remove master.zip and README.md as they are no longer needed. <br/> 
$ rm master.zip <br/>
$ rm README.md <br/> <br/>
Your *MyDir* folder must now look like this: <br/> 
dog.jpg <br/>
mumbai.jpg <br/>
YoloV4.cpb <br/>
yoloV4.cpp <br/>
yolov4-tiny-opt.bin <br/>
yolov4-tiny-opt.param <br/><br/>
If you want to run the full YoloV4 version you need: <br/>
yolov4.bin (download this 245 MB file from [Gdrive](https://drive.google.com/file/d/1dtkgOUKIeNdKRH5z9uTm-A6SUewjiBrj/view?usp=sharing))<br/>
yolov4.param <br/><br/>
Many thanks to [nihui](https://github.com/nihui/) again!

