Ansible init for integrated
---------------------------

* This role allowing you to arrange to organize groups in a playbooks dir.

```
├── playbooks
│   ├── addusr_ssh.yml
│   ├── disable_selinux.yml
│   ├── gce-instance-provision_and_init.yml
│   ├── gce-lb-provision.yml
│   ├── instance-provision_and_init.yml
│   ├── monitoring-tool.yml
│   ├── td-agent.yml
│   ├── test.yml
│   ├── vuls.yml
│   └── wordpress.yml
├── plugins
│   └── inventory
├── roles
│   ├── add_ssh_user
```

## Example Playbook

    - hosts: servers
      roles:
         - init-for-integrated
         - <other-role>

## Memo

* You can use dependencies of meta.
