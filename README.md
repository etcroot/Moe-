# Moe-
Listen.moe Discord Streaming Bot

### Self-Hosting
**Configuration**
```
{
"token":"Bot Token",
"prefix":"Prefix",
"ownerID":"Owner ID"
}
```
**Requirements**
```
npm i
```
If that doesn't work, use these.
```
npm i discord.js
npm i ffmpeg-binaries
npm i node-opus
npm i opusscript
npm i moment
npm i moment-duration-format
npm i random-puppy
npm i kitsu.js
npm i animequote
```
**Running The Bot**
```
node index.js
```
Run with autorestart
```
npm i -g pm2
pm2 start index.js
pm2 restart index.js
pm2 stop index.js
```
