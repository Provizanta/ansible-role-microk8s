---

name: Bug report
about: Create a report to help us improve the code

---

## Bug description

Describe the bug and both the expected and actual outcome.

## Environment details

### Provisioner
The provisioner is the control node performing the ansible commands:
- Provisioner OS: [e.g. Ubuntu 20.04] (`cat /etc/os-release`)
- Provisioner Ansible version: [e.g. 2.9.1] (`ansible --version`)

### Managed host
The managed host targeted by the playbook:
- Managed host OS: [e.g. CentOS 7] (`cat /etc/os-release`)

### Playbook
Please, include the playbook you were using to trigger the bug.

```yaml
---
THE PLAYBOOK HERE
```

In case external dependencies are needed, please, add `requirements.yml`.

### Output
Show at least the error, ideally the entire output of the playbook.
