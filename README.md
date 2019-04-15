#archdiscover.sh

crapy  modifications in discover.sh (leebaird/discover) to port it on  Archlinux



#INSTALL/HACK/CRAP 

-clone discover.sh (leebaird/discover) in /opt/discover

$git clone https://github.com/leebaird/discover.git /opt/discover

-clone archdiscover.sh in whatever you want 

$ git clone https://github.com/eroa/archdiscover.git /tmp/archdiscover
$ cd /tmp/archdiscover


-copy archdiscover.sh archupdate.sh in /opt/discover

$ cp archdiscover.sh archupdate.sh /opt/discover

-run it 

$ cd /opt/discover
$ bash archupdate.sh
$ bash archdiscover.sh 

