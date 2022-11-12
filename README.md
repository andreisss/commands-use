# commands-use

grep -E -o "([0-9]{1,3}[\.]){3}[0-9]{1,3}" iis-log-dump.log | uniq

sed -r 's/.*(dm[^\.]*\.[^/ ]*).*/\1/g' iis-log-dump.log

 grep "404" iis-log-dump.log | uniq | sort


grep "200.10.209.169" iis-log-dump.log | wc -l
