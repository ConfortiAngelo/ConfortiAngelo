### Junior SOC Analyst in training · Blue Team · Python automation · Mendoza, Argentina

Systems Engineering student at UTN (Universidad Tecnológica Nacional), 4th year completed.

#### What I'm working on
- **SOC investigations:** alert triage write-ups from LetsDefend, CyberDefenders and Blue Team Labs Online.
- **Detection as code:** turning detections into Sigma rules validated in CI against recorded attacks (next).

#### Featured investigations

| Investigation | Type | ATT&CK | Write-up |
|---|---|---|---|
| SOC153 · Suspicious PowerShell script executed | Malware / execution | T1059.001, T1105, T1071.001 | [read](https://github.com/ConfortiAngelo/soc-investigations/tree/main/investigations/letsdefend/SOC153-suspicious-powershell-script) |
| SOC257 · VPN login from unauthorized country | Identity / valid accounts | T1078, T1621, T1110 | [read](https://github.com/ConfortiAngelo/soc-investigations/tree/main/investigations/letsdefend/SOC257-vpn-unauthorized-country) |

#### Projects
- [**soc-home-lab**](https://github.com/ConfortiAngelo/soc-home-lab): Splunk in Docker ingesting Sysmon (Windows) and auth/syslog (Linux) through Universal Forwarders.
- [**log-threat-detection**](https://github.com/ConfortiAngelo/log-threat-detection): threshold-based SSH brute-force, login-after-brute-force and port-scan detection in Python, ATT&CK-mapped, 22 tests in CI.
- [**secure-auth-cli**](https://github.com/ConfortiAngelo/secure-auth-cli): my own 2024 login CLI after a security review: SQL injection, SHA-256 and weak RNG fixed (Argon2id), 33 tests.
- [**http-vs-https-traffic-analysis**](https://github.com/ConfortiAngelo/http-vs-https-traffic-analysis): Wireshark lab capturing cleartext credentials over HTTP vs TLS 1.3.
- [**tcp-port-scanner**](https://github.com/ConfortiAngelo/tcp-port-scanner): async TCP connect scanner (asyncio) to understand scans from the defender's side.

#### Skills
SIEM: Splunk (SPL basics, Universal Forwarder) · Sysmon / Windows event logs · Linux auth logs · Wireshark · MITRE ATT&CK · Python (asyncio, pytest) · Docker · Git / GitHub Actions
