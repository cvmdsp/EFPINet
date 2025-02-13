# EFPINet
The corresponding paper title for this project is “EFPINet: Enhanced Feature Preservation and Interaction Network for SAR Ship Detection”.


# Train your net
train.py --weights '' --cfg your yaml address --data data/SSDD.yaml --hyp data/hyps/hyp.scratch-low.yaml --name your name --batch-size 16 --workers 0 --cache --epochs 300 --save-period 1

# Train your net
val.py --data data/SSDD.yaml --weights runs/train/exp/weights/best.pt

# SSDD dataset
baidu disk: https://pan.baidu.com/s/1Lpg28ZvMSgNXq00abHMZ5Q
Extract code: 2021 

# HRSID dataset
baidu disk: https://pan.baidu.com/share/init?surl=z0-E3Lwdkg14feu1FwRf3g 
Extract code: bs64 
