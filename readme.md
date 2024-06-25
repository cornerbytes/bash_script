one line bash benchmark `wget -qO- bench.sh | bash`

get public ip adress `curl ipinfo.io`

free memory as a root user `echo 3 > /proc/sys/vm/drop_caches`

find special permission file `find / -perm -u=s -type f 2>/dev/null`

curl https website for ignore invalid and self signed certificate `curl -k https://93.184.215.14/`

list tcp connection `netstat -tlpn` or `ss -tlpn`

get information about shell being executed `echo $0` or `ps -p $$`

bypass space restriction using `$IFS`. Example : `ls$IFS-la`
