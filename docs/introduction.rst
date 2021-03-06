Introduction
============

`gdnsd <http://gdnsd.org/>`_ is a powerful Authoritative-only DNS server with
some advanced features such as geographic (or other sorts of) balancing,
redirection, wighting and service-state-conscious failover at the DNS layer.

The ``debops-contrib.gdnsd`` Ansible role installs and configures the name
service and is able to generate zone files from name records defined in the
Ansible inventory and properly increase the serial on zone updates.

Installation
~~~~~~~~~~~~

This role requires at least Ansible ``v1.9.0``. To install it run:

.. code-block:: console

   user@host:~$ ansible-galaxy install debops-contrib.gdnsd

..
 Local Variables:
 mode: rst
 ispell-local-dictionary: "american"
 End:
