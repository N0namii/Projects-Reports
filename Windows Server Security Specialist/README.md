**Description**:  
This project focuses on building a secure Windows Server environment with Active Directory (AD) and conducting penetration testing to identify and mitigate vulnerabilities. The project includes setting up a fully functional AD domain, joining a Windows 10/11 client to the domain, and performing security assessments using tools like Mimikatz, CrackMapExec, and BloodHound. The goal is to develop expertise in both system administration and offensive security techniques.  

**Key Features**:  
- **Windows Server Setup**:  
  - Configure a Windows Server with Active Directory Domain Services (AD DS).  
  - Create Organizational Units (OUs), user accounts, and security groups.  
  - Apply Group Policies for access control and security enforcement.  
- **Domain Integration**:  
  - Join a Windows 10/11 virtual machine to the AD domain.  
  - Test user access and permissions based on group memberships.  
- **Penetration Testing**:  
  - Perform information gathering using Nmap and Enum4linux-ng.  
  - Exploit vulnerabilities using CrackMapExec, Mimikatz, and Kerberoasting.  
  - Conduct lateral movement with Pass-the-Hash (PTH) and WinRM exploitation.  
  - Maintain persistence by creating backdoor accounts.  
- **Analysis and Visualization**:  
  - Use BloodHound to map AD relationships and identify privilege escalation paths.  

**Technologies and Tools Used**:  
- **Windows Server**: Active Directory, DNS, Group Policy.  
- **Penetration Testing Tools**:  
  - Mimikatz: Credential dumping and privilege escalation.  
  - CrackMapExec: SMB and LDAP exploitation.  
  - BloodHound: AD relationship visualization.  
  - Impacket: Kerberoasting and SPN extraction.  
- **Information Gathering**: Nmap, Enum4linux-ng.  
- **Virtualization**: VirtualBox for Windows 10/11 VM.  

**Who Is This Project For?**  
- System administrators looking to secure Windows Server environments.  
- Cybersecurity professionals specializing in Active Directory security.  
- Penetration testers and red teamers focusing on Windows networks.  
- Students and enthusiasts preparing for certifications like OSCP, CEH, or CompTIA Security+.  

---

### **Contents**  
1. **Windows Server and AD Setup**:  
   - Initial configuration: Static IP, hostname, and updates.  
   - Install and configure AD DS, DNS, and OUs.  
   - Create user accounts, security groups, and apply Group Policies.  
2. **Domain Integration**:  
   - Join a Windows 10/11 VM to the AD domain.  
   - Verify domain functionality and test user access.  
3. **Penetration Testing**:  
   - Information gathering with Nmap and Enum4linux-ng.  
   - Exploitation using CrackMapExec, Mimikatz, and Kerberoasting.  
   - Lateral movement with Pass-the-Hash and WinRM exploitation.  
   - Persistence through backdoor account creation.  
4. **Analysis and Visualization**:  
   - Collect AD data using SharpHound.  
   - Visualize AD relationships and attack paths with BloodHound.  

---
