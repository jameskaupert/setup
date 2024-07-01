# setup

## Pop!_OS
1. Clone the repo: `cd ~ && git clone https://github.com/jameskaupert/setup.git && cd setup`
2. Run setup script: `./setup`
3. `exit`
4. Open new terminal, `sudo su`, then `exit`
5. `cd setup`
6. Run the playbook: `ansible-playbook main.yml`
7. Set up ssh keys for GitHub: `ssh-keygen -t ed25519 -C "<email>"`. Upload to GitHub.
