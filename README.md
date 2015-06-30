# smt.tmbundle



#SMT TextMate Bundle

This is a TextMate support for viewing and editing version 2.5 of [SMT-LIB2.](http://smtlib.cs.uiowa.edu/papers/smt-lib-reference-v2.5-r150528.pdf)

# Installation

For background on installing TextMate Bundles read [Installing a Bundle](http://manual.macromates.com/en/bundles#installing_a_bundle).


The following documentation is wrong. When I finally figure out
how to do this I will make sure this gets updated.

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


