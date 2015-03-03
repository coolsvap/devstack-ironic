devstack-ironic
===============
Devstack and Ironic localrc

Prerequisites:
--------------
- DevStack setup requires to have 1 VM/ BM machine with internet connectivity.
- Setup a fresh supported Linux installation. (Ubuntu/Fedora/CentOs)
- Install Git

Steps
-----
1. Clone devstack
```
$git clone https://github.com/openstack-dev/devstack.git
```

2. Clone devstack-ironic
```
$git clone https://github.com/svashu/devstack-ironic.git
```

3. Copy localrc from devstack-ironic to devstack
```
$ cp devstack-ironic/localrc devstack

```

4. Modify the devstack/localrc for IP and password modifications

5. Deploy your Devstack

```
$cd devstack && ./stack.sh
```
