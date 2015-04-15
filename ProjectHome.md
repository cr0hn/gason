## News ##

### Update: 2013-12-16 ###

  * Use Gason in new burp suite version: http://www.smeegesec.com/2013/02/sqlmap-plugin-for-burp-extender.html
  * Fix for running Gason in Windows: http://www.praetorian.com/blog/burp-sqlmap-plugin-for-windows

### Old ###

  * This project contains a plugin to extend BurpSuite proxy. **And know you can run gason stand alone!!**

## What's Gason? ##

This plugins are wrapper of well known security tools.

This tool was developed by **Daniel García García a.k.a cr0hn**.


## Documentation ##
  * English: <a href='http://blog.buguroo.com/?p=2471&lang=en'><a href='http://blog.buguroo.com/?p=2471&lang=en'>http://blog.buguroo.com/?p=2471&amp;lang=en</a> </a>
  * Spanish: <a href='http://blog.buguroo.com/?p=2471&lang=es'><a href='http://blog.buguroo.com/?p=2471&lang=es'>http://blog.buguroo.com/?p=2471&amp;lang=es</a> </a>
  * <a href='http://gason.googlecode.com/svn/BurpPlugins/Changelog.txt'>Changelog</a>

## How to run? ##

### From BurpSuite ###

You must copy the plugin at home of burpsuite are installed. Then write:

`java -classpath gason-x.x.x.jar:"burpsuite_VERSION.jar" burp.StartBurp`

### Stand alone ###

You only need to write:

`java -jar gason-x.x.x.jar`

## Some images ##

New stand alone interface:

<img src='http://gason.googlecode.com/svn/BurpPlugins/screenshot/standalone.png' />

Burpsuite integration:

<img src='http://gason.googlecode.com/svn/BurpPlugins/screenshot/burpsuite_option.png' />

SQLMap interface:

<img src='http://gason.googlecode.com/svn/BurpPlugins/screenshot/main_newlook.png' />

Integrated searcher:

<img src='http://gason.googlecode.com/svn/BurpPlugins/screenshot/highlight.png' />