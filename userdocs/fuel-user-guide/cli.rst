.. _cli:

Use the Fuel CLI
================

Using the Fuel Command Line Interface (CLI) you can:

* Operate your OpenStack environments using Fuel text commands, as well as
  using standard Linux commands.
* Apply advanced configurations through configuration files that you cannot
  modify using the Fuel Web UI.

.. warning::
   We do not recommend to use Fuel CLi for unexperienced users.
   Fuel CLI may break your environment if not used carefully.

Modifications that you make using the Fuel CLI take precedence over the
settings applied from the Fuel Web UI. If a change has been applied using
the Fuel CLI, Fuel displays the corresponding message in the Fuel web UI.

This section includes the following topics:

.. toctree::
   :maxdepth: 3

   cli/cli_acronyms.rst
   cli/cli_usage.rst
   cli/cli_config_openstack.rst
   cli/cli_change_ip_range.rst