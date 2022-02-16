### pi

### esp32
* uart -> ```ls /dev/tty*```
* permission -> ```sudo chown <yourname> /dev/ttyUSB0```
* quit monit -> ctrl-a -> q
* env -> ```. ./export.sh```
* build -> ```idf.py build```
* flash -> ```idf.py -p /dev/ttyUSB0 -b 460800 flash```
* monit -> ```idf.py -p /dev/ttyUSB0 -b 115200 monitor```
* quit monit -> ctrl + ]