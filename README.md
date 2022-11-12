# commands-use

grep -E -o "([0-9]{1,3}[\.]){3}[0-9]{1,3}" iis-log-dump.log | uniq

sed -r 's/.*(dm[^\.]*\.[^/ ]*).*/\1/g' iis-log-dump.log
