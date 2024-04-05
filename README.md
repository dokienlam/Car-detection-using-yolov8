
<H1 align="center">Car Detection using YOLOv8</H1>

YOLOv8 re-implementation

### Installation
! pip install ultralytics

! pip install pycocotools

### Results

| Version | Epochs | Box mAP |                                                                                  Download |
|:-------:|:------:|--------:|------------------------------------------------------------------------------------------:|
|  v8_n   |  500   |    37.0 |                                                                [model](./weights/best.pt) |
|  v8_n*  |  500   |    37.2 | [model](https://github.com/jahongir7174/YOLOv8-pt/releases/download/v0.0.1-alpha/v8_n.pt) |
|  v8_s*  |  500   |    44.6 | [model](https://github.com/jahongir7174/YOLOv8-pt/releases/download/v0.0.1-alpha/v8_s.pt) |
|  v8_m*  |  500   |    50.0 | [model](https://github.com/jahongir7174/YOLOv8-pt/releases/download/v0.0.1-alpha/v8_m.pt) |
|  v8_l*  |  500   |    52.5 | [model](https://github.com/jahongir7174/YOLOv8-pt/releases/download/v0.0.1-alpha/v8_l.pt) |
|  v8_x*  |  500   |    53.5 | [model](https://github.com/jahongir7174/YOLOv8-pt/releases/download/v0.0.1-alpha/v8_x.pt) |


<H1 align="center"> Dataset </H1>
About dataset: https://www.kaggle.com/datasets/lamdo2k3/dataset-car-detection-using-yolov8/data

This dataset consists of 2978 files organized into various file types. The dataset contains a total of 7 columns, providing information about each file. Below is a breakdown of the dataset:
.jpg Files (2497 files):

This category comprises 2497 files with the ".jpg" extension. These files likely contain images in JPEG format.
.cache Files (2 files):

Images: train 960
val 361
Test images: 175
Train images: 1001
This category consists of 2 files with the ".cache" extension. ".cache" files are commonly used to store temporary data or cache data for quick access.
.txt Files (476 files):

This category includes 476 files with the ".txt" extension. These files are likely text files, typically used to store textual information.
Other (3 files):

This category encompasses 3 files that do not fall under the previously mentioned extensions. They might have different file formats or extensions not specified in the description.
### Dataset structure

    ├── Data 
        ├── data 
            ├── images
                ├── train
                    ├── 1111.jpg
                    ├── 2222.jpg
                ├── val
                    ├── 1111.jpg
                    ├── 2222.jpg
            ├── labels
                ├── train
                    ├── 1111.txt
                    ├── 2222.txt
                ├── val
                    ├── 1111.txt
                    ├── 2222.txt
                ├── train.cache
                ├── val.cache
            ├── testing_images
            ├── training_images
            ├── sample_submission.csv
            ├── train_solution_bouding_boxes(1).csv
            ├── yolo.yaml
            
        
        
            
        
        





                
