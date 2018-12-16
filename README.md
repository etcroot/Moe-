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
If that doesn't work, do this.
```
npm i discord.js ffmpeg-binaries node-opus opusscript moment moment-duration-format random-puppy kitsu.js animequote
```
All in one line & if that doesn't do it, try installing them seperately.

**Running The Bot**
```
node shard.js
```
Run with autorestart
```
npm i -g pm2
pm2 start shard.js
pm2 restart shard.js
pm2 stop shard.js
```
