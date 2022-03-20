# Boostrap Workstation

``` bash
curl https://bootstrap.pypa.io/get-pip.py > /tmp/get-pip.py
python3 /tmp/get-pip.py
python3 -m pip install --user ansible
ansible-pull --ask-become-pass --url https://github.com/Sam-Killgallon/bootstrap-workstation.git
```
