Apache Libcloud (Mod) - a unified interface for the cloud
=========================================================

Apache Libcloud is a Python library which hides differences between different
cloud provider APIs and allows you to manage different cloud resources
through a unified and easy to use API.


:Code:          https://github.com/apache/libcloud
:License:       Apache 2.0; see LICENSE file
:Issues:        https://issues.apache.org/jira/projects/LIBCLOUD/issues
:Website:       https://libcloud.apache.org/
:Documentation: https://libcloud.readthedocs.io

Resources you can manage with Libcloud are divided into the following categories:

* **Compute** - Cloud Servers and Block Storage - services such as Amazon EC2 and Rackspace
  Cloud Servers (``libcloud.compute.*``)
* **Storage** - Cloud Object Storage and CDN  - services such as Amazon S3 and Rackspace
  CloudFiles (``libcloud.storage.*``)
* **Load Balancers** - Load Balancers as a Service, LBaaS (``libcloud.loadbalancer.*``)
* **DNS** - DNS as a Service, DNSaaS (``libcloud.dns.*``)
* **Container** - Container virtualization services (``libcloud.container.*``)


Apache Libcloud is an Apache project, see <http://libcloud.apache.org> for
more information.

Documentation
=============

Documentation can be found at <https://libcloud.readthedocs.org>.

Custom Edits
============

This version of Apache Libcloud features the following modifications:

* **[EC2]** create_node now supports the optional parameter "ex_monitoring" (bool), in order to
  allow the user to launch an instance with the Advanced Monitoring enabled.
* **[OpenStack]** create_node now supports the optional parameter ex_scheduler_hints (dict),
  allowing the user to provide detailed informations to the OpenStack scheduler and using
  the OpenStack REST API presented at <https://developer.openstack.org/api-ref/compute/?expanded=create-server-detail>.

Feedback
========

Please send feedback to the mailing list at <dev@libcloud.apache.org>,
or the JIRA at <https://issues.apache.org/jira/browse/LIBCLOUD>.

Contributing
============

For information on how to contribute, please see the Contributing
chapter in our documentation
<https://libcloud.readthedocs.org/en/latest/development.html#contributing>

License
=======

Apache Libcloud is licensed under the Apache 2.0 license. For more information, please see LICENSE_ and NOTICE_  file.

.. _LICENSE: https://github.com/apache/libcloud/blob/trunk/LICENSE
.. _NOTICE: https://github.com/apache/libcloud/blob/trunk/NOTICE
