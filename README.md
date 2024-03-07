# wordpress
Install and configure Webserver with Ssl certificate and virtual host for Multi-site wordiress
Install and configure MariaDB server as backend server for wrdoress (hosting databases for wordpress).

<b>#Commands to setup wordpress envirnotment</b>

<b>#Note:</b>
  0. Add DNS entries to access wordpress through URL.
  1. Modify wordpress/group_vars/all variable file as per your DNS need and the DNS entry you did, 
  3. Run below commands:
<b>#Install</b>
  3.1. ansible-playbook VagrantFile.yml
  3.2. vagrant up
  3.3. ansible-playbook -i inventory.ini ConfigureServers.yml
  3.4. ansible-playbook -i inventory.ini InstallWordpress.yml

<b>#Browse:</b>
  https://wordpress.iservermate.local

Have fun...!
