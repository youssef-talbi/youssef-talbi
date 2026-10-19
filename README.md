<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0b3d5c,100:00b4d8&height=200&section=header&text=Youssef%20Talbi&fontSize=46&fontColor=ffffff&fontAlignY=36&desc=Cybersecurity%20engineer%20in%20training%20%C2%B7%20TEK-UP%202027&descSize=17&descAlignY=58&animation=fadeIn" width="100%" alt="Youssef Talbi, cybersecurity engineering student at TEK-UP, class of 2027"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=19&pause=1400&color=00B4D8&center=true&vCenter=true&width=620&lines=Cybersecurity+engineering+student;Cloud%2C+DevOps+and+DevSecOps;Detection%2C+response+and+SOC+automation;Network+security+and+Zero+Trust;Pentesting+and+malware+analysis" alt="Rotating line: cybersecurity engineering student; cloud, DevOps and DevSecOps; detection, response and SOC automation; network security and Zero Trust; pentesting and malware analysis"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/talbi-youssef"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn profile"/></a>
  <a href="mailto:iam.yousseftalbi@gmail.com"><img src="https://img.shields.io/badge/Email-0d1117?style=for-the-badge&logo=gmail&logoColor=00B4D8" alt="Send me an email"/></a>
  <img src="https://img.shields.io/badge/Tunis%2C%20Tunisia-0d1117?style=for-the-badge&logo=googlemaps&logoColor=00B4D8" alt="Based in Tunis, Tunisia"/>
</p>

I'm a final-year cybersecurity engineering student at TEK-UP University in Tunis, graduating in 2027. My projects cover a lot of ground in security: detection and automated response on AWS, Kubernetes and DevSecOps pipelines, Zero Trust access, network security, SOC automation, malware analysis and penetration testing. Cloud and DevOps are where I'm strongest, and I bring that to whatever security problem I'm working on. Before TEK-UP I studied Information Systems Engineering at ISSAT Kairouan.

I'm open to cybersecurity roles in Europe, whether that's security engineering, DevSecOps, SOC or infrastructure security, and to a six-month end-of-studies (PFE) internship starting January 2027.

## Experience

**Security intern**, Attijari Bank, security department (ended September 2026)
Built a network vulnerability scanner in Go for the internal network. It sweeps VLANs for obsolete TLS (1.0 and 1.1), cleartext services such as Telnet and FTP, and SMBv1 hosts, and confirms MS17-010 exposure through Nmap.

**Software development intern**, Aftercode (2024)

**Data science intern**, Euro Tech Conseil (2023)
Trained a recurrent neural network to predict traffic jams from real Waze data, from raw data cleaning to the final model.

## Projects

<!-- Link each title once its repo is public: [Name](https://github.com/youssef-talbi/REPO-NAME) -->

| Project | What I did | Stack |
|---|---|---|
| **AWS threat detection lab** | Ran real attacks (port scans, SSH brute force) against an AWS environment and had GuardDuty catch them. An EventBridge rule triggers a Lambda that isolates the instance and alerts me through SNS in under 30 seconds. All of it is Terraform, with tfsec running in GitHub Actions before each deploy. | AWS · Terraform · Python · GitHub Actions |
| **[VLAN posture scanner](https://github.com/youssef-talbi/vlan-posture-scanner)** | Single Go binary with a CLI and a local web dashboard. Flags weak TLS, cleartext protocols and SMBv1 across network segments. When a host refuses an anonymous SMB session, it reports the patch state as undetermined instead of guessing. | Go · Nmap |
| **Zero Trust access platform** *(team of 3, in progress)* | My part is device posture with osquery and continuous verification in Wazuh, which revokes a user's Keycloak session or Ziti identity when their device drifts out of policy. I also own the attack demos and the overall architecture. | Keycloak · OpenZiti · step-ca · OPA · Wazuh · osquery |
| **Kubernetes DevOps pipeline** | Took a microservices app from VMs to containers to Kubernetes: a 3-node kubeadm cluster, minikube, then EKS, deployed through Jenkins with SonarQube checks. | Docker · Kubernetes · EKS · Jenkins · SonarQube |
| **Secure IP/MPLS backbone** | Multi-site carrier backbone in GNS3 with L3 MPLS VPNs (MP-BGP VPNv4, VRF) isolating each customer, AAA through FreeRADIUS, SNMPv3 monitoring and HSRP failover. | GNS3 · MPLS · BGP · FreeRADIUS · Zabbix |
| **AI-augmented SOC** *(team of 4)* | I set up pfSense as the lab's central firewall and wrote the Shuffle SOAR workflows that block attacking IPs over SSH and send Telegram alerts. | pfSense · Shuffle · Wazuh |

<details>
<summary>More projects</summary>

<br>

| Project | What I did | Stack |
|---|---|---|
| **Odoo ERP high availability** | HA architecture for an ERP, designed against ISO 27001 ISMS requirements and built from a hardened RHEL 9.5 template. | RHEL 9 · Docker Compose · Odoo |
| **Malware analysis: NjRAT and WannaCry** | Static, dynamic and sandbox analysis of both samples. Extracted IOCs, network behaviour and registry persistence, mapped to MITRE ATT&CK. | PEStudio · dnSpy · ANY.RUN · Wireshark |
| **Kioptrix penetration tests** | Levels 1 to 4 (Samba RCE, SQL injection, command injection, privilege escalation), written up as formal reports. | Metasploit · Nmap · SQLmap |
| **[HR management system](https://github.com/youssef-talbi/HR-Management-System)** | Web HR app with employee records, facial-recognition attendance, leave and payroll. | Python · Flask |
| **[Traffic jam prediction](https://github.com/youssef-talbi/Traffic_Jam_Prediction_Internship)** | The deep learning model from my Euro Tech Conseil internship. | Python · TensorFlow |

</details>

## Certifications

<p>
  <img src="https://img.shields.io/badge/AWS-Solutions%20Architect%20Associate-FF9900?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS Certified Solutions Architect Associate (SAA-C03)"/>
  <img src="https://img.shields.io/badge/Red%20Hat-RHCSA-EE0000?style=for-the-badge&logo=redhat&logoColor=white" alt="Red Hat Certified System Administrator"/>
  <img src="https://img.shields.io/badge/Red%20Hat-RHCE%20(Ansible)-EE0000?style=for-the-badge&logo=ansible&logoColor=white" alt="Red Hat Certified Engineer (Ansible)"/>
  <img src="https://img.shields.io/badge/INE-eJPTv2-1f2937?style=for-the-badge&logoColor=white" alt="INE eJPTv2"/>
</p>

In progress: AWS Security Specialty. Next: CKA and ISO 27001 Lead Implementer.

## Tools I use

<p>
  <img src="https://skillicons.dev/icons?i=aws,terraform,kubernetes,docker,ansible,jenkins,githubactions,linux,bash,python,go&theme=dark" alt="AWS, Terraform, Kubernetes, Docker, Ansible, Jenkins, GitHub Actions, Linux, Bash, Python, Go"/>
</p>

On the security side: Wazuh, Keycloak, pfSense, Shuffle SOAR, Nmap, Burp Suite, Wireshark and Metasploit.

## Right now

Building the continuous-verification layer of the Zero Trust platform, working through PortSwigger's Web Security Academy, and studying for AWS Security Specialty.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:00b4d8,50:0b3d5c,100:0d1117&height=100&section=footer" width="100%" alt=""/>
</p>
