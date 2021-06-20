# smokeproject
首先将数据集放入data文件夹
运行voc_label.py生成txt文件
运行train_test_split.py分离训练集和测试集
运行path_trans.py补全数据路径
修改smoke.yaml
使用 python train.py --data data/smoke.yaml --cfg models/yolov5s.yaml --weights weights/yolov5s.pt --batch-size 10 --epochs 100命令开始训练
