my_own_role
=========

Creates a text file with the specified content and name at the specified path

Requirements
------------

No requirements

Role Variables
--------------
| Name | Description |
|---|---|
| `path` | path to file |
| `content` | content of the file |

Dependencies
------------

git@github.com:AlexeyKhrapov/my_own_collection.git

Example Playbook
----------------

```yaml
- name: Example of collection playbook
  hosts: localhost
  collections:
    - my_own_collection.yandex_cloud_cvl
  vars:
    - path: "./example.txt"
    - content: "Some content"
  roles:
    - my_own_role
```

License
-------

MIT

Author Information
------------------

Alexey Khrapov,  Netology, devops-13
