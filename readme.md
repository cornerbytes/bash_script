one line bash benchmark `wget -qO- bench.sh | bash` or `wget -qO- yabs.sh | bash`

get public ip adress `curl ipinfo.io`

free memory as a root user `echo 3 > /proc/sys/vm/drop_caches`

find special permission file `find / -perm -u=s -type f 2>/dev/null`

curl https website for ignore invalid and self signed certificate `curl -k https://93.184.215.14/`

list tcp connection `netstat -tlpn` or `ss -tlpn`

get information about shell being executed `echo $0` or `ps -p $$`

bypass space restriction using `$IFS`. Example : `ls$IFS-la`

listing of last logged in users `last`

terminate session users login on system`sudo pkill -9 -t pts/1`

list directory or file in human readable `ls -lah`

list directory or file recursively `ls -laR`

unzip to specific directory `unzip file.zip -d /specific_dir/`

set immutable attribute to file `chattr +i filename.txt`

list attribute file `lsattr -l filename.txt`

list tcp connection with pid information `sudo netstat -tlpn` or `sudo ss -tlpn`

delete user `userdel --remove (username)`

update password without passwd `echo "(username):password" | chpasswd` (warning: .bash_history or history)

get ip address of the computer `hostname -I`

curl follow redirect `curl -L http://google.com/`

w - Show who is logged on and what they are doing `w`

Bash history expansion. Example: repeat a history command `whoami` using `!who`

Get information about default shell `echo $SHELL`

Generate a fingerprint for a public key `ssh-keygen -lf ~/.ssh/id_rsa.pub`

display information about the command type `type grep && type -a git`

find writeable file in specific directory `find /opt/ -writable`
