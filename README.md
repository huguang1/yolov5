## train
python train.py --weights yolov5s.pt --data data/fire.yaml --workers 1 --batch-size 8 

## test 
python detect.py --weights best.pt --source ./dataset/fire/images/test
