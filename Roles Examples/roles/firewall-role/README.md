This role installs and manages firewalld, opens the required ports using a loop, and 
uses a handler to restart the service only when changes occur. 
Separating the restart into handlers/main.yml keeps the role modular and avoids unnecessary service restarts. 
This is a cleaner and more production-friendly approach to firewall automation.
