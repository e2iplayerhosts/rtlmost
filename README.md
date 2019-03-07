E2iPlayer https://rtlmost.hu/ host

Install:
~~~
wget --no-check-certificate https://github.com/e2iplayerhosts/rtlmost/archive/master.zip -q -O /tmp/rtlmost.zip
unzip -q -o /tmp/rtlmost.zip -d /tmp
cp -r -f /tmp/rtlmost-master/IPTVPlayer/* /usr/lib/enigma2/python/Plugins/Extensions/IPTVPlayer
rm -r -f /tmp/rtlmost*
~~~

restart enigma2 GUI
