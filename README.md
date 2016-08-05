##About

This work is based ruped24/toriptables2

updateproxy.sh is a simple bash script that changes proxy through which traffic is routed with user specified interval between changes and number of changes.

#####Usage:
Both updateproxy.sh and toriptables2.py must have executable permissions and be placed in /usr/local/bin

Changing proxy: sudo updateproxy.sh <number-of-changes> <delay-between-changes>
Remove proxy: sudo toriptables2.py -f

<delay-between-changes> is by default in seconds. Also check toriptables2.py -h for additional information.


#####To test:
* http://ipchicken.com
* https://check.torproject.org
* http://witch.valdikss.org.ru
* https://ipleak.net
* http://dnsleaktest.com

