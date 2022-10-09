# ansible-playbooks
Performing repetitive activities is boring. What if we automate them with ansible?


## :bookmark: Requirements
- [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

## :triangular_flag_on_post: Starting
```bash
#Clone the repository
https://github.com/arielroque/ansible-playbooks.git
```
## :books: Available playbooks

- :book: [`Setup VM`](https://github.com/arielroque/ansible-playbooks/blob/main/playbooks/setup-vm.yaml) for install Docker (with post instalation) and Kubectl
- :book: [`Setup VM with SGX Driver`](https://github.com/arielroque/ansible-playbooks/blob/main/playbooks/setup-vm-with-sgx.yaml) for install Docker (with post instalation), Kubectl and Intel SGX Driver


## :triangular_flag_on_post: Running

```bash
# Export HOST IP
export HOST_IP=<IP>
echo $HOST_IP >> hosts

# Available command options:
# ansible-playbook playbooks/setup-vm.yaml -i hosts
# ansible-playbook playbooks/setup-vm-with-sgx.yaml -i hosts
```
