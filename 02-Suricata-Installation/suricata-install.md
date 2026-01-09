## Suricata installation 
This section explains how Suricata IDS/IPS was installed and configured on an Ubuntu Server 
system for network traffic monitoring.

#### 1. System update  
Before installing Suricata, the system packages were updated to ensure stability and compatibility.

`sudo apt update && sudo apt upgrade -y` 

#### 2. Add suricata repository
The official Suricata repository was added to obtain the latest stable version.

`sudo add-apt-repository ppa:oisf/suricata-stable`
`sudo apt update`

#### 3. Install suricata
Suricata was inatalled using the package manager.

`sudo apt install -y suricata`

verify installation
`suricata --version`

#### 4. Status
Check suricata status using.

`sudo systemctl status suricata`

to stop the suricata service use  `sudo systemctl stop suricata` & 
to start the suricata service use  `sudo systemctl start suricata`

#### 5. Path
To navigate to suricata use this path
`sudo /etc/suricata`
