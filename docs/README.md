
# 陽明交通大學選課系統改良

## 概述
陽明交通大學選課系統改良版，以python編寫。它提供一個更加方便直觀的選課環境。例如直接從
對應的時段選課，無須頻繁切換課表及選課網頁。

## 安裝
依序於終端Terminal執行以下命令：
```
pip install pillow
pip install ttkbootstrap
pip install pandas
pip install requests
pip install openpyxl
```
或是在終端機執行
```
pip install -r requirements.txt
```

## 執行
以python執行位於src目錄下的run.py檔案即可。

首次執行會需要下載課表
![image](https://github.com/SalmoonSake2/Project---Course-Adding-Tool/blob/main/docs/show_case1.png)

介面說明
![image](https://github.com/SalmoonSake2/Project---Course-Adding-Tool/blob/main/docs/show_case2.png)

篩選器說明
![image](https://github.com/SalmoonSake2/Project---Course-Adding-Tool/blob/main/docs/show_case3.png)

搜尋結果介面
![image](https://github.com/SalmoonSake2/Project---Course-Adding-Tool/blob/main/docs/show_case4.png)

課程詳細資料
![image](https://github.com/SalmoonSake2/Project---Course-Adding-Tool/blob/main/docs/show_case5.png)

## 已知問題
- 結果畫面有時無法順利滾動，這是由於scrollframe被物件遮掩所致，滑鼠移一下位置就好了。
- 希望老師能給A+
- 大家都是我的好朋友

## 作者
- Azusa Kaze
- Salmoon Sake

## 版本資訊
v1.0 updated in: 2024.12.9
