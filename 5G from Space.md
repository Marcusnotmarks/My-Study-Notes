# Study note 1.
## 一、學習目標
**1.研究5G from Space: An Overview of 3GPP Non-Terrestrial Networks中的專有名詞及觀念。** <br>
**2.理解5G NTN(Non-Terrestrial Networks)基本架構。** <br>

## 二、參考文獻：5G from Space: An Overview of 3GPP Non-Terrestrial Networks
1.作者：Xingqin Lin, Stefan Rommer, Sebastian Euler, Emre A. Yavuz, and Robert S. Karlsson <br>
2.年份：2021 <br>
3.論文頁面：https://ieeexplore.ieee.org/document/9579443 <br>
4.pdf：https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9579443&tag=1 <br>

## 三、內容
### 1.Introduction
描述這份論文是在討論使用第三代合作夥伴計畫中5G無線技術以支援非地面衛星網路的相關設計及重要課題。
* 3GPP/3rd Generation Partnership Project：第三代合作夥伴計畫，為國際合作計畫，主要工作為制定技術規範，包含3G(WCDMA/HSPA)、4G(LTE)、5G(NR、New Radio)及正在規劃的6G，並推出各種版本：Realse 15/16為地面5G、Realse 17第一次將衛星納入5G、Realse 18+為邁向6G的過渡期。<br>

### 2.NTN的分類
根據3GPP的定義，非地面網路包含三類：<br>
**1.衛星通訊網路 (Satellite):** 分為 LEO (低軌), MEO (中軌), GEO (同步軌道)。近年來也隨著大型衛星星座的出現(Starlink、Kuiper、OneWeb)，衛星產業更積極的參與3GPP將5G網路整合到衛星當中。<br>
**2.高空平台系統/HAPS:** 高空平台（如氣球、無人機），是指包括飛機、氣球和飛艇在內的空中平台，在3GPP NTN的工作中，重點在於作為國際行動通訊基地台的高空平台，稱為HIBS。<br>
**3.空對地網路/ATG:** 空對地網路(為飛機提供Wi-Fi)，旨在利用地面站為飛機提供機上連線，地面站在空對地網路中扮演類似基地台的角色。但地面站的天線是向上傾斜對向天空的，且地面站之間的距離遠大於地面行動網路。 <br>

### 3.無線存取網路 RAN(Radio Access Networks)
在 5G 中，RAN的正式名稱叫做NG-RAN (Next Generation Radio Access Network)，而裡面的基地台叫做gNB，跟傳統的RAN相比挑戰增加了，例如：距離問題、位置問題、速度問題等等需要克服。NR NTN 中的 NR 指的是New Radio，意思是把 5G 的無線傳輸技術 (NR)，搬到非地面網路 (NTN，如衛星) 上使用。。<br>
**Release-15 針對 NR NTN 的研究項目：** 3GPP 對 NR NTN 的工作始於2017年，重點在於部署場景與通道模型。<br>
**Release-16 針對 NR NTN 的研究項目：** 繼Rel-15 對場景與通道模型的研究完成後，3GPP 在 Rel-16 繼續研究適配 NR 以支援 NTN 的解決方案。主要目標是確定一套「最小必要功能集」，使 NR 能支援 NTN（特別是衛星通訊）。這涵蓋了架構、高層協議與物理層。<br>
