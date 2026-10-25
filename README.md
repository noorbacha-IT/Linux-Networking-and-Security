# Linux-Networking-and-Security
This repository showcases hands-on experience with Ubuntu Linux, TCP/IP networking, network diagnostics, and foundational cybersecurity concepts.
It includes practical command-line exercises demonstrating network connectivity testing, route analysis, socket monitoring, IP-to-MAC address resolution, and routing table inspection.

## Technologies & Tools
- Operating Systems: Ubuntu Linux, Windows

- Networking: TCP/IP, ICMP, ARP, Routing

- Tools: Ping, Traceroute, Netstat, ARP, Route

- Environment: Linux Terminal, Windows Command Prompt

### Practical Exercises
#### Network Connectivity Testing

<img width="975" height="472" alt="image" src="https://github.com/user-attachments/assets/4988d9a3-2e82-4289-bb5b-ebd20bddcc01" />
<img width="975" height="149" alt="image" src="https://github.com/user-attachments/assets/2392d503-7a67-46a1-a456-6941fac8fded" />


##### Purpose: 
Tests network reachability, measures round-trip time, and reports packet loss.
Useful for initial connectivity diagnostics and investigating network availability.

#### Network Path Analysis
<img width="975" height="538" alt="image" src="https://github.com/user-attachments/assets/381c0198-29a4-482c-8ac2-a1e7baae02ec" />
<img width="975" height="369" alt="image" src="https://github.com/user-attachments/assets/2f25c3e7-18e1-425b-8eae-a70d32e3df73" />
<img width="753" height="738" alt="Pic2" src="https://github.com/user-attachments/assets/f4246b69-c281-4b79-805b-34412e92a7c7" />

##### Purpose: 
Displays listening TCP/UDP sockets and associated port information.
Supports identification of exposed services and unexpected listening ports.

#### Network Connection Monitoring
<img width="975" height="446" alt="image" src="https://github.com/user-attachments/assets/3dcae29e-e57f-4512-88b8-fb6f9913c11f" />
<img width="975" height="427" alt="image" src="https://github.com/user-attachments/assets/b50e2791-832f-483e-837e-ebba7f0c86fa" />
<img width="975" height="423" alt="image" src="https://github.com/user-attachments/assets/ead83540-7462-43a4-9b37-9ec2e5409e57" />
<img width="975" height="427" alt="image" src="https://github.com/user-attachments/assets/1394344a-088c-4575-836e-a38571081f6f" />
<img width="975" height="433" alt="image" src="https://github.com/user-attachments/assets/e4ff3fa2-06de-4b7b-9bf8-ef1825088036" />
<img width="975" height="428" alt="image" src="https://github.com/user-attachments/assets/c50d20c5-cadf-47df-a0c5-eb4788c46229" />
<img width="975" height="424" alt="image" src="https://github.com/user-attachments/assets/ec86e82a-00d0-45ce-98b9-732cc9da0174" />

##### Purpose: 
Displays listening TCP/UDP sockets and associated port information.

Security relevance: Supports identification of exposed services and unexpected listening ports.

#### Address Resolution Analysis


<img width="975" height="309" alt="image" src="https://github.com/user-attachments/assets/a8af0f87-4ef0-4b36-b15b-bbc1bab5c4cf" />


##### Purpose:
Displays IP-to-MAC address mappings in the local ARP cache.
Supports local network troubleshooting and basic investigation of suspicious address mappings.

#### Routing Table Analysis

<img width="975" height="309" alt="image" src="https://github.com/user-attachments/assets/16b33c3e-f668-44b8-ae96-9e200c7efc5b" />

<img width="975" height="355" alt="image" src="https://github.com/user-attachments/assets/abc9ad3e-22be-44bc-8cf3-18df32f3bd61" />

<img width="975" height="297" alt="image" src="https://github.com/user-attachments/assets/10f9b685-6fb8-4551-a57d-47704cf0cd1e" />

<img width="975" height="113" alt="image" src="https://github.com/user-attachments/assets/8df17eb2-1507-4a98-b4ed-443ec539429b" />

<img width="983" height="99" alt="image" src="https://github.com/user-attachments/assets/7c255a41-7b1e-4d40-b18a-539a549762ab" />


Write shell script that defines 2 integers and one float value like 
a=5 
b=7 
c=5.5 
Perform multiplication of integers then divide with float. 
and finally print result with four decimal places. like 6.3636 
you have to use pipe operator ( | ) to send variables to bc utility for arithmetic.

<img width="975" height="705" alt="image" src="https://github.com/user-attachments/assets/441edec7-edad-497f-b788-e3e289e1054d" />
<img width="975" height="164" alt="image" src="https://github.com/user-attachments/assets/8d88e9cf-df3a-4dfa-aab6-a12d61852402" />

Write shell script that takes string from user, and make folder with named with string. Folder should contain file with named timestamp. having current time and date written on it.
<img width="949" height="740" alt="image" src="https://github.com/user-attachments/assets/3a87aeb3-bfcd-47d0-a6ae-096fe1692601" />
<img width="900" height="670" alt="image" src="https://github.com/user-attachments/assets/bccfdc75-9bb4-448e-90df-551ccc9c34f4" />
<img width="966" height="175" alt="image" src="https://github.com/user-attachments/assets/59402a7d-d1f7-4667-b015-0b75ff2626e6" />

Write a script which first picks hours from the system date and then greets the user 
according to following conditions. use if else structure to solve this example  
Hours 00 – 11 “Good Morning”  
Hours 12-17 “Good Afternoon”  
Hours 18-23 “Good night”  
Hint:- To take system hours use: date +%H, use if then elif then else

<img width="975" height="578" alt="image" src="https://github.com/user-attachments/assets/ba414648-c95a-4ebd-8f4d-fdb288434723" />
<img width="975" height="196" alt="image" src="https://github.com/user-attachments/assets/929b0a16-aaef-40d3-84ac-5546076ad339" />


Write shell script that print following output using while loop only.  
9 8 7 6 5 4 3 2 1 0  
8 7 6 5 4 3 2 1 0  
7 6 5 4 3 2 1 0  
6 5 4 3 2 1 0  
5 4 3 2 1 0  
4 3 2 1 0  
3 2 1 0  
2 1 0  
1 0  
0


<img width="828" height="738" alt="image" src="https://github.com/user-attachments/assets/24d40b94-932e-431c-a107-b75cc9a6e65a" />
<img width="700" height="407" alt="image" src="https://github.com/user-attachments/assets/27c3eb11-bf3c-47cd-bdd9-69c68372f289" />

---

<img width="743" height="565" alt="Lab3LIN2" src="https://github.com/user-attachments/assets/edd19694-83d7-46d0-a805-07e54a1eb4f4" />

##### Purpose: !
Displays the Linux kernel routing table, including gateways and network interfaces.
Helps identify routing misconfigurations and investigate network traffic paths.

##📌 Source Code Availability & Disclaimer

This repository is shared for portfolio demonstration and educational purposes, highlighting practical Linux networking knowledge and foundational cybersecurity skills.
