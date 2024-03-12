# Ansible handle Linux packages

- Edit inventory.yaml to add your servers

  
- Edit the "packages" array on vars.yaml to check if each package is up to date
- If somes are not and "makeupdate" is true, then they will be updated


## Run

```
ansible-playbook -i inventory.yaml playbook.yaml
```
