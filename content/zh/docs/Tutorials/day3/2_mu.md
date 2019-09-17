---
title: "MU 視覺辨識模組"
linkTitle: "MU 視覺辨識模組"
slug: microbit-mu
date: 2017-01-05
weight: 2
description: >
  MU 視覺辨識模組，為小車帶來了機器視覺。我們將探討電腦AI視覺原理及如何運用視覺打造一輛AI小車
---

MU 視覺模組已內建數種視覺辨識功能，包含：

- 形狀卡片
- 交通卡片
- 數字卡片
- 人體檢測
- 球體檢測
- 顏色識別
- 顏色檢測

我們可以利用這些內建的 AI 視覺辨識功能，來打造許多應用

## 安裝 MU 摩圖視覺模組

請務必仔細跟著下列步驟安裝，才能正確啟用 MU 摩圖視覺辨識模組

### 1. 確認 MU 為 I2C 模式

請確認下圖紅框中的開關，是往上撥的

<img src="https://i.imgur.com/QbEFngO.jpg" width=600>

### 2. 將 MU 連接到 micro:bit

為了方便接線，可以先把超音波模組拿下來。接完線後再把超音波模組插回。

請將連接線插頭，插入 MU 模組的插槽中，其他 4 根端子，分別依照下列順序插到麥昆小車上。

口訣：綠、藍、黑、紅

<img src="https://i.imgur.com/N7hrNg9.jpg" width=600>

<img src="https://i.imgur.com/NVPgXfP.png" width=600>

### 3. 固定 MU 模組

可以用橡皮筋或是魔術黏土將 MU 模組跟 micro:bit 固定起來

### 4. 加入摩圖 MU MakeCode 擴展

`https://github.com/zjuxumang/pxt-MuVisionSensor`

### 5. 寫程式前要進行初始化

<img src="https://i.imgur.com/Dm6XRML.png" width=600px>

## 交通卡辨識

我們將利用交通卡辨識算法來做一個小小專案
