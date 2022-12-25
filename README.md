# Ansible

Contain Ansible samples using regular directory structure.

```
ansible
   ├── hosts.ini               # The inventory file
   ├── roles
   |   ├── <roleName1>
   |   ├── <roleName2>
   |   └── <roleName3>
   |       ├── tasks
   |       |   ├── main.tf
   |       |   ├── Debian.tf
   |       |   ├── RedHat.tf
   |       |   └── config.tf
   |       ├── vars            # Variables associated with this role
   |       |   └── main.tf
   |       ├── defaults        # Default lower priority variables for this role
   |       |   └── main.tf
   |       ├── handlers
   |       |   └── main.tf
   |       └── templates
   |           └── main.tf
   ├── <playbookName1>
   ├── <playbookName2>
   └── <playbookName3>
```
