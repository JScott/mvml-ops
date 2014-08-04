#mvml-ops

Scripts to get mvml-host up and running. This should serve as good documentation on the backend setup.

#Running ansible

We need some packages first:

```
sudo apt-get install git
sudo apt-get install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt-get update
sudo apt-get install ansible
```

Then run:

```
git clone git@github.com:JScott/mvml-ops.git
ansible-playbook server.yml -i hosts -K
```
