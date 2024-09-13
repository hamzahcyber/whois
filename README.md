# Python WHOIS Lookup Tool

This project is a simple WHOIS lookup tool built using Python. It allows you to retrieve domain registration information by sending queries to the IANA WHOIS server over a TCP connection. This tool demonstrates fundamental networking concepts and protocol handling within the context of domain management and cybersecurity.

## Features
- **Domain WHOIS Query:** Retrieves domain registration details using the WHOIS protocol.
- **Socket Communication:** Uses Python’s `socket` library to establish TCP connections.
- **Network Programming Example:** Demonstrates the use of low-level network protocols for communication.

## How It Works
1. **TCP Connection:**
   - The tool opens a TCP connection to the IANA WHOIS server (`whois.iana.org`) on port 43.
   
2. **Sending WHOIS Query:**
   - The domain name is sent as a query to the WHOIS server.

3. **Receiving Response:**
   - The server's response, containing the domain's WHOIS information, is retrieved and displayed.

## Requirements
- Python 3.x

## Usage
1. Clone the repository or download the `whois_lookup.py` file.
2. Run the script using Python:
   ```bash
   python whois_lookup.py

