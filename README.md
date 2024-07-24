# setup

## Pop!_OS
1. Clone the repo: `cd ~ && git clone https://github.com/jameskaupert/setup.git && cd setup`
2. Run setup script: `./setup`
3. `exit`
4. `cd setup`
5. Run the playbook: `ansible-playbook main.yml -K`
6. Set up ssh keys for GitHub: `ssh-keygen -t ed25519 -C "<email>"`. Upload to GitHub.
