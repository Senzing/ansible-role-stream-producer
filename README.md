ansible-role-stream-producer
=========

This role setups Senzing Stream Producer. It installs the binary into `/usr/local/bin`

Installation
------------
Use `ansible-galaxy install senzing.stream_producer` to install the latest stable release of the role on your system.

The following are the supported Stream Producer versions.

| Stream Producer version|Galaxy Version|Path to Install|
|----------|:-------------:|:-------------:|
|1.2.2|1.2.2|`ansible-galaxy install senzing.stream_producer:1.2.2`|
|1.2.0|1.2.0|`ansible-galaxy install senzing.stream_producer:1.2.0`|
|1.1.0|1.1.0|`ansible-galaxy install senzing.stream_producer:1.1.0`|
|1.0.0|1.0.0|`ansible-galaxy install senzing.stream_producer:1.0.0`|

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
      vars:
        stream_producer_version: '1.2.2'

      roles:
        - senzing.stream_producer

License
-------

Apache 2

Author Information
------------------

This role was created in 2020 by [Mah Chia Hui](https://github.com/mahchiahui),
