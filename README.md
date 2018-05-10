Role Name
=========

Bare bones installation of Confluent Kafka OSS

Requirements
------------

A compatible version of Java is required. Details here: https://docs.confluent.io/current/installation/versions-interoperability.html

Role Variables
--------------

See vars/main.yml

Dependencies
------------

Java is such a finicky beast I really don't want to dictate to your organization which version or vendor's Java to use. But, this was developed with OpenJDK 1.8

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Install Confluent Kafka
      hosts: all
      become: true
      roles:
        - confluent_kafka

License
-------

MIT

Author Information
------------------

Chris Short  
https://chrisshort.net  
https://devopsish.com