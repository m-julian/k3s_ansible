# k3s_ansible

Installing k3s on server and agent nodes, as well as setting up rancher.

# rancher hostname

rancher needs a hostname to work. It is easiest to set up a DNS entry on the router which redirects to an IP address where rancher is running. A hostname such as `rancher.home.arpa` will work, as `home.arpa` is used for home networks.