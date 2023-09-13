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

# Pen Test Tools Categories:

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible     information     about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.
## OUTPUT:

![1](https://github.com/karthickop6/InformationGathering/assets/72570119/9cbc7863-f798-4165-aed6-62bf11b6c45a)


Finding IP address:

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```

# Output:
![0](https://github.com/karthickop6/InformationGathering/assets/72570119/b08a0b58-aebf-4b3f-afe8-2a5e5ec5061c)

## Finding Hosting Company

get further detail by using ip2location.com website.

## Output:
![2](https://github.com/karthickop6/InformationGathering/assets/72570119/580b2b78-de65-4eb7-bbda-16c7acb29042)

## History of the website:
## Output:
https://web.archive.org/
![3](https://github.com/karthickop6/InformationGathering/assets/72570119/0d0686e5-56cc-4825-a589-43f808697424)



## Webserver Fingerprinting:
## Netcat:
```
nc 172.17.52.118 80
```

## Output:
![4](https://github.com/karthickop6/InformationGathering/assets/72570119/308b76e9-6d8d-41a2-8092-9c11591ae91a)



## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```

# Output:
![5](https://github.com/karthickop6/InformationGathering/assets/72570119/f2ada1f9-5bc8-4827-864a-033a9f86aa61)


Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```


Output:
![6](https://github.com/karthickop6/InformationGathering/assets/72570119/0cc0f251-f7a7-422c-8de7-0cec363b3e0f)


httprint:

```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```

output:

![7](https://github.com/karthickop6/InformationGathering/assets/72570119/a0438894-bf49-4344-9f6b-807d9bbbf75f)

Tracing the Location

TCP Traceroute:

```
sudo traceroute -T www.saveetha.ac.in
```
Output:



UDP Traceroute:

Output:


![8](https://github.com/karthickop6/InformationGathering/assets/72570119/d049c8cd-98bb-4c45-ac09-dbeab86904cb)

ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
Output:
![9](https://github.com/karthickop6/InformationGathering/assets/72570119/856b526d-54fc-4335-a0e3-dcb598ca7749)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
