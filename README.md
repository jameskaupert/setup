# setup

## Pop!_OS
1. Clone the repo: `cd ~ && git clone https://github.com/jameskaupert/setup.git && cd setup`
2. Run setup script: `./setup`
3. `sudo su`, then `exit`
4. Run the playbook: `ansible-playbook main.yml --extra-vars "local_user=<insert-username>"`
5. Set up ssh keys for GitHub: `ssh-keygen -t ed22519 -C "<email>"`. Upload to GitHub.
