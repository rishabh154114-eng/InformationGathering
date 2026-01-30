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


## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output

<img width="1867" height="882" alt="image" src="https://github.com/user-attachments/assets/03dfd560-4718-4428-b8d7-9782ef6a82e1" /></br>


## Finding Hosting Company
get further detail by using ip2location.com website.
##output
<img width="1903" height="852" alt="image" src="https://github.com/user-attachments/assets/6b08543b-9698-40c9-bff6-90810bf00c37" /></br>



## History of the website:
## output
https://web.archive.org/

<img width="1908" height="1032" alt="image" src="https://github.com/user-attachments/assets/ae1fb601-05ae-4be8-9a5f-21d4343274da" /></br>

# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
<img width="747" height="505" alt="image" src="https://github.com/user-attachments/assets/70ca4156-648d-47db-b2ef-e5ff2d7abef3" />



## nmap:
###output


## Whatweb
### output


## httprint
### output




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.instragram.com
## output


## UDP Traceroute:
sudo traceroute -U www.instagram.com
## output



## ICMP Traceroute:
sudo traceroute  www.instragram.com
## output






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
