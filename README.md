# -NETWORKWALKS-VIVIAN-B084--WK1-PM1-CYBERSECURITY-LAB-SETUP
Security Lab set up
# 🔐 Cybersecurity Lab Environment Setup

**Building an isolated virtual lab for penetration testing and ethical hacking practice**
</div>
## 🎯 Objectives

The main objectives of this project are to:
-Install and Configure Virtual Box
-install an set up Kali Linux 
-Create a private **NAT Network** for the cybersecurity lab.Configure the network settings on your Virtualbox (create NATNetwork in 10.0.0.0/24)
- Configure network connectivity for Kali Linux.
- Assign a consistent IP address to the Kali VM.
- Verify network connectivity and DNS resolution.
- Take a clean VM snapshot for recovery.
- Document the complete setup process.
- Prepare the environment for future cybersecurity projects.

  ##
## 🛡️ Purpose of the Lab

The lab provides an isolated and controlled environment for cybersecurity learning and authorized security testing.

It can be used for the following activities 

- Network reconnaissance
- Port scanning
- Vulnerability assessment
- Packet analysis
- Web security testing
- Exploitation practice
- Security-tool experimentation

##
## 🏗️ Lab Architecture

![](1-screenshot-title-image.png)


Additional target machines can be added to the same virtual network in future projects.

---

## ⚙️ Lab Configuration

| 🧩 Component       | ⚙️ Configuration   |
| ------------------ | ------------------  |
| 🖥️ Host OS         | Windows 10         |
| 🧠 Host RAM        | 8 GB               |
| ⚡ Processor       | Intel Core i7      |
| 🧰 Hypervisor      | VirtualBox 7.2  |
| 🐉 Security OS     | Kali Linux 2026.2  |
| 🧠 Kali RAM        | 2048 MB            |
| 🌐 Virtual Network | NAT Network        |
| 📡 Network Address | 10.0.0.0/24        |
| 🐧 Kali IP Address | 10.0.0.2/24        |
| 🚪 Default Gateway | 10.0.0.1           |
| 🌍 DNS Server      | 8.8.8.8            |
| 🔮 Future VM Range | 10.0.0.3–10.0.0.99 |

---

##
LAB SET UP PROCEDURES [FOR CYBER SECURITY ANDE ETHICAL HACKING PRACTICE]
after watching the video guide, 
I downloaded and installed the 7-zip 

I DOWNLOADED AND INSTALLED THE VIRTUAL BOX ON MY LAPTOP<img width="628" height="377" alt="Screenshot 2026-10-27 134417" src="https://github.com/user-attachments/assets/fc77fc08-2db5-41fe-abf5-fee02c64475e" />
**Important; was downloaded in a zip file, it was extracted first before the installation took place.

I CONFIGURED THE NETWORK SETTING ON MY VIRTUALBOX BY CREATING A NATNETWOR IN 10.0.0/24

<img width="954" height="529" alt="3rd step network set up" src="https://github.com/user-attachments/assets/17923f08-ff59-4dd0-9e18-ee56b0934dd8" />
2
<img width="954" height="529" alt="Screenshot 2026-11-06 174738" src="https://github.com/user-attachments/assets/dcc4df30-f619-48c6-8a0b-bafe96e95bd2" />

<img width="575" height="430" alt="Screenshot 2026-11-06 050605" src="https://github.com/user-attachments/assets/c48c3592-7eb7-4bd9-9641-c82949ea8a04" />

I DOWNLOADED AND IMPORTED KALI LINUX VIRTUAL MACHINE IN MY VIRTUALBOX
<img width="935" height="512" alt="Screenshot 2026-10-27 183849" src="https://github.com/user-attachments/assets/e5b9e4b0-3e74-405a-95ba-5ec2f589bb81" />


##
PROBLEMS ENCOUNTERED

I encountered a network issue on my kali, my browser was not opening and the network was not pinging via the terminal, I removed the kali and imported it back to the virtual machine. 

<img width="1280" height="800" alt="problems encountered" src="https://github.com/user-attachments/assets/5415b400-0524-42ee-b70d-bf77de2095ba" />


I aslo encountered problem at the first step of downloading my kali, my laptop seurity set up flagged it and it wasn't  getting into my system 



<img width="578" height="330" alt="Screenshot 2026-10-27 153815" src="https://github.com/user-attachments/assets/6bb8e010-fbde-4fc2-b80c-4b6225677065" />

i went to my window security and my browser setting and permitted it to download by creating an exception on my windows security that aligns with that of the exact file location

After reimporting my kali, i went back to the guides to see what i missed on, and corrected my errors.

i reset up the ip configuration on my kali linux, 


<img width="575" height="430" alt="Screenshot 2026-11-06 050605" src="https://github.com/user-attachments/assets/2813fdca-4310-441b-a4c8-e1b69f997360" />

2
<img width="959" height="526" alt="Screenshot 2026-11-06 050811" src="https://github.com/user-attachments/assets/55b72b27-6b05-426c-8ef3-5ba72046b775" />

KALI IP CONFIGURATION

<img width="959" height="538" alt="Screenshot 2026-11-07 121331" src="https://github.com/user-attachments/assets/c02862f1-9d4b-41b9-9d34-be3fc9baebcb" />

Configuration done, and my network is working

<img width="959" height="530" alt="Screenshot 2026-11-07 115718" src="https://github.com/user-attachments/assets/bdabcaab-dd2d-4e45-bb5b-924198289f55" />





my SNAPSHOT Taken
<img width="959" height="535" alt="Screenshot 2026-11-06 200317" src="https://github.com/user-attachments/assets/4a4e42d0-b94f-42b4-904d-c5f4e13bd46a" />







