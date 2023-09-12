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




Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.




## OUTPUT:
![Screenshot 2023-09-12 152308](https://github.com/sakthivel005/InformationGathering/assets/120550359/fb605ffb-4e33-4412-beb4-c71ec1a38825)

## Finding IP adress:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```

## Output:
![Screenshot 2023-09-12 152407](https://github.com/sakthivel005/InformationGathering/assets/120550359/2f7743ba-65d3-4adb-815e-6ba5fc2f764d)

## Finding Hosting Company:
get further detail by using ip2location.com website.
## Output:
![Screenshot 2023-09-12 152510](https://github.com/sakthivel005/InformationGathering/assets/120550359/1233b61a-681d-4d86-9ea5-e93419286f6d)

## History of the wbsite:
## Output:
https://web.archive.org/
![Screenshot 2023-09-12 152622](https://github.com/sakthivel005/InformationGathering/assets/120550359/794c3fb5-1feb-4d85-9900-14f7a71887a1)


## Web server Fingerprint:
## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![Screenshot 2023-09-12 152654](https://github.com/sakthivel005/InformationGathering/assets/120550359/ef6059ac-3575-4f62-a59a-941573720ac3)

## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:
![Screenshot 2023-09-12 152727](https://github.com/sakthivel005/InformationGathering/assets/120550359/c2a20ecd-93d6-4898-a845-eb69b01e2898)

## Whatweb:
```
whatweb infosys.com
whatweb zoho.com
whatweb -v -a 3 172.17.52.201
```
## Output:
![Screenshot 2023-09-12 152759](https://github.com/sakthivel005/InformationGathering/assets/120550359/c0983409-ecb1-4bb2-a398-7e77b7b6c171)

## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```

## Output:
![Screenshot 2023-09-12 152831](https://github.com/sakthivel005/InformationGathering/assets/120550359/6259edf5-ea49-4ab6-95f0-92ad2e2b1866)

## Tracing the Location:

## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```

## Output:
![Screenshot 2023-09-12 152908](https://github.com/sakthivel005/InformationGathering/assets/120550359/b7da0438-b3f6-4da3-8fe6-8c68ac4c0469)



## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:


![Screenshot 2023-09-12 153036](https://github.com/sakthivel005/InformationGathering/assets/120550359/6291f133-9802-4538-8849-77c5134157f6)


## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```

## OUTPUT:

![Screenshot 2023-09-12 153100](https://github.com/sakthivel005/InformationGathering/assets/120550359/a99bd6ba-f88d-4173-a03a-c8e439d61995)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
