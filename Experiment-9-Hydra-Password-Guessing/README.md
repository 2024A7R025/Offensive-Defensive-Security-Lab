
# Experiment 9: Controlled Password-Guessing Demonstration Using Hydra

## Aim
To perform a controlled password-guessing demonstration using Hydra in an authorized lab environment.

## Theory
Hydra, also known as THC-Hydra, is an open-source password-auditing tool available in Kali Linux. It is used to test authentication security of services such as SSH, FTP and web login services.

## Tools Used
- Kali Linux
- THC-Hydra
- Nmap
- Metasploitable 2
- SSH Service

## Procedure

### Step 1 – Identify Target Services
Nmap was used in the authorized lab to identify active services on the target machine. SSH was found running on port 22.

![Nmap Scan](outputs/01-nmap-scan.jpg)

### Step 2 – Observe Hydra Authentication Testing
Hydra was used in the controlled lab to demonstrate authentication testing. An initial connection error was observed.

![Hydra Attempt](outputs/02-hydra-attempt.jpg)

### Step 3 – Confirm the Result
The final Hydra output showed a successful authentication result in the lab environment.

![Hydra Result](outputs/03-hydra-result.jpg)

## Result
The experiment demonstrated password-auditing using Hydra and identified a valid test credential pair in the controlled lab environment.

## Conclusion
The experiment helped us understand Hydra, SSH authentication and the importance of strong passwords.


