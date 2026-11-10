### Junior SOC Analyst in training · Blue Team · Python automation

Systems Engineering student at UTN (Universidad Tecnológica Nacional), currently in 4th year.

#### What I'm working on
- **SOC investigations:** alert triage write-ups from LetsDefend, CyberDefenders and Blue Team Labs Online.
- **Detection as code:** Sigma rules mapped to ATT&CK, converted to SPL/KQL and validated in CI against recorded attacks.

#### Featured investigations

| Investigation | Type | ATT&CK | Write-up |
|---|---|---|---|
| SOC153 · Suspicious PowerShell script executed | Malware / execution | T1059.001, T1105, T1071.001 | [read](https://github.com/ConfortiAngelo/soc-investigations/tree/main/investigations/letsdefend/SOC153-suspicious-powershell-script) |
| SOC257 · VPN login from unauthorized country | Identity / valid accounts | T1078, T1621, T1110 | [read](https://github.com/ConfortiAngelo/soc-investigations/tree/main/investigations/letsdefend/SOC257-vpn-unauthorized-country) |

#### Projects
- [**detections-as-code**](https://github.com/ConfortiAngelo/detections-as-code): 6 Sigma detections (LSASS dumping, log clearing, PsExec, hidden PowerShell…) auto-converted to Splunk SPL and Microsoft KQL, each tested in CI against a recorded attack with zero false positives on the rest of the corpus.
- [**soc-home-lab**](https://github.com/ConfortiAngelo/soc-home-lab): Splunk in Docker ingesting Sysmon (Windows) and auth/syslog (Linux) through Universal Forwarders.
- [**log-threat-detection**](https://github.com/ConfortiAngelo/log-threat-detection): threshold-based SSH brute-force, login-after-brute-force and port-scan detection in Python, ATT&CK-mapped, 22 tests in CI.
- [**secure-auth-cli**](https://github.com/ConfortiAngelo/secure-auth-cli): my own 2024 login CLI after a security review: SQL injection, SHA-256 and weak RNG fixed (Argon2id), 33 tests.
- [**http-vs-https-traffic-analysis**](https://github.com/ConfortiAngelo/http-vs-https-traffic-analysis): Wireshark lab capturing cleartext credentials over HTTP vs TLS 1.3.
- [**tcp-port-scanner**](https://github.com/ConfortiAngelo/tcp-port-scanner): async TCP connect scanner (asyncio) to understand scans from the defender's side.

#### Skills
SIEM: Splunk (SPL, Universal Forwarder) · Sigma · KQL (Sentinel / Defender XDR) · Sysmon / Windows event logs · Linux auth logs · Wireshark · MITRE ATT&CK · Python (asyncio, pytest) · Docker · Git / GitHub Actions

#### Contact
[LinkedIn](https://www.linkedin.com/in/angelo-conforti-a18b42330)
