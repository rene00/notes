# k3s

I'm running k3s on a single host using a VM as the master node and the host as
the only node. Both master and node are running Debian.

The master node is built using a [Taskfile](https://taskfile.dev) which calls
out to livirtd using `virsh`.

# Links
 - [k3s-ansible](https://github.com/k3s-io/k3s-ansible):
   - Has been a pleasure to work with this playbook.
