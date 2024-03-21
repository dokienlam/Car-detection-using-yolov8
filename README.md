<H1 align="center">Fire Detection using YOLOv8</H1>

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
### Dataset structure

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
        ├── sample_submission.csv
        ├── train_solution_bouding_boxes(1).csv
        ├── yolo.yaml
        
        
        
            
        
        





                
