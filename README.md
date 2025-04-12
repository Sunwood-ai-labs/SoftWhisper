<h1 align="center">SoftWhisper 🎤✨</h1>

<p align="center">
   <a href="README_JP.md"><img src="https://img.shields.io/badge/ドキュメント-日本語-white.svg" alt="JA doc"/></a>
   <a href="README.md"><img src="https://img.shields.io/badge/english-document-white.svg" alt="EN doc"></a>
</p>

<p align="center">
   <img src="docs/header.png" alt="SoftWhisper Header" width="600px">
</p>

<p align="center">
   <img src="https://img.shields.io/badge/Python-3.7%2B-blue.svg" alt="Python 3.7+"/>
   <img src="https://img.shields.io/badge/FFmpeg-Required-green.svg" alt="FFmpeg"/>
   <img src="https://img.shields.io/badge/VLC-Required-orange.svg" alt="VLC"/>
</p>

音声文字起こしと話者分離を簡単に行えるソフトウェア！

## 必要な環境

- Python 3.7以上
- FFmpeg
- VLCメディアプレイヤー

## インストール手順

1. このリポジトリをクローン：
```bash
git clone https://github.com/NullMagic2/SoftWhisper .
```

2. 必要なソフトウェアをインストール：
   - [Python](https://www.python.org/downloads/) (3.7以上)
   - [FFmpeg](https://ffmpeg.org/download.html)
   - [VLCメディアプレイヤー](https://www.videolan.org/vlc/)

3. 依存パッケージをインストール：
```bash
pip install -r requirements.txt
```

## 使い方

1. SoftWhisper.batを実行：
```bash
.\SoftWhisper.bat
```

2. GUIが起動したら、以下の手順で文字起こし：
   - 音声/動画ファイルを選択
   - モデルサイズを選択（tiny, base, small, medium, large）
   - 必要に応じて話者分離機能を有効化
   - 「開始」ボタンをクリック

<p align="center">
   <img src="docs/demo.png" alt="SoftWhisper Demo" width="600px">
</p>

## 機能

- 🎯 高精度な文字起こし（Whisperモデル使用）
- 👥 話者分離機能（誰が話したかを識別）
- 🌍 多言語サポート
- 🎮 使いやすいGUIインターフェース

## トラブルシューティング

### よくある問題

1. `libvlc.dll not found`エラー
   - VLCメディアプレイヤーがインストールされていることを確認してください
   - インストール後、プログラムを再起動してください

2. FFmpegエラー
   - FFmpegが正しくインストールされ、PATHに追加されていることを確認してください

## ライセンス

[MITライセンス](LICENSE)

## 謝辞

このプロジェクトは以下のオープンソースプロジェクトを使用しています：
- [Whisper](https://github.com/openai/whisper)
- [inaSpeechSegmenter](https://github.com/ina-foss/inaSpeechSegmenter)
- [FFmpeg](https://ffmpeg.org/)
