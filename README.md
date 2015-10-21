# mobilecaddy-sublime-package
Package for Sublime Text to aid with MobileCaddy development.

Adds snippets to aid with use of the MobileCaddy API.

## Install
Currently installation is completed by cloning this repo into your Sublime Text 3's `Packages/User` directory.
On linux this is `~/.config/sublime-text-3/Packages/User`


## Snippets


### devUtils.deleteRecord

**snippet**: *mcdelete*


### devUtils.dirtyTables

**snippet**: *mcdirty*


### devUtils.getCurrentUser

**snippet**: *mcuser*


### devUtils.insertRecord

**snippet**: *mcinsert*


### devUtils.readRecords

**snippet**: *mcread*

```
devUtils.readRecord(tableName).then(function(result){
	// body
}).catch(function(e){
	logger.error(e);
});
```

### devUtils.smartSql

**snippet**: *mcsmartsql*


### devUtils.syncMobileTable

**snippet**: *mcsync*


### devUtils.updateRecord

**snippet**: *mcupdate*


### vsnUtils.upgradeAvailable

**snippet**: *mcupgrade*


### vsnUtils.upgradeIfAvailable

**snippet**: *mcupgrade*