Hyperfoil Setup
=========

Generates Hyperfoil report

Requirements
------------

Pre-released Java archive

Dependencies
------------

None

Role Variables
--------------

* `JRE_11_FOLDER` (required): Java Runtime Environment installation path
* `reporter_version` (required): Reporter release version
* `hyperfoil_dir` (optional): remote directory for Hyperfoil (unpacked distribution, logs...)
* `hyperfoil_controller_group` (optional): Ansible group that hosts the controller. Default is `hyperofoil-controller`.

License
-------

Apache License, Version 2.0
