# Gila CMS 1.10.9 - Remote Code Execution (RCE) (Authenticated)

## Description:
This Python script exploits the Gila CMS 1.10.9 vulnerability to achieve authenticated remote code execution (RCE). It uploads a shell, allowing arbitrary command execution on the target system. The exploit requires the target login URL, email, password, local IP, and port. It is for educational purposes only.

By Unknown_Exploit

## ExploitDB:
  - https://www.exploit-db.com/exploits/51569
  
## Exploit Brief:
- Vendor Homepage: https://gilacms.com/
- Software Link: https://github.com/GilaCMS/gila/
- Version: Gila 1.10.9
- Tested on: Linux
- Appreciation: Umar Muzaffar and André Maia

## Usage:
1. Enter the target login URL, including the "http://" or "https://" prefix.
2. Provide the email and password for authentication.
3. Enter the local IP (LHOST) and port (LPORT) for setting up the reverse shell connection.


![Exploit Execution](https://github.com/omershaik0/Handmade_Exploits/blob/main/Gila-CMS-1.10.9-RCE-Authenticated/execution.png)




![Reverse Shell](https://github.com/omershaik0/Handmade_Exploits/blob/main/Gila-CMS-1.10.9-RCE-Authenticated/rev_shell.png)
