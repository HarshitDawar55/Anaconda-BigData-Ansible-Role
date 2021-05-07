<img src = "https://img.shields.io/badge/version-1.1.0-brightgreen" />

Anaconda-BigData
=========

* It configures Anaconda with a separate environemnt of BigData to loaa data directly from hdfs using python.

Requirements
------------

* Hadoop cluster should be there, otherwise there is no need for this.

Role Variables
--------------

**anaconda_installation_directory** => Directory where the anaconda will be downloaded and then installed from this directory. *Note: this directory will not have anaconda installed, it will be installed in by default directory of "/root/anaconda3".*

Dependencies
------------

Nil

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: AnacondaNodes
      vars:
        - anaconda_installation_directory: "/anaconda" 
      roles:
         - Anaconda-BigData

License
-------

[GPL-3.0](https://github.com/HarshitDawar55/Anaconda-BigData-Ansible-Role/blob/main/LICENSE)

Author Information
------------------

Developed by Harshit Dawar, also known as Technologist, a public speaker, extrovert, & optimist.

**LinkedIn:** https://www.linkedin.com/in/harshitdawar

**PortFolio:** https://harshitdawar55.github.io

**Twitter:** https://www.twitter.com/harshitdawar55

**Medium:** https://harshitdawar.medium.com

**GitHub:** https://www.github.com/harshitdawar55

