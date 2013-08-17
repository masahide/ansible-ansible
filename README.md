Building a ansible-server using Ansible Playbooks.
------------------------------------------------------------------

These playbooks require Ansible 1.2.

These playbooks are meant to be a reference and starter's guide to building
Ansible Playbooks. These playbooks were tested on CentOS 5.x so we recommend
that you use CentOS to test these modules.

This ansible-servers can be on a single node. The inventory file
'hosts' defines the nodes in which the stacks should be configured.

```
        [ansible-servers]
        localhost

```

The stack can be deployed using the following
command:

        ansible-playbook -i hosts site.yml



