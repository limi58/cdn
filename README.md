# cdn

r=$(ps -ef | grep "firefox" | wc -l | awk '$1=$1');if [ $r == "1" ]; then firefox; fi

https://addons.mozilla.org/firefox/downloads/file/3927544/auto_amazon-1.2-fx.xpi
