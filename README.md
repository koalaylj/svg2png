xlsx2json
=========

convert svg files to png。

### usage:

1. setup config.json
```json
{
    "src": "./svg",
    "dest": "./png"
}
```

2. run `$./export.sh` or `$./export.bat`
	this will convert all svg files from `src` to `dest` folder that configed in config.json with png format.

### notice
for now, it's only support convert to png format.