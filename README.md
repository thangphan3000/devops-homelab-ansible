# README

## Table of contents

- Tool requirements
- Run playbook

## Tool requirements

- ansible
- sshpass

## Run playbook

```bash
ansible-playbook playbook.yaml --ask-pass
```

## Run playbook with k8s cluster setup only

```bash
ansible-playbook playbook.yaml --ask-pass --tags k8s,k8s-init,k8s-join-worker
```
