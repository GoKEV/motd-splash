motd-splash
=========

This role lays down a template for /etc/issue (pre-login warning) as well as /etc-motd (post login splash).

This includes two colorful ASCII text logos for CentOS or Red Hat.  The role will conditionally determine CentOS or RHEL logo, based on Ansible fact gathering of the target OS.  If the target system is neither, a generic and boring template is used.  All template options lay down some basic information about the target system for login MOTD display.


A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - motd-splash

License
-------

Logo artwork is rough ASCII text and was rendered without approval or permission of respective copyright holders.  The original logo, likeness, or usability of these logos is still property of the respective copyright holders and can be revoked at their discretion.  There are probably all sorts of legalese things that I should say here, but in a nutshell... these logos will make your system look cool.  I hope the people that designed and own the artwork will appreciate that intent.


Author Information
------------------

Kevin Holmes :: kev@GoKEV.com



Screen Shots of End Results
------------------

/etc/motd for RHEL systems
![motd_rhel](https://raw.githubusercontent.com/GoKEV/motd-splash/tree/master/files/motd_rhel.png)

/etc/motd for CentOS systems
![motd_centos](https://raw.githubusercontent.com/GoKEV/motd-splash/tree/master/files/motd_centos.png)

/etc/motd for systems that have no OS-specific MOTD template
![motd_generic](https://raw.githubusercontent.com/GoKEV/motd-splash/tree/master/files/motd_generic.png)

/etc/issue pre-login warning
![issue](https://raw.githubusercontent.com/GoKEV/motd-splash/tree/master/files/issue.png)





