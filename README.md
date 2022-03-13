
# Install the powertools ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_powertools

# Clone the powertools ansible role. 
git clone git@github.com:computate-org/computate_powertools.git ~/.ansible/roles/computate.computate_powertools
cd ~/.ansible/roles/computate.computate_powertools
```

# Run the powertools ansible playbook to install powertools locally. 

```bash
ansible-playbook install.yml
```

