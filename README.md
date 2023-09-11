<div align="center">

# ReScaler 🌟

<!-- s;HidemaruOwO/ReScaler/g;User/Repository;g -->

![image](https://github.com/HidemaruOwO/ReScaler/g/assets/82384920/bf4ccddf-3eae-4fae-97f4-d2b59bec919f)
[![Test CLI](https://github.com/HidemaruOwO/ReScaler/actions/workflows/test.yml/badge.svg)](https://github.com/HidemaruOwO/ReScaler/actions/workflows/test.yml)
![最終コミット](https://img.shields.io/github/last-commit/HidemaruOwO/ReScaler?style=flat-square)
![リポジトリのスター](https://img.shields.io/github/stars/HidemaruOwO/ReScaler?style=flat-square)
![問題](https://img.shields.io/github/issues/HidemaruOwO/ReScaler?style=flat-square)
![オープンな問題](https://img.shields.io/github/issues-raw/HidemaruOwO/ReScaler?style=flat-square)
![バグの問題](https://img.shields.io/github/issues/HidemaruOwO/ReScaler/bug?style=flat-square)

![image](https://user-images.githubusercontent.com/82384920/267009775-678efca7-4f05-4410-82bf-3186a2a9a0c9.png)

## なんだこれは？

GANを使用して画像及び動画を高画質にしたまま拡大するGUIソフトウェアです。

</div>

- Select Language

<table>
  <thead>
    <tr>
      <th style="text-align:center"><a href="README.md">🎌日本語</a></th>
      <th style="text-align:center"><a href="README.en.md">🤡English</a></th>
      <th style="text-align:center"><a href="README.zh-CN.md">🐉简体中文</a></th>
      <th style="text-align:center"><a href="README.zh-TW.md">🍜繁体中文</a></th>
      <th style="text-align:center"><a href="README.ko.md">🌸한국어</a></th>
    </tr>
  </thead>
</table>

## Usage 💨

[Release](https://github.com/HidemaruOwO/ReScaler/releases/latest)もしくは[Actions](https://github.com/HidemaruOwO/ReScaler/actions/workflows/build.yml)からバイナリをダウンロードして、実行してください。

## Install 😊

このスクリプトを実行してください。

```bash
yarn install
```

## Build 🔨

```bash
yarn build
```

## Repository Tools 🔧

- [x] Depandabotのセットアップ
- [ ] CodeQLのセットアップ
- [x] ChatGPT Code Reviewのセットアップ

<details>
<summary>メモ</summary>

- Depandabotのセットアップ
  - `.github/dependabot.yml`の`package-ecosystem`に値を設定 (例: npm,yarn,pip)
- CodeQLのセットアップ
  - https://dev.classmethod.jp/articles/github-code-scanning/
  - [対応言語](https://codeql.github.com/docs/codeql-overview/supported-languages-and-frameworks/)
- GPT PRのセットアップ
  - リポジトリの`Secret Value`に`OPENAI_API_KEY`の設定
  - https://github.com/anc95/ChatGPT-CodeReview/blob/main/README.ja.md

</details>

## For Contributor 🤝

本プロジェクトにコントリービュートする場合は[コントリービュートガイド](docs/README.md)をお読みください。

## Reference ✨

- [nihui/realcugan-ncnn-vulkan](https://github.com/nihui/realcugan-ncnn-vulkan)
- [xinntao/Real-ESRGAN-ncnn-vulkan](https://github.com/xinntao/Real-ESRGAN-ncnn-vulkan)
- [nihui/waifu2x-ncnn-vulkan](https://github.com/nihui/waifu2x-ncnn-vulkan)
