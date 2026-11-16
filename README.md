<div align="center">
  
  ![GitHub repo size](https://img.shields.io/github/repo-size/codewithsadee/grilli)
  ![GitHub stars](https://img.shields.io/github/stars/codewithsadee/grilli?style=social)
  ![GitHub forks](https://img.shields.io/github/forks/codewithsadee/grilli?style=social)
[![Twitter Follow](https://img.shields.io/twitter/follow/codewithsadee_?style=social)](https://twitter.com/intent/follow?screen_name=codewithsadee_)
  [![YouTube Video Views](https://img.shields.io/youtube/views/CjVGp5kGHxA?style=social)](https://youtu.be/CjVGp5kGHxA)

  <br />
  <br />

  <h2 align="center">Grilli - Restaurant Website</h2>

  Grilli is a fully responsive restaurant website, <br />Responsive for all devices, build using HTML, CSS, and JavaScript.

  <a href="https://codewithsadee.github.io/grilli/"><strong>➥ Live Demo</strong></a>

</div>

<br />

### Demo Screeshots

![Grilli Desktop Demo](./readme-images/desktop.png "Desktop Demo")

### Prerequisites

Before you begin, ensure you have met the following requirements:

* [Git](https://git-scm.com/downloads "Download Git") must be installed on your operating system.

### Run Locally

To run **Grilli** locally, run this command on your git bash:

Linux and macOS:

```bash
sudo git clone https://github.com/codewithsadee/grilli.git
```

Windows:

```bash
git clone https://github.com/codewithsadee/grilli.git
```

### 多言語対応

日本語（`/`）・英語（`/en/`）・中国語簡体字（`/zh/`）・韓国語（`/ko/`）に対応しています。

- 編集するのは日本語の `index.html` のみです。`en/`・`zh/`・`ko/` の `index.html` は自動生成されるため、直接編集しないでください。
- 翻訳は `i18n/en.json`・`i18n/zh.json`・`i18n/ko.json` に「日本語の文 → 翻訳」の形式で記載します。
- `index.html` を変更したら、次のコマンドで各言語のページを再生成してコミットします（Node.js が必要）。

```bash
node scripts/build-i18n.js
```

- 翻訳が足りない文があるとエラーになり、不足している日本語の文が表示されます。翻訳対象の一覧は `node scripts/build-i18n.js --list` で確認できます。
- `<!-- i18n:head -->` と `<!-- i18n:switcher -->` の間（hreflang と言語切替メニュー）もスクリプトが生成します。

### Contact

If you want to contact with me you can reach me at [Twitter](https://www.twitter.com/codewithsadee).

### License

[MIT](https://choosealicense.com/licenses/mit/)
