# cdn

r=$(ps -ef | grep "firefox" | wc -l | awk '$1=$1');if [ $r == "1" ]; then firefox; fi
