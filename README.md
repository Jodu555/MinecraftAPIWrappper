# MinecraftAPIWrappper

A Simple and handy minecraft API Wrapper

## Usage

### Create a McPlayer Object and get basic values from it

```javascript
const { McPlayer } = require('minecraftapiwrappper');

const playerName = new McPlayer('jodu555');
const playerUUID = new McPlayer('076b1e9c37714e84b1c70638514aba2e');
const playerUUID2 = new McPlayer('076b1e9c-3771-4e84-b1c7-0638514aba2e');

playerName.getUUID();
playerUUID.getName();
playerUUID2.getName();
```
