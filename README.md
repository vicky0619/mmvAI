# mmvAI

## 中技社 AI 創意競賽

**主辦單位:** 財團法人中技社  

**作品名稱:** 迷霧安全行駛輔助系統  

**團隊成員:** 施丞穎、莊子賢、蔡文綺  

### 解題說明
利用毫米波感測器的特性（能穿越水氣），在濃霧中檢測前方是否有障礙物，以提升行車安全。  
我們將感測器回傳的速度-距離、速度-角度變化圖做為資料集進行訓練，最終使模型得以判斷感測器當前在接近或遠離前方障礙物。


## 功能

- **運動檢測：** 精確檢測各種運動類型，包括前進、後退和停止。
- **數據可視化：** 用於可視化收集的數據，以協助分析的工具。
- **模型訓練：** 在運動數據上高效訓練 AI 模型。

## 安裝

要開始使用 mmvAI 專案，請遵循以下步驟：

1. 克隆此倉庫：
   ```bash
   git clone https://github.com/vicky0619/mmvAI.git
   ```
2. 進入該目錄：
   ```bash
   cd mmvAI
   ```
3. 安裝必要的依賴（如果適用）：
   ```bash
   pip install -r requirements.txt
   ```

## 使用

安裝後，您可以使用以下命令運行運動檢測模型：
```bash
python motion_detection.py
```

## 貢獻

歡迎貢獻！如果您有改進或新功能的建議，請隨時克隆此倉庫並提交拉取請求。

## 授權

此專案根據 MIT 許可證進行授權。詳情請參見 [LICENSE](LICENSE) 文件。

---

## Features

- **Motion Detection:** Accurately detect various types of movements, including forward, backward, and stopping.
- **Data Visualization:** Tools for visualizing collected data to aid in analysis.
- **Model Training:** Efficient training of AI models on motion data.

## Installation

To get started with the mmvAI project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/vicky0619/mmvAI.git
   ```
2. Navigate into the directory:
   ```bash
   cd mmvAI
   ```
3. Install the necessary dependencies (if applicable):
   ```bash
   pip install -r requirements.txt
   ```

## Usage

After installation, you can run the motion detection model using the following command:
```bash
python motion_detection.py
```

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to fork the repository and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.



