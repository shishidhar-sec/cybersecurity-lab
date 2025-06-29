# 🧠 Splunk Basic Queries

## 🔍 List all failed logins (SSH brute force detection):
```spl
index=linux sourcetype=auth log_level="error" message="Failed password"
