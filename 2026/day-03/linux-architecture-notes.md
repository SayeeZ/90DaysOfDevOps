# Linux Commands

1. Process management commands:
- journalctl -u <service_name> : shows tha logs of specified service
- systemctl start <service_name> : To start a service
- systemctl stop <service_name> : To stop a service
- systemctl status <service_name> : To display the status of service, eg. running
- systemctl restart <service_name> : To restart a service
- ps: shows running processes
- kill <process_id> : to kill a specific process
- top : rovides a real-time, interactive view of running processes and system resource usage (CPU, memory, etc.).

2. File system commands:
- ls : to list contents
- pwd : print current working directory
- cd : change directory
- touch <file_name> : create a new file
- mkdir <dir_name> : create a new directory
- chmod <permissions> : to change file permissions
- rm <file_name> : delete file

3. Networking troubleshooting commands: 
- ping <website> : verifies ip level connectivity
- telnet <ip> <port> : used to check connectivity at a specified port
- ip addr : displays ip address
