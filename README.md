# aubiojs

- [demo](https://code4fukui.github.io/aubiojs/)

## usage

```js
import aubio from 'https://code4fukui.github.io/aubiojs/aubio.esm.js';

const { Tempo } = await aubio();
const tempo = new Tempo(
  scriptProcessor.bufferSize * 4,
  scriptProcessor.bufferSize,
  audioContext.sampleRate
);
```
