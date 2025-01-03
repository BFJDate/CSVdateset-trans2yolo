# Dateset-trans2yolo

# 将csv格式数据集标签转换为yolo数据集

以SPARK数据集为例

SPARK数据集格式
└───data/  
    ├───train_rgb/  
        ├───AcrimSat/  
        ├───Aquarius/  
        ├───Aura/  
        ├───...
    ├───train_depth/  
        ├───AcrimSat/  
        ├───Aquarius/  
        ├───Aura/  
        ├───...
    ├───train_labels.csv
    ├───validate_rgb/  
        ├───AcrimSat/  
        ├───Aquarius/  
        ├───Aura/  
        ├───...
    ├───validate_depth/  
        ├───AcrimSat/  
        ├───Aquarius/  
        ├───Aura/  
        ├───... 
    ├───validate_labels.csv


    目标yolo数据集格式
    dataset/
├── train/
│   ├── images/
│   └── labels/
└── val/
    ├── images/
    └── labels/
