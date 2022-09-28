Gitlab-runner-role
===================

Роль устанавливает gitlab-runner

Requirements
------------

Их нет

Role Variables
--------------

Отсутствуют

Dependencies
------------

None

Example Playbook
----------------

```yml
- name: Install GitLab runner
  hosts: gitlab-runner
  become: true
  roles:
    - role: gitlab-runner-role
```

License
-------

BSD

Author Information
------------------

Frolls
