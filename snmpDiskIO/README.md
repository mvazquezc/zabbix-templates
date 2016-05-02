# SNMP Disk IO Template for Zabbix

Template for Disk IO data gathering on Zabbix via SNMP

## Requeriments

You must configure a global regexp (Administration -> General -> Regular expressions) as follows: 

```
Name: Disk devices for IO Discovery
Expression: ^(sd[a-z]|hd[a-z]|vd[a-z])$
Expression type: Result is TRUE
Case sensitive: checked
```
