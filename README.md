YATCO
=====

Yet Another Tabbed Chat Option - this one blinks

Since 2.5, has been broken into Config and the actual YATCO package. I will add defaults for any new configs which come up as a separate package named YATCOConfig-2.5-to-2.6.xml if, for instance, there are new config options added between 2.5 and 2.6 versions of YATCO

# To install
## YATCO 2.4
```
lua local a="https://raw.githubusercontent.com/demonnic/YATCO/master/YATCO-2.4.xml"function d(b,c)if not c:find("YATCO",1,true)then return end installPackage(c)os.remove(c)cecho("<lime_green>Package installed!\n")end registerAnonymousEventHandler("sysDownloadDone","d")downloadFile(getMudletHomeDir()..(a:ends("xml")and"/YATCO.xml"or"/YATCO.zip"),a)
```
## YATCOConfig - install before YATCO 2.5 or later. Only need installing once

```
lua local a="https://raw.githubusercontent.com/demonnic/YATCO/master/YATCOConfig.xml"function d(b,c)if not c:find("YATCO",1,true)then return end installPackage(c)os.remove(c)cecho("<lime_green>Package installed!\n")end registerAnonymousEventHandler("sysDownloadDone","d")downloadFile(getMudletHomeDir()..(a:ends("xml")and"/YATCO.xml"or"/YATCO.zip"),a)
```

## YATCO2.5 (from 2.5 onward make sure YATCOConfig is installed first
```
lua local a="https://raw.githubusercontent.com/demonnic/YATCO/master/YATCO2.5.xml"function d(b,c)if not c:find("YATCO",1,true)then return end installPackage(c)os.remove(c)cecho("<lime_green>Package installed!\n")end registerAnonymousEventHandler("sysDownloadDone","d")downloadFile(getMudletHomeDir()..(a:ends("xml")and"/YATCO.xml"or"/YATCO.zip"),a)
```
