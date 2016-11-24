Ansible init for integrated
---------------------------

* This role allowing you to arrange to organize groups in a playbooks dir.

## Example Playbook

    - hosts: servers
      roles:
         - init-for-integrated
         - <other-role>

## Memo

* You can use dependencies of meta.
