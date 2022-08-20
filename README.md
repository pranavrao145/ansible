# Ansible Playbooks

All of the Ansible playbooks I use to set up my sytem.

## Execution Order

Below is a possible execution order of these playbooks for everything to work properly:

- Install packages (run `packages-primary`, `packages-secondary` (with `netcat`), and
  `packages-tertiary` separately)
- Git setup
- Shell
- Dotfiles
- Package managers
- Scripts
- X
- Development
