Ansible Playbooks
=================


Instructions
------------

   * Cloud9IDE SDK / local install  

      ```
      curl -sSL https://github.com/gbraad/ansible-playbooks/raw/master/playbooks/install-c9sdk.yml -o install-c9sdk.yml
      ```
      
      ```
      ./install-c9sdk.yml
      ```
      or
      ```
      ansible-playbook install-c9sdk.yml
      ```


Requirements
------------

You need to have Ansible > 2.0 installed.


### Ubuntu
```
$ apt-get install ansible
```
or
```
$ apt-get install python-pip
$ pip install -U ansible
```


### CentOS / Fedora
```
$ yum install ansible    # or   dnf install ansible python2-dnf
```
or
```
$ yum install python-pip
$ pip install -U ansible
```


Authors
-------

| [!["Gerard Braad"](http://gravatar.com/avatar/e466994eea3c2a1672564e45aca844d0.png?s=60)](http://gbraad.nl "Gerard Braad <me@gbraad.nl>") |
|---|
| [@gbraad](https://twitter.com/gbraad)  |
