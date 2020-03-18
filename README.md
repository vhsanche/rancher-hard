# rancher-hard
Instructions come from, https://releases.rancher.com/documents/security/2.3.x/Rancher_Hardening_Guide.pdf.
To run do the following:
```bash
ansible-playbook -i inventory/test --ask-become-pass rancher-hardening.yml
```