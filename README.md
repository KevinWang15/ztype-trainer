# ztype-trainer
Trainer for the famous typing game ZType (http://zty.pe/)

## How to use

### Online
1. Head to [zty.pe](http://zty.pe/) to play the game.
2. In Chrome, open ```Developer Tool```, (press F12 on windows), go to ```Console``` tab, paste and execute the following code:
```
var script = document.createElement("script");script.type = "text/javascript";script.src = "https://cdn.jsdelivr.net/gh/KevinWang15/ztype-trainer@master/ztype-trainer.js";document.getElementsByTagName("head")[0].appendChild(script);
```

### Offline
Just clone this repo and use an http-server to serve the website.

e.g. Using [http-server](https://www.npmjs.com/package/http-server)

	git clone https://github.com/KevinWang15/ztype-trainer
	cd ztype-trainer
	http-server

and visit ```http://localhost:8080```

## Key Bindings
|Shortcut|Function|
|----|----|
|<kbd>Alt</kbd>+<kbd>1</kbd>|Toggle machine gun (automatic shooting). None->slow->fast->none..|
|<kbd>Alt</kbd>+<kbd>2</kbd>|Toggle manual machine gun (press anykey to shoot! impress your friends)|
|<kbd>Alt</kbd>+<kbd>3</kbd>|Toggle instant kill (one bullet kill)|
|<kbd>Alt</kbd>+<kbd>4</kbd>|Unlimited EMP (press <kbd>enter</kbd> to use)|
|<kbd>Alt</kbd>+<kbd>5</kbd>|God Mode (Can be used with <kbd>Alt</kbd>+<kbd>0</kbd>)|
|<kbd>Alt</kbd>+<kbd>6</kbd>|Shotgun (kills every enemy)|
|<kbd>Alt</kbd>+<kbd>7</kbd>|A lot of enemies (spawn 80 enemies)|
|<kbd>Alt</kbd>+<kbd>8</kbd>|A lot of fast moving enemies (spawn 80 fast-moving enemies)|
|<kbd>Alt</kbd>+<kbd>9</kbd>|Deactivate all|
|<kbd>Alt</kbd>+<kbd>0</kbd>|Disable screen shake|
|<kbd>Alt</kbd>+<kbd>-</kbd>|Distraction free mode (removes everything other than the game)|
