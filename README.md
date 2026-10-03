# Linux-Login-Security-Tracker
A Bash-based Linux Login & Logout Monitoring and Intrusion Detection System that tracks successful and failed login attempts, monitors login and logout activities, detects suspicious IP addresses, blocks suspicious IPs, provides a web-based monitoring dashboard, and generates reports.
## Description

A Bash-based Linux Login & Logout Monitoring and Intrusion Detection System designed to monitor authentication activities, detect suspicious login behavior, and provide both terminal and web-based monitoring.

## Key Features

* **Login & Logout Tracking** – Tracks successful login and logout activities from Linux authentication logs.
* **Failed Login Detection** – Detects and displays failed password attempts.
* **Suspicious IP Detection** – Identifies IP addresses with repeated failed login attempts.
* **IP Blocking** – Blocks suspicious IP addresses using `/etc/hosts.deny`.
* **Top Attacking IPs** – Shows IP addresses with the highest number of failed attempts.
* **Username Search** – Searches login, logout, and failed-login records by username.
* **Terminal Menu** – Provides an interactive menu for monitoring and managing activities.
* **Security Reports** – Generates timestamped reports containing login, logout, failed-attempt, and suspicious-IP information.
* **Web Dashboard** – Displays login statistics, login/logout history, failed attempts, and suspicious IPs through a web interface.
* **JSON & Web Data** – Generates structured monitoring data for web integration.
* **Auto Refresh** – Automatically refreshes the web dashboard every 30 seconds.
* **System Information** – Displays hostname and current system time.
* **Manual Refresh** – Allows users to manually refresh the monitoring dashboard.
