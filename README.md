# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 
```
Developed by:Gracia Ravi R
Register no:212222040047
```

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

## Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com



intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.


inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

 
# DNS Enumeration


## DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion



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


## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same


# Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  

# nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.

 
## output:
## site:
![Screenshot 2024-10-06 215434](https://github.com/user-attachments/assets/c82b2904-1a73-4a27-88dc-55cf704c6142)

## filetype:

![Screenshot 2024-10-06 215611](https://github.com/user-attachments/assets/470e6ba3-2e5c-438d-a585-f4ca8e7bad85)



## intext:

![Screenshot (149)](https://github.com/user-attachments/assets/2c83e5f0-60ee-4fc2-9512-a8110e6785d2)


## inurl:

![Screenshot 2024-10-06 220206](https://github.com/user-attachments/assets/9572616a-189d-4d14-b166-9998f0bf6883)


## intitle:
![Screenshot 2024-10-06 220109](https://github.com/user-attachments/assets/2708c91c-35f9-472f-9375-f3900ca67e8a)

## link:
![Screenshot 2024-10-06 220236](https://github.com/user-attachments/assets/e9f9f14d-70e7-4b65-b6bf-3695ccdb03ff)

## cache:
![Screenshot 2024-10-06 220415](https://github.com/user-attachments/assets/3d53716b-130a-4600-8f39-8594302d5b69)


## DNS Enumeration:
## DNS Recon:
![Screenshot 2024-10-16 220212](https://github.com/user-attachments/assets/a3a9b1a6-5054-4543-ba44-c6315e3ac258)

## dnsenum:

![Screenshot 2024-10-22 231747](https://github.com/user-attachments/assets/610ce075-4b01-4f81-9465-7d36200eee2b)

![47](https://github.com/user-attachments/assets/b43a4b26-86cc-460a-ab7d-141c2ac4f489)




## smtp-user-enum:

![Screenshot 2024-10-16 221217](https://github.com/user-attachments/assets/66cf4dd3-0eb1-4707-8a11-6a5ab4688bc0)

## nmap –script smtp-enum-users.nse :

![Screenshot 2024-10-16 221351](https://github.com/user-attachments/assets/325926c3-21dc-49b5-bc4f-2e2b44e3e7d3)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

