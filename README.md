# Commands

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
