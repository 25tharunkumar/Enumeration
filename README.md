# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 
NAME : Tharun kumar.M

REG NO: 212222100056

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

## Output:
![Screenshot 2024-09-25 134445](https://github.com/user-attachments/assets/5a52717a-e8b7-4624-b095-147fc3b8e72d)



filetype: This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com
## Output:
![Screenshot 2024-09-25 134639](https://github.com/user-attachments/assets/08ce32de-c1ad-429c-8497-63973f4acdc9)




intext: This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.
## Output:
![Screenshot 2024-09-25 134744](https://github.com/user-attachments/assets/d9662994-4363-43a8-8066-6432274dd1cc)



inurl: This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.
## Output:
![Screenshot 2024-09-25 134822](https://github.com/user-attachments/assets/6fdbce7d-3b6a-4524-bf6a-9624e47612ae)


intitle: This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.
## Output:
![Screenshot 2024-09-25 134856](https://github.com/user-attachments/assets/dbb55d3b-868d-44c5-a793-bdb4d18d6498)


link: This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.
## Output:
![Screenshot 2024-09-25 134930](https://github.com/user-attachments/assets/b3bcf3e2-647c-4ffa-a4de-6d72cd9c6be8)


cache: This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.
## Output:
![Screenshot 2024-09-25 135127](https://github.com/user-attachments/assets/014d2a82-f1cd-4be7-9459-a8cae66bd90e)

 
#DNS Enumeration


##DNS Recon
provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion
## OUTPUT:
![Screenshot 2024-09-25 233643](https://github.com/user-attachments/assets/cceec0e3-dfa3-4817-a3ef-6934e9300dd1)







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
## Output:
![Screenshot 2024-09-25 233746](https://github.com/user-attachments/assets/80af920b-3a46-4ed1-8a94-8215a45be295)
![Screenshot 2024-09-25 233813](https://github.com/user-attachments/assets/3032b569-7595-4bb8-b2fe-07c80f89fe9f)





## smtp-user-enum
Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.


In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:

select any username in the first column of the above file and check the same
## Output:
![Screenshot 2024-09-25 233932](https://github.com/user-attachments/assets/e7caabed-8f8d-4429-94b0-6e87b6bf0fb9)



## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands
  
 ## Output:
![Screenshot 2024-09-25 234024](https://github.com/user-attachments/assets/b6f36f10-5e64-4a63-9de2-092f329c7789)

  
  

## nmap –script smtp-enum-users.nse <hostname>

The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


## OUTPUT:
![Screenshot 2024-09-25 234419](https://github.com/user-attachments/assets/5efd6a27-fb1d-4bd7-86e5-82b1fb4f02ee)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

