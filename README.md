# Satellite 6 on Centos 7
Capture a katello install in a Vagrant centos box using an ansible playbook.
Initial reference [Install Satellite 6 on Centos 7](https://github.com/lukepafford/iac_config/wiki/Install-Satellite-6-on-Centos-7)
Working reference [Katello 3.6 Installation](https://theforeman.org/plugins/katello/3.6/installation/index.html)

## Usage

``` bash
git clone https://github.com/cdd-aix/satellite-centos-vagrant.git
cd satellite-centos-vagrant
vagrant up --provision
$BROWSER https://localhost:1443/
```

## Caveats
This is not a forklift replacement... just a handy tool for training.
