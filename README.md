**Mehul Mahaveer Nahar**  
**Company**: Code Tech IT Solutions  
**Employee ID**: CT08DS7233  
**Domain**: Cyber Security & Ethical Hacking  
**Project Duration**: August to September 2024

---
## Project: Vulnerability Scanning Tool
![Screenshot (30)](https://github.com/user-attachments/assets/235eead2-5c72-4188-bd92-5097f5684537)

## Project Overview

The **Vulnerability Scanning Tool** is a web-based application designed to help network administrators and security professionals scan websites or networks for common security vulnerabilities. The tool checks for issues such as open ports, outdated software, and potential misconfigurations. This project aims to create an easy-to-use, browser-based vulnerability scanner that simulates common scanning techniques used in penetration testing and cybersecurity assessments.

### Objective

The primary objective of this project is to:
- **Identify Potential Vulnerabilities** such as open ports and outdated software.
- **Assist Users in Securing Their Systems** by providing real-time results of the vulnerabilities detected.
- **Promote Cybersecurity Awareness** by enabling easy vulnerability scanning for websites and networks.

### Key Activities

During this project, the following tasks were undertaken:
1. **Design and Implementation**: Created a user-friendly interface for vulnerability scanning using HTML, CSS, and JavaScript.
2. **Port Scanning**: Simulated the scanning of common open ports (HTTP, HTTPS, FTP, SSH, etc.) to detect potential vulnerabilities.
3. **Software Version Checks**: Implemented simulated checks for outdated software versions.
4. **Misconfiguration Scanning**: Checked for common security misconfigurations, such as SSL certificate issues and missing HTTP security headers.
5. **Real-Time Feedback**: Displayed real-time results to the user on vulnerability status (safe or vulnerable).

### Features

- **Simulated Port Scanning**: Detects open ports commonly targeted by attackers, such as HTTP (80), HTTPS (443), FTP (21), and SSH (22).
- **Outdated Software Detection**: Simulates checks for outdated software versions like Apache HTTP Server.
- **Misconfiguration Detection**: Identifies common security misconfigurations such as missing HTTP Strict Transport Security (HSTS) and expired SSL certificates.
- **User-Friendly Interface**: The tool is browser-based and can be run locally using any modern browser like Chrome.
- **Real-Time Results**: Vulnerabilities are highlighted immediately as the scan progresses.

### Technologies Used

- **Frontend**: HTML, CSS
- **Scripting**: JavaScript
- **Testing Platform**: Chrome Browser

### How the Tool Works

1. **Port Scanning**: The tool checks for known open ports critical to securing network communication. This helps detect any open entry points that may be exploited.
   
2. **Outdated Software Detection**: The tool checks to identify if the target website or network is running potentially vulnerable versions of common software.

3. **Misconfiguration Checks**: It checks for common issues like missing or incorrectly configured security headers, expired SSL certificates, and similar vulnerabilities that may leave a system exposed.

### Key Insights

- **Port Scanning**: Open ports, if left unsecured, are among the most vulnerable points in a system's defenses. The tool highlights these potential attack vectors effectively.
- **Outdated Software**: Running outdated versions of software opens the door for known vulnerabilities to be exploited. The tool flags such risks, helping admins stay proactive about updating systems.
- **Configuration Management**: A critical part of securing any system is ensuring proper configurations, such as enforcing SSL/TLS protocols and proper headers. This tool provides basic insights into misconfigurations that can be easy to overlook.

### Installation and Usage

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/MehulMahaveerNahar/vulnerability-scanning-tool.git
   ```

2. **Run the Tool**:
   Open the `index.html` file in your browser (preferably Chrome). No installation is required as this is a web-based tool.

3. **Scan for Vulnerabilities**:
   - Enter a website URL or IP address in the input field.
   - Click "Scan for Vulnerabilities."
   - The results of open ports, outdated software, and misconfigurations will be displayed in real time.

### Future Enhancements

- **Real Port Scanning**: Integrating with backend services like `nmap` or `openVAS` for real-time port scanning.
- **Integration with Security Databases**: Connect the tool to live security databases to get up-to-date information on software vulnerabilities.
- **Reporting**: Add the ability to generate and export scan reports for audit purposes.
- **Full Network Scanning**: Extend the tool’s capability to scan an entire network range rather than individual domains or IPs.


