
``` bash
# Clone role
cd roles/
git clone https://github.com/lesfurets/ansible-role-python3.git
ansible-galaxy install lesfurets.python3
cd ..
# Export environment vars:
export AWS_ACCESS_KEY_ID=AKIAIOSFODNN7EXAMPLE
export AWS_SECRET_ACCESS_KEY=wJalrXUtnFEMI/K7MDENG/bPxRfiCYEXAMPLEKEY
export AWS_DEFAULT_REGION=eu-west-1
# Execute ansible-playbook
ansible-playbook python_app.yml --key-file "mykey.pem"
```
