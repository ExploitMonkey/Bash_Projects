This script is used to find alive subdomains and enumerate them using the following tools:
1. subfinder
2. assetfinder
3. amass (optional)
4. httprobe
5. gowitness
6. nmap

Please make sure all of these tools are downloaded before running this script.

Make sure to make the script executable
CMD: chmod +x ./subrecon.sh

Run script with command:
CMD: ./subrecon <domain>
EX: ./subrecon google.com

After running the script a directory will be made with the domain name as the folder name
In this folder are 3 sub folders subdomain, screenshots and scan containing the results.
