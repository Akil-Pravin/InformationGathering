# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2026-01-31 144957" src="https://github.com/user-attachments/assets/731d4061-a3a5-418e-9c70-d019f74cda83" />




## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of netflix.com.
##output:
<img width="1484" height="459" alt="Screenshot 2026-01-31 142021" src="https://github.com/user-attachments/assets/3dd6ac4d-59fd-4499-8f58-4d7009068748" />



## Finding Hosting Company
get further detail by using ip2location.com website.
##output:
<img width="1920" height="1080" alt="Screenshot 2026-01-31 141912" src="https://github.com/user-attachments/assets/030b4a1b-9643-424a-b08e-662291693b9f" />



## History of the website:
https://web.archive.org/
## output:
<img width="1920" height="1080" alt="Screenshot 2026-01-31 140557" src="https://github.com/user-attachments/assets/3a1170de-f7d6-4a5b-bc06-755e3e30a74a" />



# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
## output: 
<img width="1919" height="622" alt="Screenshot 2026-01-31 135330" src="https://github.com/user-attachments/assets/3a2bfc78-0b50-4abb-adc2-48e2b0f998ae" />



## nmap:
###output:
<img width="1875" height="366" alt="Screenshot 2026-01-31 144252" src="https://github.com/user-attachments/assets/bc15cdd1-fa9b-4da2-b450-e78485910069" />


## Whatweb
### output:
<img width="1909" height="596" alt="Screenshot 2026-01-31 135636" src="https://github.com/user-attachments/assets/27d1f145-48a9-4644-aa58-18525e407048" />



## httprint
### output:




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output:
<img width="1919" height="126" alt="Screenshot 2026-01-31 135839" src="https://github.com/user-attachments/assets/8022dcdc-7fb4-49cd-82ae-a195f8fffe2e" />


## UDP Traceroute:
sudo traceroute -U www.google.com
## output:
<img width="1915" height="643" alt="Screenshot 2026-01-31 140009" src="https://github.com/user-attachments/assets/98ae9287-8b23-4d7b-96c2-9896a0089f80" />



## ICMP Traceroute:
sudo traceroute  www.google.com
## output:
<img width="1919" height="547" alt="Screenshot 2026-01-31 140114" src="https://github.com/user-attachments/assets/0c697623-4833-4237-b671-af06cc119902" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
