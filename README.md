# Domain Warrior

Domain Warrior is a command-line tool for performing various tasks related to domain reconnaissance. It helps you gather information about a domain, including DNS records, IP addresses, SSL certificates, web server headers, and more.
Features

    Zone Transfer: Attempt a DNS zone transfer.
    DNS Resolution: Resolve DNS records for a domain.
    IP Address Lookup: Find the IP address associated with a domain.
    MX Records: Check Mail Exchanger (MX) records for a domain.
    TXT Records: Check Text (TXT) records for a domain.
    Name Server (NS) Records: Check name server records for a domain.
    SSL Certificate Information: Retrieve SSL certificate details.
    Web Server Headers: Fetch web server header information.
    Subdomain Enumeration: Perform subdomain enumeration with Subfinder.
    httprobe: Check available domains using httprobe.
    ASN Tracking: Track Autonomous System Numbers (ASNs) using Amass.
    Reverse DNS Lookup: Perform reverse DNS lookup.
    Reverse WHOIS Lookup: Perform reverse WHOIS lookup with the "whois" tool.

## Usage

    Clone or download the repository.
    Run the script with ./warrior.
    Follow the prompts and provide the domain you want to query.

## Note: Ensure you have the required dependencies like Subfinder, httprobe, Amass, and the "whois" tool installed on your system.
Dependencies

    Subfinder: https://github.com/projectdiscovery/subfinder
    httprobe: https://github.com/tomnomnom/httprobe
    Amass: https://github.com/OWASP/Amass
    "whois" tool: Install via your package manager (e.g., apt-get install whois).
