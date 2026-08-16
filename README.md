# SOC-HOME-LAB
# SOC Home Lab

A virtualized Security Operations Center (SOC) laboratory
for security monitoring, detection and investigation.

## Technologies

- pfSense
- Splunk Enterprise
- Windows Server
- Kali Linux
- softflowd / NetFlow
- VMware Workstation

## Architecture

Internet
   ↓
pfSense
   ↓
SOC Lab Network
   ├── Kali Linux
   └── Windows Server
          ↓
       Splunk SIEM

## Key Implementations

- Firewall monitoring
- Network traffic analysis
- NetFlow monitoring
- Windows Security Event Collection
- Authentication monitoring
- Brute-force detection
- Splunk dashboards
- Controlled security testing

## Documentation

[View Project Report](Documentation/SOC_Home_Lab_Report.pdf)
