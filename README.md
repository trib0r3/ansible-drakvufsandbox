# ansible-drakvuf

Ansible playbooks for managing [drakvuf-sandbox](https://github.com/CERT-Polska/drakvuf-sandbox).

## How to use

1. Copy your *inventory.example* to *inventory* and edit it:
   - change ip address of machine(s)
   - create ssh key used to connect in *./files/ssh_drak*
2. Run the playbooks:

```bash
ansible-playbook -i ./inventory drakvuf-upgrade.yml
```

## Playbooks

- `drakvuf-upgrade.yml` - install the newest release of packages from the repository and install them

# ToDo

- [ ] playbook for installing drakvuf and machine

## License

[BSD-3 License](./LICENSE)
