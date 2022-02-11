# ansible_task2
BaseConfig:\
ansible-playbook -K run.yml --ask-pass -i hosts\
After changing ports:\
ansible-playbook -K run.yml --ask-pass -i hosts --extra-vars "ansible_port=1834"
