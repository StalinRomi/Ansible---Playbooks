Ansible is an **open source automation tool** used to **configure multiple computers** at the same time.

## Ansible Playbooks

Text files / Configuration files written in YAML language which tells ansible what to do & how to do it.

Ansible can work with 1 or multiple systems in your infrastructure at the same time. Ansible establishes connection between these servers using **SSH for Linux & Power shell remoting for windows**.

Information about target systems is stored in **Inventory file**.

Its in Playbooks where we define what we want Ansible to do. Playbook has set of tasks to be run on Hosts. Task is an action performed on the Hosts.

Eg. Execute a command, Run a script, Install a package, Shutdown / Restart.
