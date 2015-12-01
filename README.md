cheatsheet
==========

To get the elasticsearch version, you can curl where it listens and get basic info : `curl http://localhost:9200`

##Linux Command

Count the number of line in a document : ` wc -l data/anonymized.csv `
Change a char in a file : `sed -i 's/foo/bar/g'`

##Mongo

Get the name of the collections `db.getCollectionNames()`

## Vagrant 

When a vm has a "runnning" status but all vm are shutdown, you can do `vagrant global-status --prune` to invalid wrong entries.

## Gif
using recordmydesktop

    mplayer -ao null out.ogv -vo jpeg:outdir=output
    convert output/* output.gif
    convert output.gif -fuzz 5% -layers Optimize optimised.gif

## Shell

http://www.thegeekstuff.com/2008/09/bash-shell-ps1-10-examples-to-make-your-linux-prompt-like-angelina-jolie/
