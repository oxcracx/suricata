## Rules

#### 1. Default rule directory
All Suricata rules are stored in the following directory.

`/etc/suricata/rules/`
to list all the available rules use `ls`.
<img width="866" height="629" alt="image" src="https://github.com/user-attachments/assets/195cab38-d308-44b6-af5e-0c1e5e57681b" />

#### 2. Rule view 
To view the specific rule use 

`sudo less _.rules`

example: `sudo less http2-events.rules `

#### 3. Rule configuration
Suricata is instructed which rules to load via the configuration file
`sudo nano /etc/suricata/suricata.yaml`

##### vars 
Locate the section called **vars**.
<img width="866" height="629" alt="image" src="https://github.com/user-attachments/assets/286fa122-4456-4dfe-b23a-119cb81893ed" />
As I have put my ubantu server ip - 192.168.1.4, you can put yours here.


##### af-packet
verify your network network interface using `ifconfig`
<img width="866" height="629" alt="image" src="https://github.com/user-attachments/assets/b62ad710-6afb-49dc-ad7b-571a9f4a1df0" />

now configure your interface accordingly 
<img width="866" height="629" alt="image" src="https://github.com/user-attachments/assets/df166045-5f97-4080-ac7d-8dd3b790b48d" />

##### pcap
same as af-packet 
<img width="866" height="629" alt="image" src="https://github.com/user-attachments/assets/cb15406d-7c34-4a7b-9b49-084787b278e1" />

##### comminity-id
configure that `from` false to `true`.
<img width="866" height="629" alt="image" src="https://github.com/user-attachments/assets/f77a8444-ff2f-43e9-b4be-f4323e7e25a6" />


##### default rule path
<img width="866" height="629" alt="image" src="https://github.com/user-attachments/assets/fac12ce5-6aa7-4661-8c78-c3922eabafa6" />

