# mobilecaddy-sublime-package
Package for Sublime Text to aid with MobileCaddy development.

Adds snippets to aid with use of the MobileCaddy API.

## Install
Currently installation is completed by cloning this repo into your Sublime Text 3's `Packages/User` directory.
On linux this is `~/.config/sublime-text-3/Packages/User`
 

## Snippets

### devUtils.readRecords

**snippet**: *mcread*

2 options are available. 

**devUtils.readRecords(...)  (Full Promise)**

```
devUtils.readRecord(tableName).then(function(result){
	// body
}).catch(function(e){
	logger.error(e);
});
```

**devUtils.readRecords(...);**

```
devUtils.readRecord(tableName);
```
