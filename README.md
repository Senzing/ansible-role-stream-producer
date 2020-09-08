ansible-role-stream-producer
=========

This role builds the Senzing Stream Producer. It installs the binary into `/usr/local/bin`

Requirements
------------

To install the python packages required for Stream Producer, python 3.8 and above is needed, along with pip 20.0 and above.

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

    stream_producer_version: "1.2.2"

The Stream Producer version that is being used. Substitute the version by passing in a variable file.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: senzing
      roles:
        - { role: senzing.stream_producer }

License
-------

BSD

Author Information
------------------

This role was created in 2020 by [Mah Chia Hui](https://github.com/mahchiahui),
