# Home Lab Setup Write-up

**Date**: 10/20/2026  
**Platform**: Local VirtualBox  

## Overview
Built an isolated cybersecurity home lab using VirtualBox with Kali Linux as the attacker machine and Metasploitable 2 as the vulnerable target.

## Steps Completed
1. Installed VirtualBox and Extension Pack.
2. Imported the official Kali Linux VirtualBox image.
3. Created a Metasploitable 2 virtual machine by selecting “Use an existing virtual hard disk file” and pointing it to the Metasploitable.vmdk file.
4. Configured both machines on the same Host-only / NAT Network named CyberLab so they can talk to each other but stay isolated from the real internet.
5. Verified connectivity by pinging between the two machines.
6. Took clean snapshots of both machines.

## Screenshots
<img width="952" height="1023" alt="image" src="https://github.com/user-attachments/assets/ae884149-60e0-4aab-8d60-617cf587be13" />
<img width="960" height="1032" alt="image" src="https://github.com/user-attachments/assets/fe741883-b529-4a4a-b0c3-7e2347fedcf6" />
<img width="720" height="400" alt="VirtualBox_Metasploitable2_20_10_2026_14_21_52" src="https://github.com/user-attachments/assets/1088c511-ad99-462a-8915-578f5c4744b3" />
<img width="1280" height="800" alt="VirtualBox_kali-linux-2026 2-virtualbox-amd64_20_10_2026_14_21_19" src="https://github.com/user-attachments/assets/3f91100b-a9f0-428c-b46e-023d7d0a942d" />


## Lessons Learned
Creating an isolated network is the most important first step so that practice stays legal and safe.
