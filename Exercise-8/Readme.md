
# Ansible Playbook: Web Server Configuration

This Ansible playbook automates the installation and configuration of Apache2 and PHP on a web server. It also sets the timezone, copies an `index.php` file to the web server, and restarts the Apache service.

## Usage

1. **Clone the Repository:**
   git clone https://github.com/your-username/ansible-web-server-config.git
**Navigate to the Project Directory:**
  cd ansible-web-server-config
**Update Inventory:**
  Edit the inventory.ini file and replace web with the hostname or IP address of your target web server.

**Run the Ansible Playbook:**
ansible-playbook playbook1..yml -i inventory.ini
This will execute the playbook and configure the web server according to the defined tasks.

**Playbook Structure**
Task 1: Install Apache2 and PHP
Installs Apache2 and PHP on the web server.
- name: Install Apache2 and PHP on web server
  # ... (see playbook1.yml)
Task 2: Start Apache2
Starts the Apache2 service on the web server.
- name: Start Apache2 on webserver
  # ... (see playbook1.yml)
Task 3: Change Timezone
Sets the timezone to "Africa/Lagos" on the web server.
- name: Change timezone on webserver
  # ... (see playbook1.yml)
Task 4: Copy index.php File
Copies the index.php file to the web server.
- name: Copy index.php file to webserver
  # ... (see playbook1.yml)
Task 5: Restart Web Server
Restarts the Apache service on the web server.
- name: Restart web server
  # ... (see playbook1.yml)

Contributors
Georgia Omoja
