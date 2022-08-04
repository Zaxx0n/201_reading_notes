# Powershell
Why is Powershell important?
- You can automate or execute advanced operations via terminal in Windows systems 
- Generally, it is  used by systems administrators and engineers
- Attackers use PowerShell to navigate through environments, knowing how        
    attackers use the tool helps to defend against attacks. 
- Also, it looks good on a resume! 


Generally some of the best practice are to:
Same reasons developers put out software updates - to fix problems discovered with the software.
What does it mean to upgrade an OS?

Changing the verseion of the installed OS to a more current one.
Windows in-place upgrades are messier than clean installs; more bugs, but also more convenient = faster.
Clean install wipes everything off the drive and performs a fresh, first-time OS install.
Remote Access
Why might we deploy remote access to a computer system?

Work from home
Virutal Desktop Infrastructure (VDI)
Hosting desktop environments on a single server
Extremely convenient for the end user
Can be costly
Attaching local physical devices can be a hassle
Example: Citrix
Access company-hosted resources
Access cloud resources
Systems administration
Attaching local devices can be a hassel

What does remote access for end user look like when offsite?

Commercial remote desktop products
TeamViewer, Splashtop, GoToMyPC (third party)
Native protocols
SSH, RDP
What is required to use RDP from outside the network?

A Virtual Private Network (VPN) encrypts traffic over the internet allowing secure remote access to a host in a private network.
like a tunnel that connects router to pc
Port forwarding

Ports are connections/tunnels
Forwards all port traffic to the LAN PC
Not ideal for most business environments, but can be good in home networks
Not ideal for business environments, but can be useful for home networks i.e. gaming
forward to MS (my server) - ip address
What is most useful for a sysadmin?

Desktop or shell
Powershell can use Windows Remoting
Often referred to as WinRM

This is encrypted natively and supports SSL as

Utilizes port 5985 and for SSL port 5986

SSL secures web traffic