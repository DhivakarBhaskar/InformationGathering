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
<img width="722" height="677" alt="image" src="https://github.com/user-attachments/assets/e5c0f8e8-c27e-4d16-bd85-afd5209ea953" />



## History of the website:
## output

<img width="757" height="807" alt="image" src="https://github.com/user-attachments/assets/4de8159c-9696-4c04-92ed-c4669e355a1e" />


# Webserver Fingerprinting:

## Netcat:
sudo nc chatgpt.com 80
GET / HTTP/1.1
Host: chatgpt.com

<img width="772" height="332" alt="image" src="https://github.com/user-attachments/assets/3e093e92-6cc4-465b-b222-606921fa68d8" />


## nmap:
nmap -sL chatgpt.com
###output
<img width="811" height="196" alt="image" src="https://github.com/user-attachments/assets/065bfe0c-9c77-4281-a73e-b652c168f51f" />


## Whatweb
nmap -sL chatgpt.com
### output

<img width="805" height="135" alt="image" src="https://github.com/user-attachments/assets/30c33522-1151-4186-b53c-b0fa47fc95d7" />

## httprint
httprint -h https://chatgpt.com/ -s /usr/share/httprint/signatures.txt -P0 -t 30000
### output

<img width="810" height="271" alt="image" src="https://github.com/user-attachments/assets/66bd7430-7032-4004-9c50-80d79d4fcb6a" />



# Tracing the Location
TCP Traceroute:
sudo traceroute -T -m 12 -q 1 -w 2 chatgpt.com
## output

<img width="810" height="137" alt="image" src="https://github.com/user-attachments/assets/91bc436a-6669-4eeb-bf59-36bf98bdf499" />

## UDP Traceroute:
sudo traceroute -U -m 12 -q 1 -w 2 chatgpt.com
## output
<img width="807" height="323" alt="image" src="https://github.com/user-attachments/assets/1cdb358d-5781-4ded-a11a-1397766f1494" />



## ICMP Traceroute:
sudo traceroute -I -m 12 -q 1 -w 2 chatgpt.com
## output
<img width="808" height="136" alt="image" src="https://github.com/user-attachments/assets/88931c74-abc1-4197-ace7-59080a8978bd" />






## RESULT:
The information gathering techniques tools/procedure were  identified successfully
