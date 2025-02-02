<!-- 
    title: RTX 升級器 - 基於 NVIDIA RTX 技術的 AI 視頻增強
    description: 使用 NVIDIA Maxine SDK 轉換低質量和老舊視頻。利用 RTX 實時加速提供 AI 超分辨率和偽影消除功能。用戶友好的 Gradio 界面實現無縫視頻增強。
    keywords: 視頻升級, NVIDIA RTX, AI 視頻增強, 超分辨率, 偽影消除, 老舊視頻修復, Maxine SDK, Gradio GUI, 視頻處理
    author: ABUS
    version: 1.0.0
    last-updated: 2025-2-3
    product-type: 視頻增強軟件
    platforms: Windows
    technology-stack: NVIDIA RTX, Maxine SDK, Super Resolution, Artifact Reduction, Gradio, CUDA, ffmpeg
    license: 商用
-->

# RTX Upscaler：基於 NVIDIA RTX 技術的 AI 視頻增強工具 📺

🌍 [English](README.md) ∙ [한국어](docs/README.kor.md) ∙ [日本語](docs/README.jpn.md) ∙ [中文简体](docs/README.zh.md) ∙ [中文繁體](docs/README.tw.md) ∙ [Deutsch](docs/README.de.md) ∙ [Español](docs/README.es.md)

運用 NVIDIA RTX 技術將低畫質視頻轉換成清晰精美的作品。RTX Upscaler 是一個基於 Gradio 的使用者友善介面，採用 NVIDIA Maxine Video Effects SDK 進行 AI 視頻增強。

[![GitHub Release](https://img.shields.io/github/v/release/abus-aikorea/rtx-upscaler)](https://github.com/abus-aikorea/rtx-upscaler/releases)

<p align="center">
  <img style="width: 90%; height: 90%" src="images/main_page.eng.png?raw=true" alt="NVIDIA RTX Video Super Resolution Web UI Interface"/>
</p>  

## 🚀 主要特點

- **AI 驅動增強**：採用 NVIDIA 尖端超解析度和瑕疵修復技術
- **即時 GPU 加速**：利用 RTX 功能實現更快處理速度
- **使用者友善介面**：簡單的 Gradio 圖形介面，操作便捷
- **老舊視頻修復**：完美提升舊影片至現代標準
- **一鍵安裝**：便攜且易於設置

## 🎯 系統需求

- **作業系統**：僅支援 Windows 10/11（64位元）
- **顯示卡**：NVIDIA RTX 系列（20、30、40、50）或 NVIDIA Quadro RTX
- **顯示記憶體**：最低 4GB（建議 8GB）
- **記憶體**：最低 4GB
- **儲存空間**：20GB 可用空間
- **網路**：安裝和更新時需要
- **驅動程式**：需要最新的 NVIDIA 顯示卡驅動程式

## 🛠️ 安裝指南

### 快速開始
1. 🚀 執行 `configure.bat`（首次設置）
   - 安裝必要依賴項（git、ffmpeg、CUDA）
   - 一次性過程，需要網路連接
   
2. 🚀 執行 `start.bat`
   - 啟動帶有網頁介面的 RTX Upscaler
   - 首次運行包含自動安裝

### 更新
- 執行 `update.bat` 更新 Python 虛擬環境
- 建議現有使用者執行此操作

### 解除安裝
- 執行 `uninstall.bat` 移除所有元件
- 或直接刪除安裝資料夾（便攜安裝）

## 💻 功能

### RTX Studio 介面
- 整合 YouTube 下載器
- AI 驅動瑕疵修復
- 超解析度增強
- 視頻壓縮工具
- 支援所有 ffmpeg 相容格式
- 可自訂輸出設定（wav、flac、mp3）
- 可調整模式、縮放比例、CRF 和預設選項

## ⚠️ 重要說明

- **免費試用限制**：處理最多 60 秒的視頻
- **顯示卡相容性**：僅支援 NVIDIA RTX 20 系列及更新型號
- **必要軟體**：
  - 最新的 [NVIDIA 顯示卡驅動程式](https://www.nvidia.com/en-us/drivers/)
  - [NVIDIA Video Effects SDK](https://www.nvidia.com/en-us/geforce/broadcasting/broadcast-sdk/resources/)

## 🔧 故障排除

如果瀏覽器沒有自動啟動：
1. 使用 start.bat 重新啟動應用程式
2. 手動訪問顯示的地址（例如：http://127.0.0.1:7892）

關於 Windows 安全性警告：
- 如果可用，點擊「更多資訊」然後「仍要執行」
- 如有需要，將檔案屬性設置為「解除封鎖」


## 📬 聯絡與支援

- 電子郵件：abus.aikorea@gmail.com
- 官方網站：https://abuskorea.imweb.me
- 在 Amazon 上架：美國、日本、新加坡、阿聯酋
- 產品展示：[YouTube 頻道](https://www.youtube.com/watch?v=z8g8LMhoh_o&list=PLwx5dnMDVC9Y7dAjm9r26CZUw1uU5VIeq)

## 🙏 鳴謝
* NVIDIA Maxine SDK：<https://docs.nvidia.com/deeplearning/maxine/vfx-sdk-system-guide/index.html>
* yt-dlp：<https://github.com/yt-dlp/yt-dlp>
* gradio：<https://github.com/gradio-app/gradio>

## ©️ 版權
  <img src="images/ABUS-logo.jpg" width="100" height="100"> by [ABUS](https://abuskorea.imweb.me)