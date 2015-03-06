webrtc
========

Builds webrtc

Role Variables
--------------

Dependencies
------------

  * jgrowl.depot_tools
  * ANXS.oracle-jdk

ExamplePlaybook
-------------------------

    - hosts: localhost
      roles:
        - { role: jgrowl.webrtc }


Example commands
-----------------------

`apt-get update && apt-get install ansible python-apt && ansible-galaxy install jgrowl.webrtc`

`ansible-playbook -K  main.yml -i localhost, --connection=local`

License
-------

MIT

