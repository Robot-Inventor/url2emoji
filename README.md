# url2emoji

Convert URL of Twemoji image on twitter.com to emoji text.

## Installation

```powershell
npm install url2emoji
```

## Usage

```typescript
import { url2emoji } from "url2emoji";

const emoji_svg = url2emoji("https://abs-0.twimg.com/emoji/v2/svg/1f600.svg");
const emoji_png = url2emoji("https://abs-0.twimg.com/emoji/v2/72x72/1f600.png");
console.log(emoji_svg); // 😀
console.log(emoji_png); // 😀
```
