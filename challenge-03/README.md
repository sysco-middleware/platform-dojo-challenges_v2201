# Update Apt and Install Tomcat
1. Created yaml file with 2 task
    * Apt update
    * Install Tomcat
2. execute command ansible-playbook tomcat9.yml
3. It will update the apt update with cache time for 3600 seconds
4. Tomcat 9 will be installed