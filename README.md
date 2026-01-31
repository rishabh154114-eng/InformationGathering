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

<img width="1867" height="882" alt="image" src="https://github.com/user-attachments/assets/03dfd560-4718-4428-b8d7-9782ef6a82e1" /></br>
## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
##output

<img width="1066" height="307" alt="image" src="https://github.com/user-attachments/assets/a7eebc80-6560-462f-93aa-48ba28df863f" /></br>


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
###output </br>
![WhatsApp Image 2026-01-31 at 08 12 26](https://github.com/user-attachments/assets/e711e398-e7d5-4548-8be2-36217fea9478)</br>

## Whatweb
### output
![WhatsApp Image 2026-01-30 at 10 52 35](https://github.com/user-attachments/assets/d7fb0edf-9c5a-4c92-b7e7-b0f914d91999)



## httprint
### output

![image](https://github.com/RahulKrishna05/InformationGathering/assets/162027231/85279b09-2753-40c3-b813-e946165370b3) </br>


# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.instragram.com
## output
<img width="1148" height="561" alt="image" src="https://github.com/user-attachments/assets/8e436fb7-7950-4241-82f2-2dd20efec4a0" />


## UDP Traceroute:
sudo traceroute -U www.instagram.com
## output

<img width="1451" height="671" alt="Screenshot 2026-01-30 104153" src="https://github.com/user-attachments/assets/a54c99a7-55e1-4cf0-832d-5fbe0cb75f09" />

## ICMP Traceroute:
sudo traceroute  www.instragram.com
## output

<img width="1257" height="592" alt="image" src="https://github.com/user-attachments/assets/87bc6884-8dba-465b-bae2-723e7af1614d" /> </br>





## RESULT:
The information gathering techniques tools/procedure were  identified successfully
