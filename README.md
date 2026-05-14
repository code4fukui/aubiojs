# aubiojs

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A JavaScript port of the Aubio audio analysis library.

## Demo
[Live demo](https://code4fukui.github.io/aubiojs/)

## Features
- Pitch detection
- Tempo tracking
- Onset detection

## Usage
```js
import aubio from 'https://code4fukui.github.io/aubiojs/aubio.esm.js';

const { Tempo } = await aubio();
const tempo = new Tempo(
  scriptProcessor.bufferSize * 4,
  scriptProcessor.bufferSize,
  audioContext.sampleRate
);
```

## License
MIT License — see [LICENSE](LICENSE).