# sentinela
<p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/28984561/170900450-60b710ed-8b5c-43fe-a4dd-0e8dfecc8596.png">
  <br><i>Keeping any and all anomaly on pedestrian trajectory in touch</i>
</p>

## Installation
The first step that we gotta do is downloading all depencencies necessary to run the 
[YOLOv5](https://github.com/ultralytics/yolov5) model. To do that, you need to have 
`pip` installed (Python3.6+ is required to use YOLO, so the pip version must follow it)

```shell
$ pip install -r https://raw.githubusercontent.com/ultralytics/yolov5/master/requirements.txt
```
## Usage

### Running
Given a set of images, the algorithm iterates inside the folder with those images and, for each picture, 
it makes a prediction to check whether there is a person (or an animal)/vehicle or not.<br>
To run, we just need to open the terminal at the project directory and type

```shell
$ python3 main.py pics_folder target_folder
```

It's important to say, again, that Python 3.6+ is needed to run because of the Yolov5 model.

## References
You can find the YOLO documentation at [YOLOv5 Docs](https://docs.ultralytics.com)
