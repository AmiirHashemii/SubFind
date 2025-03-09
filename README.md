# Subdomain Enumerator - Find and Probe Subdomains
SubFind is a Bash script for Linux that automates subdomain enumeration and HTTP probing. It uses popular tools like amass, assetfinder, and subfinder to discover subdomains for a given domain, then leverages httpx to check their HTTP status. The results are saved in a file called subdomains.txt.
    
# Features  
![Screenshot From 2025-03-09 19-24-33](https://github.com/user-attachments/assets/2e66573c-e143-4ac5-989f-50da88b2dbde)  

Subdomain Enumeration: Discovers subdomains using **Sublist3r** **amass**, **assetfinder**, and **subfinder**.  
Deduplication: Sorts and removes duplicate subdomains.  
HTTP Probing: Checks the status of subdomains with **httpx**.  
Output File: Saves all discovered subdomains to **subdomains.txt**.  


# Installation
```
git clone https://github.com/AmiirHashemii/SubFind
```

# Usage
```
./SubFind <Domain> <Options>
```
