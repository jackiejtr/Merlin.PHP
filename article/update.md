# 更新記錄

##### 0.6.4 2017-09-06

**修正**

* 修正 GFW / 大陸白 / Game 模式切換功能
* 安裝腳本支持 7.6 固件

##### 0.6.3 2017-09-06

**修正**

* GFW / Game / Stop 的菜單選項
* 改善輪詢方案為 Ajax 長連接
* 偶然出現的 complete 字樣

**移除**

* Game-V2 移除。

**備註**

* 實用工具和管理後台 SS 的顯示未能同步。就是如果是大陸白，可能會在後台顯示為以前選擇過的模式。以「ShadowSocks 配置信息」的顯示為準確。

##### 0.6.0 2017-08-09

**修正**

* 回復 ShadowSocks 快速重啟功能。
* 支持 梅林 SS 3.6.0（不再支持 SS 3.6.0 之前版本）
* 騰訊 DNS 次要 DNS 修正

**添加**

* 添加終端日誌輸出功能。

##### 0.5.10 2017-04-09

**修正**

* Google 驗證從首頁轉移到「http://google.com/generate_204」
* 國內測延遲從 Baidu 遷移到 Miui 的 generate_204 服務
* MTU 顯示從 null 更名到「自動設定」

##### 0.5.9 2017-02-20

**修正**

* 支持 SS 3.3.3（將不能再支持 3.1.5 之前）

**移除**

* ShadowSocks 的快速重啟功能

##### 0.5.8 2017-01-07

**添加**

* 添加分析用戶瀏覽器記錄

##### 0.5.7 2017-01-05

**修正**

* 模式按鈕的下拉菜單的激活伺服器不能正確顯示問題

##### 0.5.6 2017-01-04

**修正**

* 下拉菜單更新到符合移動使用習慣的樣式

##### 0.5.5 2016-10-27

**修正**

* 無法點擊的運營商 DNS 按鈕

##### 0.5.4 2016-08-27

**添加**

* 添加還原 ShadowSocks 到 1.5.7 功能（位於**在線更新**）
* 添加 DNS 設定功能
* 改善 Dashboard 部份獲取 CPU 溫度

##### 0.5.3 2016-08-19

**修正**

* 改正版本號

##### 0.5.2 2016-08-19

**修正**

* 適配 KoolShare ss 2.x 版本。
* 改善 Dashboard 界面。

##### 0.5.1 2016-08-17

**修正**

* 從 Chart.js 的圖表繪製，改為 CSS3 手工繪製。
* CPU / RAM 從餅形圖改為進度條樣式。
* Dashboard 從未發佈，調整為發佈狀態。

**備註**

* Dashboard 是**未完成功能**。
* Dashboard 在 iPhone standalone 下不工作的 Bug 未知如何解決。

##### 0.5 2016-08-03

**添加**

* 為 Dashboard 的開發準備了數據。

**修正**

* 調整網速算法，修正網速誤差。

**已完成的新特性**

* 以模擬登陸方式訪問後臺數據（未計劃使用）。

**Dashboard 功能**

* 可顯示系統狀態，如 CPU、RAM、溫度、磁碟剩餘空間、開機時間。
* 可顯示佔用資源項目，CPU TOP 5。
* 可顯示客戶端列表。
* 可顯示離線迅雷狀態。
* 可顯示基本網絡信息，如 Mac address。
* 系統摘要信息，如處理器、可用特性。

##### 0.4 2016-08-02

**修正**

* 調整「快速重啟」下的，Game 模式下的錯誤變量顯示。

##### 0.4 2016-07-30

**添加**

- 添加「遠程管理 VPS」的功能。
- Debug 調整為配置模式。

**修正**

* 部份代碼重構。
* 強化「設定」頁面。
* 調整網絡類型的獲取方式。
* 添加了自動修復權限功能。

**計劃**

* 為 Remote 添加自定義指令功能。
* 為 Remote 添加多伺服器功能。

##### 0.3 2016-07-30

**修正**

* 調整首頁所顯示的信息結構
* 與梅林的管理後臺同步 SS 所用服務器信息

##### 0.3 2016-07-28

**添加**

* 對 GFW-List 模式和大陸白名單模式的支持（可用性未知）。

**修正**

* 調整 iPad 以及 5s 上的一些顯示不佳的問題。
* 修正管理菜單總是指向 192.168.1.1。
* 調整腳本管理運行權限改為被動執行。

##### 0.3 2016-07-27

**添加**

* 切換服務器功能上線。
* 正式加入「設定」菜單，目前設定菜單只有一個功能，重新載入 SS 配置。
* 添加了「重新安裝」功能。
* 加入「即時網速」顯示。

**修正**

* 修正在非 Safari，下拉菜單的顯示問題。
* 修正在非 192.168.1.1 設備工作下的 timeout 問題。

**備註**

從 0.1 版本到 0.3 版，一直用到現在，覺得還不錯，自我感覺良好。這版會公開一下。

目前即時網速顯示略微大 100 ~ 50 KB/s，暫時未知如何解決。

##### 0.2 2016-07-19

**修改**

* 把 CDN 資源轉為本地資源（偶然的 DNS 問題導致 CDN 資源太慢了）
* 添加顯示連接所使用的 DNS
* 更新了字型
* 修正錯誤的自動更新指令

##### 0.1 2016-06-26

**功能預告**

* 遠程工具（可管理遠端 VPS 服務器，如重開等）開發中

**修改**

* 項目進行稍微重構
* 從 bootcdn 切換到 cdnjs

##### 0.1 2016-06-24

**增加**

* 一鍵安裝腳本

**修改**

* 更新更具體的說明

##### 0.1 2016-06-21

**增加**

* 在線更新功能；
* 遠程內容載入；
* UI 更新；
* Mobile Safari in standalone mode 支持；



##### 0.1 2016-06-20

**增加**

* 重啟 Network；
* 重啟 SS；
* 網絡測試；
