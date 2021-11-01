# N2  
https://github.com/ultralytics/yolov5
https://github.com/SHI3DO/N2-dataset

# train

> python train.py --img 640 --batch 32 --epochs 200 --data data/n2data.yaml --cfg models/n2x.yaml --weights yolov5x.pt --name n2-x


# run
> python detect.py --source ./testing --weights runs/train/n2-x/weights/best.pt --conf 0.5