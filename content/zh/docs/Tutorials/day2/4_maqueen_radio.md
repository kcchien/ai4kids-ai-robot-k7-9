---
title: "小車無線控制"
linkTitle: "無線控制"
slug: maqueen-radio
date: 2017-01-05
weight: 4
description: >
  micro:bit具有兩種無線通訊功能，一是無線電，另一是藍芽，我們將學習如何使用無線電來讓兩片以上的micro:bit互相溝通
---

# 無線電

無線控制隨著頻率的高低會用在不同的領域，像是 2.4GHz 一般用在生活周遭，像是藍芽或 WiFi；而 433MHz 由於頻率較低，在傳送內容較少的同時，卻具備更遠的傳輸距離，因此經常用於機場的塔臺之間的通訊。我們生活當中的廣播，無線對講機，手機等，其背後的通訊原理都是相同的。

## 實作廣播通訊

此活動需要分組配對，請先找好隊友

### 基本訊息收發

---

#### 發送端

https://makecode.microbit.org/_Lr4Yv5039cYr

![](https://i.imgur.com/FPu7CI7.png)

#### 接收端

https://makecode.microbit.org/_feAJfFi3bALm

![](https://i.imgur.com/vNAFWax.png)

### 用廣播控制小車動作

---

##### 主控

https://makecode.microbit.org/_725hYVCk46pr

![](https://i.imgur.com/8SspJQv.png)

##### 被控

https://makecode.microbit.org/_HJebaqCWJgwV水水

![](https://i.imgur.com/MshcviC.png)

### 體感控制

---

micro:bit 提供下列三個軸向的移動狀態，分別是 X、Y、Z:

- X - 左傾或右傾
- Y - 前傾或後傾
- Z - 上升或下降

![](https://i.imgur.com/lD5Sn9e.png)

#### 主控 (用晃動姿勢判斷)

https://makecode.microbit.org/_T64V30Uy6CvC

![](https://i.imgur.com/LDZTPuq.png)

#### 主控 (用 G 值判斷)

https://makecode.microbit.org/_AFw2JVFwFhEW

![](https://i.imgur.com/5r3fKXI.png)

#### 被控

https://makecode.microbit.org/_AJEATc8k7grc

![](https://i.imgur.com/7LZJnzc.png)
