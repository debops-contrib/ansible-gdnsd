Getting started
===============

.. contents::
   :local:

DNS zone configuration
----------------------

By default the role will create a forward and reverse zone defining the host
as primary name server and add a ``A`` and ``PTR`` record for the host to the
zone files. This configuration can be overwritten by defining
:envvar:`gdnsd__zones`.


Example inventory
-----------------

The ``debops-contrib.gdnsd`` role can be included in your Ansible setup by
assigning the DNS host(s) to a custom inventory group such as ``gdnsd_service``.
E.g.::

    [debops_gdnsd_service]
    hostname

Example playbook
----------------

Here's a minimal example Ansible playbook that uses the ``debops-contrib.gdnsd``
role:

.. literalinclude:: playbooks/gdnsd.yml
   :language: yaml
