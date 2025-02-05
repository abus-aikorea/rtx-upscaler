<!-- 
    title: RTX アップスケーラー - NVIDIA RTX テクノロジーによる AI 動画品質向上
    description: NVIDIA Maxine SDK を使用して低品質および古い動画を変換します。AI パワードスーパーレゾリューションとアーティファクト低減を RTX リアルタイム アクセラレーションで実現。使いやすい Gradio インターフェースで シームレスな動画品質向上を実現します。
    keywords: 動画アップスケーリング, NVIDIA RTX, AI 動画品質向上, スーパーレゾリューション, アーティファクト低減, ビンテージ動画復元, Maxine SDK, Gradio GUI, 動画処理
    author: ABUS
    version: 1.0.0
    last-updated: 2025-2-3
    product-type: 動画品質向上ソフトウェア
    platforms: Windows
    technology-stack: NVIDIA RTX, Maxine SDK, Super Resolution, Artifact Reduction, Gradio, CUDA, ffmpeg
    license: 商用
-->

# RTX アップスケーラー：NVIDIA RTX テクノロジーによる AI 動画品質向上 📺

🌍 [English](../README.md) ∙ [한국어](README.kor.md) ∙ [日本語](README.jpn.md) ∙ [中文简体](README.zh.md) ∙ [中文繁體](README.tw.md) ∙ [Deutsch](README.de.md) ∙ [Español](README.es.md)

NVIDIA RTX テクノロジーを活用して、低品質の動画を高品質に変換します。RTX アップスケーラーは、NVIDIA Maxine Video Effects SDK を基盤とした使いやすい Gradio GUI プログラムで、AI による超解像とアーティファクト除去機能を提供します。

[![GitHub Release](https://img.shields.io/github/v/release/abus-aikorea/rtx-upscaler)](https://github.com/abus-aikorea/rtx-upscaler/releases)

<p align="center">
  <img style="width: 90%; height: 90%" src="images/main_page.eng.png?raw=true" alt="NVIDIA RTX Video Super Resolution Web UI Interface"/>
</p>  

## 🚀 主な機能

- **AI による品質向上**: NVIDIA の最先端超解像・アーティファクト除去技術を活用
- **リアルタイム GPU 高速処理**: RTX 性能による高速処理
- **直感的なインターフェース**: シンプルな Gradio ベース GUI で簡単操作
- **古い映像の復元**: 古い映像を現代的な品質にアップグレード
- **ワンクリックインストール**: 簡単インストールと持ち運び可能

## 🛸 デモ動画
- [You Call It Love (from L étudiante)](https://youtu.be/HXomwoKS3V4)
- [A-ha • “Take On Me” • 1985 [Reelin' In The Years Archive]](https://youtu.be/cZPSTTsmHxI)

## 🎯 システム要件

- **OS**: Windows 10/11 (64ビット) のみ
- **GPU**: NVIDIA GeForce RTX 2060、Quadro RTX 3000、TITAN RTX以上
- **NVIDIAドライバー**: NVIDIAディスプレイドライバーバージョン570以上
- **VRAM**: 最小 4GB (8GB 推奨)
- **RAM**: 最小 4GB
- **ストレージ**: 20GB の空き容量
- **インターネット**: インストールとアップデートに必要
- **ドライバー**: 最新の NVIDIA グラフィックドライバーが必須

## 🛠️ インストールガイド

### クイックスタート
1. 🚀 `configure.bat` を実行 (初回のみ)
   - 必要なコンポーネントのインストール (git, ffmpeg, CUDA)
   - 初回のみ実行、インターネット接続が必要
   
2. 🚀 `start.bat` を実行
   - Web-UI と共に RTX アップスケーラーを起動
   - 初回起動時は自動インストールを実行

### アップデート
- `update.bat` を実行して Python 仮想環境をアップデート
- 既存ユーザーに推奨

### アンインストール
- `uninstall.bat` を実行して全コンポーネントを削除
- またはインストールフォルダを削除 (ポータブルインストール)

## 💻 機能紹介

### RTX スタジオインターフェース
- 統合 YouTube ダウンローダー
- AI によるアーティファクト除去
- 超解像による品質向上
- 動画圧縮ツール
- すべての ffmpeg 互換フォーマットに対応
- カスタマイズ可能な出力設定 (wav, flac, mp3)
- 調整可能なモード、スケール、CRF、プリセットオプション

## ⚠️ 注意事項

- **無料体験版の制限**: 最大60秒の動画処理が可能
- **GPU互換性**: NVIDIA GeForce RTX 2060、Quadro RTX 3000、TITAN RTX以上
- **NVIDIAドライバー**: NVIDIAディスプレイドライバーバージョン570以上
- **必須ソフトウェア**:
  - [NVIDIA Graphics Driver](https://www.nvidia.com/en-us/drivers/)
  - [NVIDIA Video Effects (Version 0.7.6)](https://www.nvidia.com/en-us/geforce/broadcasting/broadcast-sdk/resources/)

## 🔧 トラブルシューティング

ブラウザが自動起動しない場合:
1. start.bat で再起動
2. 表示されたアドレスに手動でアクセス (例: http://127.0.0.1:7892)

Windows セキュリティ警告について:
- 「詳細情報」をクリックし、「実行」を選択
- 必要に応じてファイルプロパティで「ブロックの解除」を設定

## 📬 お問い合わせ・サポート

- メール: abus.aikorea@gmail.com
- 公式サイト: https://abuskorea.imweb.me
- Amazon での購入: US, Japan, Singapore, UAE
- 製品デモ: [YouTube チャンネル](https://www.youtube.com/watch?v=z8g8LMhoh_o&list=PLwx5dnMDVC9Y7dAjm9r26CZUw1uU5VIeq)
- Amazon Japan: [製品ページ](https://www.amazon.co.jp/dp/B0DBVRJ542)

## 🙏 謝辞

* NVIDIA Maxine SDK: <https://docs.nvidia.com/deeplearning/maxine/vfx-sdk-system-guide/index.html>
* yt-dlp: <https://github.com/yt-dlp/yt-dlp>
* gradio: <https://github.com/gradio-app/gradio>

## ©️ 著作権

<img src="images/ABUS-logo.jpg" width="100" height="100"> by [ABUS](https://abuskorea.imweb.me)