# Nmap Vulnerability Scanning

## Objective

Conduct comprehensive vulnerability scanning using Nmap to identify and analyze security weaknesses in target systems, facilitating preemptive security measures.

### Skills Learned

- Vulnerability Assessment: Utilized Nmap to perform thorough scans, identifying vulnerabilities and security loopholes in network infrastructures.
- Scripting and Automation: Developed scripts to automate scanning processes and handle output for efficient vulnerability management.
- Network Security Practices: Enhanced understanding of network security protocols and defensive strategies through practical scanning exercises.
- Kali Linux Proficiency: Gained proficiency in Kali Linux, leveraging its tools and environment for enhanced security scanning and analysis.

### Tools Used

- TheHive: The primary ticketing system software.
- Kali Linux: Used extensively to leverage a suite of security and penetration testing tools within the Kali environment.

### Outcome
Successfully identified critical vulnerabilities in a designated target system, enabling the cybersecurity team to prioritize and address security issues, thereby bolstering the organization's defense mechanisms against potential threats.
                                 
## Steps

Open Kali Linux and check IP address for Kali and Metasploit, and ping each other to ensure connection

![Screenshot 2024-08-14 105729](https://github.com/user-attachments/assets/1646bcfe-a798-4d71-9e2f-27ccf5f1b770)


![Screenshot 2024-08-14 105839](https://github.com/user-attachments/assets/8845ea9a-d098-4240-9a70-e01dd88416f5)


![Screenshot 2024-08-14 105946](https://github.com/user-attachments/assets/b6468fe3-7b8a-48c7-bcf4-51cff72082ee)


------------------------------------------------------------------------

Run basic NMAP scan to find any open ports/ Run a stealth scan with a faster speed (sS)(T4)


![Screenshot 2024-08-14 110006](https://github.com/user-attachments/assets/bbed9fd4-6647-4868-9183-93964edfaab4)


![Screenshot 2024-08-14 110035](https://github.com/user-attachments/assets/21e36201-0c88-4901-9453-f315b378b6d3)

-------------------------------------------------------------------------------

Run a version scan (sV) to get more information on the system with the open port


![Screenshot 2024-08-14 110121](https://github.com/user-attachments/assets/ec7edea1-9f43-4ff9-8bbc-f2d5807a7f60)

-------------------------------------------------------------------------------

Run a port scan on port 80 (-p) and a tcp port (-sT) to narrow down search for the target

![Screenshot 2024-08-14 110211](https://github.com/user-attachments/assets/39d73ccf-419f-450d-ae45-b0f6a8d822a1)

-------------------------------------------------------------------------------

Run same scan with (-sV) to get information on the version of the port to check for vulnerabilities

![Screenshot 2024-08-14 110349](https://github.com/user-attachments/assets/b588ea57-7451-4478-9149-f0d296204c85)

-------------------------------------------------------------------------------

Run (-A) and (-O) to get operating system information for port 80 and any additional information of the open port to gain as much information on the port, so we can check if there are any vulnerabilities 

![Screenshot 2024-08-14 110936](https://github.com/user-attachments/assets/5df2a0cc-0e2f-4e90-acd6-2dbea8466410)

-------------------------------------------------------------------------------
