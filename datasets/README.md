# Log formatting:
## Apache:
```
LogFormat "\"%{%d/%b/%Y/%T}t\" \"%h\" \"%>s\" \"%B\" \"%D\" \"%m\" \"%U/%q\" \"%H\""
```
## Nginx:
```
log_format	lokari	'"$time_local" "$remote_addr" "$status" "$bytes_sent" "$request_time" "$request_method" "$request_uri" "$server_protocol"';
```