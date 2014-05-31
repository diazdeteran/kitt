kitt
====

Script that turns the Chromebook Pixel lightbar into KITT

====

#!/bin/bash
 
ectool lightbar seq stop
ectool lightbar 4 00 00 00
 
while :
do
ectool lightbar 0 ff 00 00
sleep 0.08
ectool lightbar 1 ff 00 00
sleep 0.08
ectool lightbar 0 00 00 00
ectool lightbar 2 ff 00 00
sleep 0.08
ectool lightbar 1 00 00 00
ectool lightbar 3 ff 00 00
sleep 0.08
ectool lightbar 2 00 00 00
sleep 0.08
ectool lightbar 2 ff 00 00
sleep 0.08
ectool lightbar 3 00 00 00
ectool lightbar 2 ff 00 00
sleep 0.08
ectool lightbar 2 00 00 00
ectool lightbar 1 ff 00 00
sleep 0.08
ectool lightbar 2 00 00 00
sleep 0.08
ectool lightbar 1 00 00 00

done
