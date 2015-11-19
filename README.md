# jsFiddleDownloader

Download fiddles from jsFiddle.net, just using a PhantomJS script and save it as a single HTML file.
Evolved from "Joe Kuan" script --> https://joekuan.wordpress.com/2012/10/10/using-phantomjs-to-download-jsfiddle-net-code/

**Requirements**:

- PhantomJS --> http://phantomjs.org/download.html

**How to use it**:

To download a single fiddle from its url, just use 'downloadFiddle.js' like this:

```
phantomjs downloadFiddle.js <url> [<output file>]
```

To download all scripts of a determinated 'user' from jsFiddle.net, just use "downloadAllFiddles.js" in the next way:
```
  phantomjs downloadAllFiddles.js <user> [<output-folder>]
```
It'll download all backups in the currrent directory, the jsFiddles scripts will be named as:

```
  [<output-folder>/]<id-fiddle>.html
```


