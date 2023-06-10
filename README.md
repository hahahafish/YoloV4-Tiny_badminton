# YoloV4-Tiny_badminton
Google Colab範例，使用Yolov4-tiny(darknet)對自定義數據集進行訓練及推介

final_project.ipynb為主程序，包含Yolov4-tiny預訓練測試、自定義數據集訓練及推論測試my_dataset.zip

包含203張圖片及Yolo格式標記文件(＊.txt)

obj.data 為資料集設定檔

obj.names 為資源集分類標籤名稱

yolov4-tiny-obj.cfg 為自定義模型及相關數據

train.txt 為自定義資源訓練集文件名名稱列表

test.txt 為自定義數據驗證集合檔案名稱列表

yolov4-tiny-obj_last.weights 為訓練完成權重檔

test01.jpg 為測試用影像

訓練時間約1.5小時，視頻分配到的GPU類型及網路速度。
# 詳細測試過程請參考[YOLOV4-Tiny對自訂義訓練集進行訓練](https://colab.research.google.com/drive/1F2INOW8LR1a19CRNkeavrG5xRqfUfDbP?usp=sharing)