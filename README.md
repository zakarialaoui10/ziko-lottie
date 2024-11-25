# ziko-lottie 
Lottie player element for [zikojs](https://github.com/zakarialaoui10/ziko.js)
## Install
```bash
 npm i ziko-lottie
```
## Usage 

### Node 

```js
import { LottiePlayer } from "ziko-lottie";
const Lottie = LottiePlayer(
    "https://assets1.lottiefiles.com/private_files/lf30_q2okh8lh.json"
    )
    .size("300px", "300px")
    .style({
        border : "1px darkblue solid"
    })
    Lottie.useControls()
```

### Brwoser 
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>zikojs</title>
</head>
<body>
    <script src="https://cdn.jsdelivr.net/npm/ziko@latest/dist/ziko.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/ziko-lottie@latest/dist/ziko-lottie.js"></script>
    <script>
    const { LottiePlayer } = ZikoLottie;
    const Lottie = LottiePlayer(
        "https://assets1.lottiefiles.com/private_files/lf30_q2okh8lh.json"
    )
    .size("300px", "300px")
    .style({
        border : "1px darkblue solid"
    })
    Lottie.useControls()
    </script>
</body>
</html>
```

## ⭐️ Show your support <a name="support"></a>

If you appreciate the library, kindly demonstrate your support by giving it a star!<br>
[![Star](https://img.shields.io/github/stars/zakarialaoui10/ziko-lottie?style=social)](https://github.com/zakarialaoui10/ziko-lottie)

# License 
This projet is licensed under the terms of MIT License 
<img src="https://img.shields.io/github/license/zakarialaoui10/zikojs?color=rgb%2820%2C21%2C169%29" width="100" align="right">