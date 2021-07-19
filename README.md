
# Pallet Detection

Aim of the project is to detect pallet boxes moving in conveyor

## Table of Content
* [Demo](#demo)
* [Installation](#installation)
* [Run Locally](#run-locally)
* [Running Tests](#running-tests)


## Demo
  ![ezgif com-gif-maker](https://user-images.githubusercontent.com/73110673/126075587-65edfa23-9f38-4926-b843-da45875a556a.gif)

## Installation

The Code is written in Python 3.6. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip.

## Run Locally

Clone the repository

```bash
  git clone https://github.com/Raghul-github/Pallet_Detection_YoloV5.git
```

Go to the project directory

```bash
  cd Pallet_Detection_YoloV5
```

Install dependencies

```bash
  pip install -r requirements.txt
```

  
## Running Tests

`detect.py` runs inference on a variety of sources and saving results to `runs/detect`.
```bash
$ python detect.py --weights "best.pt" --img 416 --conf 0.8 --source 0  # webcam
                                                                     file.jpg  # image 
                                                                     file.mp4  # video
                                                                     path/  # directory
                                                                     path/*.jpg  # glob
                                                                    'https://youtu.be/NUsoVlDFqZg'  # YouTube video
                                                                    'rtsp://example.com/media.mp4'  # RTSP, RTMP, HTTP stream
```
