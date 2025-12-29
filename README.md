# NKUST_AI_CUP_II
# AI CUP 2025 主動脈瓣膜物件偵測 (Aortic Valve Object Detection)

## 專案簡介
[cite_start]本專案為 **NKUST 類神經網路期末報告** 暨 **AI CUP 2025 競賽** 的解決方案 [cite: 15][cite_start]。我們利用深度學習模型進行醫學影像中的主動脈瓣膜偵測。針對原始資料中資料夾結構複雜及正負樣本不平衡的問題，我們提出了自動化路徑修正與動態負樣本採樣策略，最終在競賽中取得前 11% 的優異成績 。

## 團隊資訊 (TEAM 8931)
* [cite_start]**隊伍名稱**: TEAM 8931 [cite: 16]
* [cite_start]**成員**: 林立宸、林峯德、許芸瑄 
* **競賽成績**:
    * [cite_start]**Private Leaderboard Score**: 0.947495 
    * [cite_start]**Rank**: 105 (Top 11%) 

## 系統環境與需求
本專案主要運行於 **Google Colab** 環境，建議使用 GPU 進行加速訓練。

* [cite_start]**Python 版本**: 使用Python最新版本
* [cite_start]**GPU使用**: NVIDIA L4 / T4 GPU (CUDA 12.4) 
* [cite_start]**主要框架**: [Ultralytics](https://github.com/ultralytics/ultralytics) (YOLOv12) 
