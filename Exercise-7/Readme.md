# Midnight Mailer

## Overview

Midnight Mailer is a simple Bash script designed to automate the process of sending an email containing the system log file at midnight using cron jobs. This can be useful for monitoring system activity and receiving regular updates on system events.

## Features

- **Automated Email:** The script utilizes the cron job scheduler to run at midnight and send an email containing the system log file.
- **Customizable Recipients:** Easily configure the email recipients and other parameters in the script.
- **Logs and Notifications:** The script logs its activities, providing insights into whether the email sending process was successful or encountered any issues.

## Prerequisites

- A Unix-based system with Bash shell support.
- The `mail` command installed on the system.
- Appropriate permissions to access and read system log files.
