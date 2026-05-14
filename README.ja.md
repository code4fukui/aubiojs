# aubiojs

Aubioオーディオ分析ライブラリのJavaScript移植版です。

## デモ
[ライブデモ](https://code4fukui.github.io/aubiojs/)

## 機能
- ピッチ検出
- テンポトラッキング
- オンセット検出

## 使い方
```js
import aubio from 'https://code4fukui.github.io/aubiojs/aubio.esm.js';

const { Tempo } = await aubio();
const tempo = new Tempo(
  scriptProcessor.bufferSize * 4,
  scriptProcessor.bufferSize,
  audioContext.sampleRate
);
```

## ライセンス
MIT License — 詳細は[LICENSE](LICENSE)を参照してください。
