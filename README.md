## 🔍 Tools Used
- Kali Linux
- Nmap
- Metasploit Framework
- FTP Client

## 🛠️ Methodology
1. Reconnaissance & Scanning (Nmap)
2. Enumeration (FTP anonymous login)
3. Vulnerability Analysis (vsFTPd 2.3.4 Backdoor)
4. Exploitation (Metasploit)
5. Post-Exploitation (root access & system info gathering)
6. Reporting (Findings, Evidence, Recommendations)

## 📊 Findings
| Service        | Port | Vulnerability                  | Severity  |
|----------------|------|--------------------------------|-----------|
| FTP (vsFTPd)   | 21   | Backdoor allows root access    | Critical  |
| FTP Config     | 21   | Anonymous login enabled        | High      |
