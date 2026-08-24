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
Following searches for all the sites that is in the domain tesla.com

<img width="1917" height="893" alt="image" src="https://github.com/user-attachments/assets/e4026844-704e-4d16-b315-7a1778e778b9" />

filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain tesla.com

<img width="1916" height="957" alt="image" src="https://github.com/user-attachments/assets/04ea84f8-ca5b-4fb9-ae91-d93e4fab6dc0" />


intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
<img width="1908" height="901" alt="image" src="https://github.com/user-attachments/assets/ffebf126-9ce5-46c7-adbc-80ebb096b2b3" />




inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
<img width="1917" height="912" alt="image" src="https://github.com/user-attachments/assets/0633670d-284c-4862-84d6-ad4a06fd0d0d" />

intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
<img width="1877" height="573" alt="image" src="https://github.com/user-attachments/assets/3eee6425-881d-4e5b-827e-9831770ee6a4" />

link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
<img width="1917" height="905" alt="image" src="https://github.com/user-attachments/assets/b9604589-26a5-4f48-9b51-bd7d7b8ef5fc" />

cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
<img width="1891" height="897" alt="image" src="https://github.com/user-attachments/assets/ab6c2b6d-575f-4082-a5d4-9edd559b26fc" />

 
#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
<img width="685" height="612" alt="image" src="https://github.com/user-attachments/assets/c9b7edfa-cd6c-4848-a9a6-3ce55306a639" />




##dnsenum
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
<img width="678" height="552" alt="image" src="https://github.com/user-attachments/assets/ec5b82f4-9085-4be8-b38a-6aba25b0ea94" />


##smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same
<img width="680" height="552" alt="image" src="https://github.com/user-attachments/assets/16c73047-10ca-4845-8362-372e752ce4ed" />


#Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ##Output
 <img width="717" height="97" alt="image" src="https://github.com/user-attachments/assets/61eb5ba0-7d6c-494e-b239-748efac986c9" />

  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
<img width="706" height="567" alt="image" src="https://github.com/user-attachments/assets/180fc78d-4ff8-44b4-8bd6-16112fc29e18" />


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

