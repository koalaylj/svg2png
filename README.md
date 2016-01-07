svg2png
=========

convert svg to png.

### usage:
1. run `$npm install`

2. setup config.json
	```json
	{
	    "src": "./svg",
	    "dest": "./png"
	}
	```

3. run `$./export.sh` or `$./export.bat`
	this will convert all svg files from `src` to `dest` folder that configed in config.json with png format.

### notice
for now, it's only support for converting svg to png format.
