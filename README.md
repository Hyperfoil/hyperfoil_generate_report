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

* `hyperfoil_report_version` (required): Hyperfoil report release version
* `hyperfoil_dir` (optional): remote directory for Hyperfoil (unpacked distribution, logs...)
* `hyperfoil_report_home` (optional): Directory containing role.
* `hyperfoil_controller_group` (optional): Ansible group that hosts the controller. Default is `hyperofoil-controller`.
* `hyperfoil_report_distribution` (optional): Distribution directory.


License
-------

Apache License, Version 2.0
