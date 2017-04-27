# ansible-percona-cluster-proxysql
Ansible playbook to create a percona mysql cluster with proxysql in front.
This will eventually be tied to an app time permitting.

Please note that the app would connect through the proxy. I need to figure out
firewall rules for the proxy but for now, note that you connect through port
6033. Same goes re: firewall rules for the cluster.
