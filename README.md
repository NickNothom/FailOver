# FailOver
My Raspberry Pi Network Failover Script

## On Boot:

`sudo ip r a default via 10.0.0.1 dev eth0 metric 200`

`sudo -H -u pi screen -dm -S failover sudo /home/pi/failover.sh`
