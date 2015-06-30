# smt.tmbundle



#SMT TextMate Bundle

This is a TextMate support for viewing and editing version 2.5 of [SMT-LIB2.](http://smtlib.cs.uiowa.edu/papers/smt-lib-reference-v2.5-r150528.pdf)

# Installation

For background on installing TextMate Bundles read [Installing a Bundle](http://manual.macromates.com/en/bundles#installing_a_bundle).


The following documentation is wrong (it is for TextMate 1 not 2). When I finally figure out
how to do this I will make sure this gets updated.


https://github.com/textmate/textmate/wiki/FAQ


## Install Location

If you plan on making changes to the Bundle that you want me to
pickup, you must install in a different location than you would
typically install TextMate Bundles. If you use the TextMate Bundle
editor to edit a bundle in any location other than
`~/Library/Application Support/TextMate/Bundles`, it will create delta
files which are very difficult to merge.

### Normal Install

	cd ~/Library/Application\ Support/Avian/Pristine\ Copy/Bundles
	git clone https://github.com/SRI-CSL/SMT.tmbundle.git
	osascript -e 'tell app "TextMate" to reload bundles'

### Development Install

	cd ~/Library/Application Support/Avian/Bundles
	git https://github.com/SRI-CSL/SMT.tmbundle.git
	osascript -e 'tell app "TextMate" to reload bundles'


### Ian's attempt at TextMate 2 Instructions.

The [FAQ](https://github.com/textmate/textmate/wiki/FAQ) says the following:


If you wish to edit the bundles and share your changes you should install (git clone) them to:
```
~/Library/Application Support/Avian/Bundles
```

This way, TextMate won’t create delta files (which aren’t useful for sharing).

If you manually install bundles and they do not show up, your file system may lack support for fs-events. If this is the case, you will need to delete the cache and relaunch TextMate:
```
rm ~/Library/Caches/com.macromates.TextMate/BundlesIndex.plist
```



