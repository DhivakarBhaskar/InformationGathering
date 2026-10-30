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
<img width="808" height="277" alt="image" src="https://github.com/user-attachments/assets/9146c51f-e23c-4f92-84c0-a6ec5d46feb4" />



## Finding Hosting Company
get further detail by using ip2location.com website.
##output

<img width="757" height="807" alt="image" src="https://github.com/user-attachments/assets/4de8159c-9696-4c04-92ed-c4669e355a1e" />


## History of the website:
## output
<img width="722" height="677" alt="image" src="https://github.com/user-attachments/assets/e5c0f8e8-c27e-4d16-bd85-afd5209ea953" />



# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com



## nmap:
###output


## Whatweb
### output


## httprint
### output




# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output


## UDP Traceroute:
sudo traceroute -U www.google.com
## output



## ICMP Traceroute:
sudo traceroute  www.google.com
## output






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
