# debstep
Playground for building GNUstep on Debian

This proect bootstraps GNUstep on Debian in a few special ways for my other project isostep.  In the future this will create packages that will be ingested by my other projects dockerstep, isostep.  

**Features**

* Stable GNUstep installed installed in OS X 10.4 style layout
* libdispatch, nextpsace frameworks

**Things to try after install**

* Building applications from GSDE or Nextspace
* Testing GORM, ProjectCenter in /Developer/Applications

**Installing**

This following command requires a Debian 12 bookworm host:

```
sudo ./debstep-installer
```
