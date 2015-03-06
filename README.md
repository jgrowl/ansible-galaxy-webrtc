webrtc
========

Builds webrtc

Role Variables
--------------

Dependencies
------------

  * jgrowl.depot_tools
  * php-coder.oraclejdk

ExamplePlaybook
-------------------------

    - hosts: localhost
      roles:
        - { role: jgrowl.webrtc }


Example commands
-----------------------

`apt-get update && apt-get install ansible python-apt \
&& ansible-galaxy install jgrowl.webrtc && ansible-galaxy install jgrowl.depot_tools`

`ansible-playbook -K  main.yml -i localhost, --connection=local`

License
-------

MIT

