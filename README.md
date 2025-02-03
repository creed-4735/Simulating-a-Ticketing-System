# Simulating a Ticketing System 

## Objective

This project simulates a ticketing system using Zammad to demonstrate security hardening techniques and troubleshooting processes found in a real-world IT environment. By configuring and securing the platform, the project highlights best practices for access control, incident response, and system resilience. It serves as a showcase of hands-on cybersecurity skills, emphasizing the ability to identify, mitigate, and resolve security vulnerabilities within a service management system.

### Skills Learned
- Virtualization
- Access Control and User Management (Linux Administration)
- Security Hardening 
- Incident Response and Troubleshooting
- Log Anaylsis and Monitoring
- Documentation and Reporting
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used
- VMWware Workstation Player
- Ubunti Server LTS (Linux)
- Windows 11
- Zammad
- Docker/Docker Compose
- PostgreSQL
- Elasticsearch/Redis
- Nginx
- SSL
- Splunk


## Steps
- Create and Prepare Ubuntu Server LTS in VMWare:

After downloading Ubuntu from a reliable and secure source. Input the image file into VMWare and launch the software. Configure Ubuntu as needed.

<img src="https://github.com/user-attachments/assets/bce2e7e4-e7cd-4438-903b-d02b45e20cd3" width="800">

- Installing Docker , Docker Compose , and all necessary dependencies:

 Docker simplifies the setup process and helps prevent conflicts with existing system packages, particularly when setting up complex environments. It can containerize services such as PostgreSQL, Elasticsearch, Ruby, Node.js, and Redis, allowing them to run independently but interact with each other as needed.
<img src="https://github.com/user-attachments/assets/2b9094dd-91ef-440b-9659-10ffc6311587" width="800">

- Ensure that Docker and all necessary dependencies are active:
<img src="https://github.com/user-attachments/assets/1d334021-c052-4b6b-a3b1-80ab9c3f20f0" width="800">

- Install and Deploy Zammad utilizing Docker:

Install Zammad within Docker by cloning a repository from the official Zammad Docker github. Then access Zammad from a web browser using the IP address of the instance within another VM (Windows 11).

<img src="https://github.com/user-attachments/assets/e8ee4449-2876-43d6-8896-883c2cebae00" width="800">



