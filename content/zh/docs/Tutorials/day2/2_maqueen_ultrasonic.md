---
title: "小車超音波感測"
linkTitle: "超音波感測"
slug: maqueen-ultrasonic
date: 2017-01-05
weight: 2
description: >
  透過超音波距離感測器，提供小車可以感知與某物體距離的能力。
---

## 關於超音波

超音波感測器（國外把它叫作 **PING)))** sensor）是由超音波發射器、接收器和控制電路所組成。當它被觸發的時候，會發射一連串 40 kHz 的聲波並且從離它最近的物體接收回音。超音波是人類耳朵無法聽見的聲音，因為它的頻率很高。
我們使用的這款感測器，其偵測距離為 2cm~450cm

超音波（英語：Ultrasound），是指任何聲波或振動，其頻率超過人類耳朵可以聽到的最高閾值 20kHz（千赫）。超音波由於其高頻特性而被廣泛應用於醫學、工業等眾多領域。
某些動物，如狗隻、海豚、以及蝙蝠等等都有著超乎人類的耳朵，也因此可以聽到超音波。亦有人利用這個特性製成能產生超音波來呼喚狗隻的犬笛。
所謂超音波，只透過具有彈性與慣性介質，如空氣，當空氣本身一旦產生膨脹或壓縮時，透過其分子的運動而有波動的傳撥產生。因此，音波無法在真空中進行傳播。人類聽覺能察覺波動，稱之為聲音。此時音波，即稱之為可聽波。

超音波感測經常用於避障或距離感測的領域，像是自走車或潛艇的聲波雷達，另外由於水面會反射雷射光，所以超音波感測技術也經常用來做水位的高度辨識喔。

<iframe width="535" height="304" src="https://www.youtube.com/embed/IQo16aCf2BE" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## 實作超音波感測專案

### 1. 讀取超音波距離

https://makecode.microbit.org/_eYE22z9tWYUr

![](https://i.imgur.com/3vDS2le.png)

### 2. 超音波避障

小車利用超音波，持續偵測行進路線上是否有障礙物，如果距離障礙物到一定距離，便會試著避開障礙物，朝其他方向前進

https://makecode.microbit.org/_Ac4h049CEatf

![](https://i.imgur.com/wMy9kTM.png)

### 3. 自動跟隨

自動跟隨演算法如下：

1. 取得目前超音波距離
1. 如果目前距離小於設定的跟隨距離，則進入跟隨模式，否則停車
1. 在跟隨模式中，如果目前距離，大於跟隨距離的一半，則前進，否則後退

https://makecode.microbit.org/_MMiWj5Cvy8jA

![](https://i.imgur.com/2ZtUzyg.png)

## 程式概念

### 演算法的設計 Algorithm

#### 什麼是演算法

什麼是演算法？ 聽起來很高深，會很難嗎？

問題 -> 描述 -> 程式流程圖 -> (虛擬碼 Pesudocode) -> 編碼

<a href="https://jason-chen-1992.weebly.com/home/-whats-algorithm" target="_blank">【演算法】入門介紹－什麼是演算法 What's Algorithm?</a>

**影片分享：What's an algorithm ?**

<iframe width="640" height="360" src="https://www.youtube.com/embed/6hfOvs8pY1k" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

生活中有沒有什麼隨處可見的例子？

你能否自己寫出或說明出今天上課的避障演算法呢？

### 變數 Variable

變數使用基本觀念
從生活中看變數
計分板
遊戲的分數，生命值
按讚數

### 函式 Function

函數的功能，用途，好處
