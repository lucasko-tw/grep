# grep


From docker logs

```
docker logs server | if grep -q \'Server IS READY\'  ; then echo \'Server is ready!\' ; else echo \'Server is not ready\'; exit 1; fi
```

From file

```
if grep -q 'Hello Wrold' /report.txt ; then  echo 'Found word' ; else echo 'Not found word'; exit 1 ;fi"

```
