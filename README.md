A fast and efficient Bash-based port scanner that leverages `nmap` for scanning a wide range of ports on a given IP address or domain. This script provides real-time notifications for open ports using `zenity` and features several optimizations for speed, including parallel scanning and aggressive timing.

### Features:
- Scans all ports or a customizable port range (default: 1-65535).
- Fast scanning with optimized settings using `nmap`.
- Real-time pop-up notifications for open ports using `zenity`.
- Supports IP addresses and domain names.
- Aggressive timing (`-T4`), reduced retries (`--max-retries 1`), and increased packet rate (`--min-rate 1000`) for faster scans.
- Option for terminal output in headless environments.
- Compatible with most Linux distributions.

### Usage:
1. Clone the repository:
   ```bash
   git clone https://github.com/username/fast-port-scanner.git  
 
 Make the script executable: {chmod +x port_scanner_nmap.sh} 
 
 Run the script:{./port_scanner_nmap.sh <target_ip_or_website> [<start_port> <end_port>] }          
 
 Example:./port_scanner_nmap.sh example.com
        ./port_scanner_nmap.sh 192.168.1.1 80 100 
        

### Explanation:
- **Repository Name**: `fast-port-scanner` reflects the key feature of the script: speed. It’s simple, easy to remember, and communicates the project’s primary goal.
  
- **Description**: The description provides a concise but detailed summary of what the project is, highlighting key features like speed optimizations, support for domain names, and real-time notifications for open ports. 

- **Features**: Outlines the functionality of the script and explains why the optimizations are useful for speeding up the scan process.

- **Usage**: Offers clear instructions for cloning the repo, making the script executable, and running it. It also includes example commands to help users get started.

- **Optimizations**: Highlights the improvements made in the script to maximize scan speed, like aggressive timing and reduced retries.

- **Prerequisites**: Lists necessary tools (`nmap` and `zenity`) so users can quickly identify and install them if needed.

- **License and Contributions**: Encourages collaboration and makes it clear that contributions are welcome.

This description provides a comprehensive, user-friendly overview of the project that will help others understand its purpose and use it efficiently.
