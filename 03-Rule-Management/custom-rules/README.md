## Custom rules

#### Detecting Ping 
A custom rule to deetct ICMP ping request and generate alert. Entries in both `fast.log` and structured `eve.json`
logs.

`alert icmp any any -> $HOME_NET any (msg:"ICMP Ping"; sid:1; rev:1;)`

#### Outcome 
<img width="791" height="115" alt="image" src="https://github.com/user-attachments/assets/d656b5cc-8f60-4ad1-993f-8f213076cbc3" />
