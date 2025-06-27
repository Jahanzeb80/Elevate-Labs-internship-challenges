# Day04 - UFW Firewall Setup and Commands

#task01 Open firewall configuration tool (Windows Firewall or terminal for UFW)
sudo apt install ufw

#task02. List current firewall rules
sudo ufw status numbered

#task03 add a rule to block inbound traffic on a specific port (e.g., 23 for Telnet)
Block inbound traffic on port 23 (Telnet) 
sudo ufw deny 23/tcp  (you can specify port number or service )

#task04 Test the rule by attempting to connect to that port locally or remotely
Test the rule    (locally)
telnet localhost 23

Test the rule (remotly)
telnet <ip> 23

#task05 add rule to allow SSH (port 22) if on Linux.
sudo ufw allow 22/SSH

#task06 Remove the test block rule to restore original state.
sudo ufw delete deny 23/tcp

sudo ufw status numbered
sudo ufw delete <rule_number>


#task07 all the thing i documents here above 

#task08 Summarize how firewall filters traffic.
firewall filters the traffic using rules,the rules which helps to configure its settings and it learns what traffic to allow and what traffic to deny 
what if the adminitrator don't sets rules?.   firewall will filters the traffic as default settings 














