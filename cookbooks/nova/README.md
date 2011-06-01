Description
===========
Cookbook and recipes for deploying OpenStack Nova.

This Chef repository was originally based on the work of Anso Labs' OpenStack-Cookbooks (https://github.com/ansolabs/openstack-cookbooks). It is intended for deploying the point-release codenamed "Cactus", other branches will be added with each release.

Requirements
============
Written and tested with Ubuntu 10.04 and 10.10 and Chef 0.10.0. 

Definitions
===========
nova_package
------------
This handles installing nova packages generically and managing them as services.

Resources/Providers
===================

Recipes
=======
api
---

config
------

compute
-------
Provides the compute functionality, currently depends on KVM.

dashboard
---------

filevg
------

finalize
--------
The last cleanup steps of the install.

mysql
-----

network
-------

objectstore
-----------

openldap
--------

project
-------
Create Nova certifications, per http://wiki.openstack.org/NovaInstall/MultipleServer
Creates Projects


rabbit
------

scheduler
---------

user
----
Creates the 'nova' user.

volume
------

License
=======
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
