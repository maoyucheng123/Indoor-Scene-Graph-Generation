# Indoor-Scene-Graph-Generation
BRMS-Net: A Multiscale Relational Network for Unbiased Indoor Scene Graph Generation

![](images\2.png)

This repository includes the code for scene graph generation on three datasets VG, OpenPSG and Indoor.

Basic operating requirement:

```
pip install -r requirements.txt
```

# Contents

```
.
├── build/
├── checkpoints/
├── configs/
├── datasets/
├── output/
├── tests/
├── tools/
├── TRAINING/
├── .gitignore
├── LICENSE
├── README
├── requirements
└── setup.py
```

VG_dataset

Download the VG annotations dataset

Download the evaluation folder evaluation

Download the yolov8 object detection pre-trained model 

Then put them into the VG_dataset folder

### Evalution

SGG PredCls evalution on VG

SGG PredCls evalution on PSG

SGG PredCls evalution on Indoor

## result

![](images\1.png)
