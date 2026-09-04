# Enumeration
Enumeration Techniques

Developed: MOHAMMED AFSAL S

Reg No: 212225040247
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
Following Categories of pen test tools are identified: Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

site: This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain. Following searches for all the sites that is in the domain yahoo.com

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files. Following searches for pdf file in the domain yahoo.com

intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

#DNS Enumeration

##DNS Recon provides the ability to perform: Check all NS records for zone transfers Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT) Perform common SRV Record Enumeration Top level domain expansion

## OUTPUT:
##dnsenum Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record). Get the namservers (threaded). Get the MX record (threaded). Perform axfr queries on nameservers and get BIND versions(threaded). Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”). Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded). Calculate C class domain network ranges and perform whois queries on them (threaded). Perform reverse lookups on netranges (C class or/and whois netranges) (threaded). Write to domain_ips.txt file ip-blocks. This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.

##smtp-user-enum Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.

In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same

#Telnet for smtp enumeration Telnet allows to connect to remote host based on the port no. For smtp port no is 25 telnet 25 to connect and issue appropriate commands

##Output
## nmap –script smtp-enum-users.nse
The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.
# output:
# 1)site

<img width="1467" height="970" alt="image" src="https://github.com/user-attachments/assets/f1e11d75-0e28-4f52-85bc-f52ac2458a38" />

# 2)filetype

<img width="1332" height="902" alt="image" src="https://github.com/user-attachments/assets/d332a69a-32de-4a39-954b-1e8503364116" />

# 3)intext

<img width="1228" height="791" alt="image" src="https://github.com/user-attachments/assets/ae5c81b9-e2db-4de3-827b-203f804d8853" />

# 4)inurl

<img width="1300" height="872" alt="image" src="https://github.com/user-attachments/assets/021ac01e-26e8-44a9-8faf-a32433097ab0" />

# 5)intitle

<img width="1293" height="645" alt="image" src="https://github.com/user-attachments/assets/1198dc8e-ba43-42d3-9ecf-1924fcf543f7" />

# 6)link

<img width="1342" height="866" alt="image" src="https://github.com/user-attachments/assets/c4e5ea96-b545-4a5f-9bd2-3a9197df5b2d" />

# 7)cache

<img width="1151" height="914" alt="image" src="https://github.com/user-attachments/assets/71338f3b-94ad-4c1e-9f96-35176afa19a6" />

# DNS Enumeration

# DNS Recon

<img width="1078" height="636" alt="image" src="https://github.com/user-attachments/assets/cffac1a2-2d28-411e-b26a-3108bd9b6c9a" />

## dnsenum

<img width="742" height="876" alt="image" src="https://github.com/user-attachments/assets/5a3cb25b-4459-4320-8d86-82dc2fedd1d4" />

<img width="677" height="781" alt="image" src="https://github.com/user-attachments/assets/c6b1d308-ee68-40e2-ad3f-35137437f309" />

# smtp-user-enum

<img width="647" height="437" alt="image" src="https://github.com/user-attachments/assets/89775d70-7e7f-4307-9a76-e108306a8592" />

<img width="770" height="775" alt="image" src="https://github.com/user-attachments/assets/c3ff9573-577f-44d4-902b-946186438a22" />

# Telnet for smtp enumeration

<img width="1067" height="492" alt="image" src="https://github.com/user-attachments/assets/07cd2ce3-c2c1-4d22-b38e-e3a90fcfad4b" />

## nmap –script smtp-enum-users.nse <hostname>

<img width="567" height="317" alt="image" src="https://github.com/user-attachments/assets/33072147-5954-4118-9afd-35d98b0a86aa" />

## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

