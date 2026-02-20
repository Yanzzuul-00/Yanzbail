# Modified Whatsapp-API
<p align='center'>
  <img src="https://files.catbox.moe/fhhpdg.png" width="500">
</p>

--- 

## Usage
```json
"depencies": {
  "Yanzbail": "github:Yanzzuul-00/Yanzbail"
}
```
## Import
```javascript
const {
  default:makeWASocket,
  // Other Options 
} = require('xatabail');
```

---
# How To Connect To Whatsapp
## With QR Code
```javascript
const {
  default: makeWASocket
} = require('Yanzbail');

const client = makeWASocket({
  browser: ['Ubuntu', 'Chrome', '20.00.1'],
  printQRInTerminal: true
})
```
