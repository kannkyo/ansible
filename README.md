# ansible

## run

```bash
docker run -it -v $(pwd)/share:/mnt/host ansible
```

## play book

```bash
cd /mnt/host/playbook/
ansible-galaxy install -r /mnt/host/playbook/requirements.yml
ansible-playbook -i /mnt/host/playbook/hosts/development /mnt/host/playbook/site.yml
```
