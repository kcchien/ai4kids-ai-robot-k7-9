---
title: "小車聲光效果"
linkTitle: "聲光效果"
slug: maqueen-light
date: 2017-01-05
weight: 3
description: >
  控制小車上的七彩LED燈與蜂鳴器
---

## 聲光效果

小車上俱備了一個小型蜂嗚器，以及 4 顆彩色 LED 燈

## 蜂鳴器

蜂鳴器（Buzzer）是產生聲音的信號裝置，有機械型、機電型及壓電型。蜂鳴器的典型應用包括警笛，報警裝置，火災警報器，防空警報器，防盜器，定時器。

蜂鳴器使用直流電供電，接通訊號源之後，音訊信號電流通過電磁線圈，使電磁線圈產生磁場，造成振動膜片週期性地振動發聲，藉由填入音符代碼，每個代碼都會對應到一個數值，這個數值相對應蜂鳴器聲音的頻率，因此就可以編輯音樂，透過蜂鳴器發聲。

![](https://i.imgur.com/i8UeSl3.jpg)

[音高頻率表 wiki](https://zh.wikipedia.org/wiki/%E9%9F%B3%E9%AB%98)

### 簡易音樂編輯與播放

[瑪莉兄弟音效下載](https://ai4kids-fcjh190729.s3.us-east-1.amazonaws.com/Day2/microbit-%E9%BA%A5%E6%98%86%E5%B0%8F%E8%BB%8A-%E8%9C%82%E9%B3%B4%E5%99%A8-%E7%91%AA%E8%8E%89%E5%85%84%E5%BC%9F.hex)

#### 蜂鳴器-星際大戰

https://makecode.microbit.org/_ae90qfYkwEMK

![](https://i.imgur.com/9yUH8SJ.png)

#### 蜂嗚器-全家門鈴

https://makecode.microbit.org/_DwLFmARqq1sE

![](https://i.imgur.com/nHWnTib.png)

#### 其他音樂資源參考

- 生日快樂 https://makecode.microbit.org/97217-41458-26568-28834
- 天空之城 https://makecode.microbit.org/_FLs4AWPr65HX
- 土耳其進行曲 https://makecode.microbit.org/_EFh0TAit2ftW
- 不可能的任務 https://makecode.microbit.org/_Umeb3jb1i9CV
- python https://makecode.microbit.org/_4hki9bfX7FC7
- Amazing Grace https://makecode.microbit.org/_ECe3fWg2Xcdo
- 新年快樂 https://makecode.microbit.org/_fevWm31gU6D3
- 迎春花 https://makecode.microbit.org/_Y8W7MXU0765k
- 迎新春 https://makecode.microbit.org/_fKMKWfX59J1H
- 瑪莉兄弟-game over https://makecode.microbit.org/_VAa835ea5aq3
- 瑪莉兄弟-水底世界音效 https://makecode.microbit.org/_TJqE8vKuDcAh
- Mozart https://makecode.microbit.org/_gLe0hp3809dh

(referenced : 宜蘭國華國中 優秀張大師以 micro:bit 音樂資源分享)

### 接到耳機或喇叭

你也可以透過連接耳機或喇叭，將 micro:bit 的聲音輸出

<img src="https://i.imgur.com/hiFhCDl.png" width=600px>

## LED

LED 的發色原理簡介與小車 LED 元件使用前的注意事項

### RGB 調色原理

RGB 指的是紅色光（Red）、綠色光（Green）與藍色光（Blue）所組成的「三原色光模式」，透過將 RGB 三種單色光按照不同比例進行合成，就可以產出各種顏色的色光。

還記得小時後上自然課，老師用一個簡單的圖案解釋所有顏色的形成嗎 ？事實上，這就是 RGB 三色原理。RGB 原理裡面的三原色就是紅色（Red）、綠色（Green）、藍色（Blue）三種顏色。稱他們為三原色是因為只要用這三種顏色，我們就可以混合出其他各種顏色。舉例來說：等量的紅色和綠色加在一起就是黃色，而等量的紅色加上藍色就是紫紅色。若是將三種顏色等量的加在一起，那就是白色了。

![](https://i.imgur.com/A6Z1h4M.png)

正如上圖所展示的，三種原色加在一起，就可以混合出各種不同的顏色。在影像的概念裡，所有的顏色就是這樣”變”出來的。

參考資料：

<a href="https://www.w3schools.com/colors/colors_picker.asp" target="_blank">HTML Color Picker</a>

<a href="https://en.wikipedia.org/wiki/Web_colors" target="_blank">Web Colors (wiki) </a>

<a href="http://csscoke.com/2015/01/01/rgb-hsl-hex/" target="_blank">RGB、HSL、Hex 網頁色彩碼，看完這篇全懂了</a>

### 色相環

![](https://i.imgur.com/Dleh2DT.png)

## 實戰 LED

小車上有四顆 LED 燈，可以發出各式各樣的色彩，透過操控這些 LED 的色彩，我們還將學到電腦科學中常碰到的色彩編碼

### 安裝 NeoPixel 擴展

---

要能順利使用小車上的 LED，請加入 NeoPixel 擴展，小車控制 LED 的引腳在 `P15`，LED 數量共有 4 個。

![LED extension](https://i.imgur.com/oHKqdOs.jpg)

![NeoPixel blocks](https://i.imgur.com/VNN0Ewj.png)

### 基本控制

透過 micro:bit 上的按鈕，來觸發小車上的 LED 燈，並發出指定的顏色

https://makecode.microbit.org/_f6DM3TFMtAio

![](https://i.imgur.com/OIIpWBZ.png)

---

### 霹靂燈

---

<a href="https://www.gq.com.tw/blog/riverhong/detail-3724.html" target="_blank">80 年代復古影集《霹靂遊俠》：尖端科技的結晶，人性化的萬能電腦車。</a>

![](https://i.imgur.com/XWHPdq0.jpg)

<iframe width="600" height="337" src="https://www.youtube.com/embed/ZIQATdjKwz4" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<iframe width="600" height="337" src="https://www.youtube.com/embed/Jz-QRH7d0YA" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

https://makecode.microbit.org/_fxdUcg8p91Cv

![](https://i.imgur.com/rtWRrh3.png)

### 呼吸燈

---

實作呼吸燈前，我們需要知道怎麼透過 HSL 色彩表示式，來控制 LED 的顏色顯示

HSL(Hue, Saturation, Lightness)色彩寫法

HSL 色彩的寫法是 HSL(色相角度但不加單位 0~360, 色彩飽和度 0~100%, 色彩亮度 0~100%)，而在括號內的色相採用的是 0~360 度，正常所見的語法就像是這樣

<h1> HSL( 240,  100%,  50% ) </h1>

色相的 0 度為 R(紅)色，120 度為 G（綠）色，240 度為 B（藍）色，為了記憶方便，先讓我把角度 0 度設定為正上方(與 CSS3 漸層相同)大家記憶比較方便點，所以以順時針方向旋轉，他們之間的角度就如同下圖所示

![](https://i.imgur.com/Dleh2DT.png)

https://makecode.microbit.org/_36DciDiomMPU

![](https://i.imgur.com/WdfIRLE.png)
