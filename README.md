
🔐 Mastering Log Collection in SOC Operations
Welcome to this documentation repository dedicated to Log Collection — a core capability of any Security Operations Center (SOC).
This guide reflects my hands-on learning journey and practical exploration in the field of cybersecurity operations and blue teaming.

🚀 Why Log Collection Matters
Logs are the lifeblood of a SOC. They provide essential data for:

🔍 Threat Detection & Real-Time Monitoring

🧪 Incident Investigation & Forensics

📊 Regulatory Compliance Auditing (e.g., PCI-DSS, HIPAA, ISO)

🛡️ Infrastructure Visibility & Cyber Resilience

🔎 Core Areas of Focus
🧩 1. System-Level Logs
Collect logs from:

🖥️ Linux/Unix systems (/var/log/syslog, auth.log)

🌐 Network hardware (routers, switches)

💻 Workstations and user endpoints

🛠️ 2. Application Logs
Monitor application-level events, including:

🌐 Web server logs (access, error)

🔐 Authentication systems (login attempts, failures)

🗃️ Database transactions and queries

🔄 API requests and responses

🔐 3. Security Devices
Capture security-related alerts from:

🛡️ Antivirus & EDR solutions

🔥 Firewalls and Unified Threat Management (UTM)

🧠 IDS/IPS tools like Snort and Suricata

🔄 4. Log Normalization
Standardize log data for cross-platform analysis in tools like SIEM:

📌 Regex-based parsing and extraction

🧾 Key-value pair transformation

🕒 Timestamp formatting (ISO 8601 standard)

📤 5. Log Forwarding & Transport
Ensure secure and efficient delivery of log data using:

🚚 Splunk Universal Forwarder

📨 Syslog agents (rsyslog, syslog-ng)

📦 NXLog / Elastic Beats (Filebeat, Winlogbeat)

🗃️ 6. Log Storage & Retention
Maintain logs for operational and compliance needs:

🗄️ On-prem/local storage for recent logs

☁️ Cloud storage (e.g., Amazon S3, Azure Blob) for long-term archives

📅 Implement retention policies (e.g., 1 year for PCI-DSS)

⚡ 7. Real-Time Log Ingestion
Enable proactive defense and situational awareness:

🚨 Trigger alerts and correlation rules

📊 Feed real-time dashboards

🧠 Support threat hunting and anomaly detection


