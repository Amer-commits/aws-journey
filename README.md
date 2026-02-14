🌩️ Cloud Foundations – ##AWS & Linux Infrastructure

📌 Overview

This repository documents my foundational learning in Cloud Computing and Linux server administration.

 #Focus areas in this section:
- Cloud service models (IaaS, PaaS, SaaS)
- Virtual server deployment
- SSH-based remote access


Goal to Build strong infrastructure fundamentals before  I move deeper into AWS services.
##☁️Cloud Fundamentals
#Cloud computing concepts and benefits
Service models:
IaaS
PaaS
SaaS
Understanding abstraction of compute, storage, and networking

##🖥️ Virtual Server Deployment
- Deployed a Linux virtual machine and accessed it remotely.
Tasks Performed:
- Created cloud account
- Deployed Linux instance
- Enabled Two-Factor Authentication
- Connected via SSH using PuTTY
- 🔐 SSH & Server Security (PuTTY – Windows)
- Connected to the remote server using PuTTY (SSH).
##Commands Executed :

Bash
mkdir -p ~/.ssh
chmod 700 ~/.ssh
touch ~/.ssh/authorized_keys
chmod 600 ~/.ssh/authorized_keys
cd /root
ls -la
nano ~/.ssh/authorized_keys

what i did in above commands:
- Security Configuration Created 
- .ssh directory
- Configured correct file permissions
- Added SSH public key
- Read and write permissions edited
- Secured root access
Key Learning: 
Understanding Linux file permissions (700 vs 600) was critical in making SSH key authentication work properly.
| Linode Concept      | AWS Equivalent                |
|---------------------|------------------------------|
| Linode VM           | Amazon EC2                  |
| Linode Firewall     | EC2 Security Group          |
| Linode TFA          | AWS MFA                     |
| SSH Access          | EC2 SSH / Instance Connect  |
| Instance Dashboard  | EC2 Instance Details        |

This helped me understand that cloud fundamentals are always same even across providers.
##NEXT STEPS
🐧 Linux Foundations:
- Linux filesystem structure
- Directory navigation
- Maintenance commands
- User account management
- Creating non-root users
- Securing user accounts
- Disabling root login
