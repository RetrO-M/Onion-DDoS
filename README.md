<div align=center>
 
# TorNet

 DDoS Tool
 <br/><br/>
 don't attack websites you don't have permission to<br/>
 To avoid it being illegal, create your own website and do whatever you want in, We are not responsible for your stupidities.<br/>


## Language</br>

 <img src="https://img.shields.io/badge/Python-FFDD00?style=for-the-badge&logo=python&logoColor=blue"/></br>
</div>

- Don't worry if there are any bugs in the tool, we will try to fix them 🔧

## Installing Python & TOR

* linux-py: `sudo apt install python3`
* windows-py: `https://www.python.org/downloads/`

* linux: `sudo apt install tor`
* windows: `https://www.torproject.org/download/`

```shell
root~# sudo apt update
root~# sudo apt install tor
root~# tor --version
root~# tor --hash-password < your_password >
root~# sudo nano /etc/tor/torrc   
# Scroll down and search for "HashedControlPassword" and "ControlPort 9051" and remove the "#"
ControlPort 9051
HashedControlPassword < YOU_PASSWORD_HASH >
root~# sudo systemctl restart tor
root~# sudo systemctl status tor
```

## Installing TorNet

```sh
git clone https://github.com/RetrO-M/TorNet
cd TorNet

Install Python modules 
 - pip3 install -r requirements.txt

Start the program
 - python3 main.py < URL > < PASSWORD_TOR >
```

## Educational Purposes Only

```
 _____________________
/                     \
! Educational Purposes !
!        Only          !
\_____________________/
         !  !
         !  !
         L_ !
        / _)!
       / /__L
 _____/ (____)
        (____)
 _____  (____)
      \_(____)
         !  !
         !  !
         \__/ 
          
This script has been developed with a strictly legitimate purpose to assist law enforcement and cybersecurity professionals 
in testing the resilience and robustness of computer systems. It is a load testing tool designed to assess a server's 
or network infrastructure's ability to withstand large amounts of data traffic.

This tool is not intended to be used for malicious attacks, such as DDoS attacks, or any other form of cyberattacks that
would violate the law. Its usage is exclusively reserved for authorized testing by system owners, with the explicit 
consent of competent authorities.

IMPORTANT: This project is intended solely for legitimate purposes and must only be used with proper authorization. 
Any use contrary to these guidelines is strictly prohibited. As the creator of this tool, I accept no responsibility
for any misuse of the script outside of the legal and ethical parameters outlined here.

Violating cybersecurity laws can result in severe criminal penalties, including hefty fines and imprisonment.

The use of this tool must always be preceded by an assessment of potential impacts and a thorough planning process to avoid 
any unintended disruption of essential services. 
```
