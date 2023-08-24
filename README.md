# Joint submission by Samir Paul ( paulsamir555@gmail.com ) and Monimoy Deb Purkayastha ( monimoyd@gmail.com )

# ERA1_S13-Yolo-on-custom-object-objection
ERA1_S13 Yolo on custom object objection; assignment of ERA1 program from TSAI (The School of AI)

## Model
This is simple custom object detection model on yolov5

Trained Ultralytics Yolov5 on custom data

## Custom Data Classes
spoon (kichen) knife (kitchen)

## Sample Data shown below

![image](https://github.com/paulsamir2010/ERA1_S13-Yolo-on-custom-object-objection/blob/main/IMG_20230812_105427.jpg)

![image](https://github.com/paulsamir2010/ERA1_S13-Yolo-on-custom-object-objection/blob/main/IMG_20230812_105330.jpg)

![image](https://github.com/paulsamir2010/ERA1_S13-Yolo-on-custom-object-objection/blob/main/Knifedetected.png)

## Custom Data
Trained the model on 238 custom images (used mobile phone to capture the images).

Trained the model for 50 epochs

## Metrics
Trained the model for 50 epochs

Metrics
mAP50 = 0.90

## Deployment
This is deployed in Hugging Face spaces using Gradio
https://huggingface.co/spaces/samirpaul/ERA1_S13_Object_Detection_Yolov5_Custom_Data

User Interface
User can browse and select an image of spoon or knife

Alternatively some examples are included in the UI of the app, to choose image of spoon or knife

![image](https://github.com/paulsamir2010/ERA1_S13-Yolo-on-custom-object-objection/blob/main/HuggingFacePic.jpg)
