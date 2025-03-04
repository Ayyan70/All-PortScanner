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
        
