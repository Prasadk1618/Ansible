### Ansible Installation..!!
```bash
sudo apt update
sudo apt install software-properties-common
sudo add-apt-repository --yes --update ppa:ansible/ansible
sudo apt install ansible
ansible --version
```

### Scp Command local key move on Server..!
```bash
 scp -i .\new.pem .\new.pem ubuntu@(Public_ip):/home/ubuntu/keys
```
### Check One Server To Another Server Ram Or Free Size..!
```bash
ansible servers -a "free -h "
```
### check Another Server Date
```bash
ansible-playbook -v FileName.yml
```


### Blogs :-
- https://prasadblock.hashnode.dev/
