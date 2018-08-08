# AIによる「カップラーメン」の物体検出(研究用)
TensorFlowを使用して画像内の「カップラーメン」を検出します。  
  
![イメージ](https://github.com/TakeshiOkamoto/Cup_Ramen_detector/blob/master/image.jpg)  
  
## 使い方
https://www.petitmonte.com/python/ai_cup_ramen.html  
  
## 目的  
TensorFlowによるSSD(Single shot multibox detector)の研究、実験です。  
オリジナルデータセットを使用した「はじめの一歩」的なプロジェクトなので、精度は求めていません。
  
## 注意事項  
画像ファイルは研究目的以外で利用しないで下さい。再配布も禁止です。
  
## 参考文献
Jwata/sushi_detector_datasetの「create_tf_record.py」を改変して使用しています。  
Copyright (c) 2018 Junji Watanabe  
  
tensorflow/modelsの「ssd_mobilenet_v1_coco.config」を改変して使用しています。  
Copyright 2016 The TensorFlow Authors.  All rights reserved.  
