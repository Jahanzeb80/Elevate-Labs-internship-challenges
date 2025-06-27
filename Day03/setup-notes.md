Nessus Setup Notes – Day 03

- **Nessus Version**: 10.8.4 (Linux)
- **Scan Type**: Advanced Scan
- **Target IP**: 192.168.144.18 # you can specify your
- **Plugin Set**: 202506261800 
- **License**: Nessus Essentials
- **Scan Duration**: around ~45 minutes

 Issues Faced
- Scan creation was disabled initially — fixed after plugin compilation completed (waited to 100%)
- CPU spiked to 100% — normal during plugin compilation
- Used local IP instead of 127.0.0.1 for broader scanning

 Notes
- No credentialed scanning enabled
- No additional policy customization beyond defaults

