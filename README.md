# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com



#DNS Enumeration


## OUTPUT:
  
 ## Output
  <img width="1010" height="830" alt="image" src="https://github.com/user-attachments/assets/98fcc072-2fbe-4183-9577-f414246c3e63" />

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
 ## Output:
 <img width="823" height="871" alt="image" src="https://github.com/user-attachments/assets/2f4e7362-b19b-4241-b2ca-4cd12d45a7ae" />
 
## Output:
<img width="738" height="587" alt="image" src="https://github.com/user-attachments/assets/d5d5bda6-3cd1-4d7a-a41b-3c575ea7bc80" />
## Output:
<img width="736" height="500" alt="image" src="https://github.com/user-attachments/assets/b2249f98-80d7-4a39-9932-687c6f8b72e5" />
intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
## Output :
<img width="816" height="813" alt="image" src="https://github.com/user-attachments/assets/62859770-2772-45dc-83d8-bf1cc2c6564c" />

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
## OUtput 
<img width="802" height="438" alt="image" src="https://github.com/user-attachments/assets/5269fbe6-24c8-4004-b4ef-a2dbda8a7d3e" />
cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion

<img width="576" height="119" alt="image" src="https://github.com/user-attachments/assets/7c5ee3bb-c57f-4675-a400-de19d445327d" />
<img width="781" height="775" alt="image" src="https://github.com/user-attachments/assets/c0153d81-7533-4c6e-af6b-756888363d15" />

<img width="637" height="436" alt="image" src="https://github.com/user-attachments/assets/ea4671f8-6c94-43e7-b43f-3095d1fede01" />

## dnsenum
Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  


## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.
<img width="633" height="339" alt="image" src="https://github.com/user-attachments/assets/ac11f1e7-4175-40b7-937a-b9fd0e2b8636" />





## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

