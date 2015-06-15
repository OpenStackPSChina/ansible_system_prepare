## This is a simple playbook for system initialization for openstack kilo deployment
- Only working if remote_user is root.
- Roles Brief:
    - common
        - setup apt sources.list   --> from templates to /etc/apt/sources.list
        - update apt-get           --> apt-get update
        - upgrade packages         --> apt-get -y upgrade
        - install ntp server
        - config ntp server
