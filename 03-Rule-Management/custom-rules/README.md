## Custom rules

#### Detecting Ping 
A custom rule to deetct ICMP ping request and generate alert. Entries in both `fast.log` and structured `eve.json`
logs.

`alert icmp any any -> $HOME_NET any (msg:"ICMP Ping"; sid:1; rev:1;)`

