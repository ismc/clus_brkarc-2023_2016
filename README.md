# build-a-cloud

Pre-requisites:

Install PIP on Centos 7:
```
yum install epel-release
yum install python-devel python-pip
```

Install OpenStack Clients:
```
yum groupinstall development
pip install python-openstackclient
pip install 'setuptools>=11.3'
pip install shade
```

Install EC2 Clients:
```
pip install boto
```

Install Ansible:
```
yum -y install libffi-devel openssl-devel
pip install git+git://github.com/ansible/ansible.git@stable-2.1
```

Install Azure:
```
pip install --no-cache-dir --upgrade 'azure==2.0.0rc5'
yum -y install npm
npm install azure-cli -g
```