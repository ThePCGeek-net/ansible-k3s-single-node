# Build a Kubernetes HA-cluster using k3s & kube-vip & metal-lb via Ansible

*Based on <https://docs.technotim.live/posts/k3s-etcd-ansible/> and <https://github.com/k3s-io/k3s-ansible*

BIG SHOUTOUT TO [TechnoTim](https://github.com/timothystewart6) who made this possible and inspired me be sure to check him out!

## Instructions/notes

- Clone this repo
- cd into the cloned repo
- run `./repo-init.sh` to create an inventory and vars file
- edit inventory/my-cluster/hosts.ini and change the ip to your single node's ip.
- edit inventory/my-cluster/group_vars/all.yml and change the appropriate settings as the comments outline
- run .deploy.sh to fire it off

## MetalLB

see <https://metallb.universe.tf/installation/>

## Links

Techno-Tim's video on his playbook this is based on: <https://www.youtube.com/watch?v=CbkEWcUZ7zM>
