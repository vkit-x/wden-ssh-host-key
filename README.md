# wden-ssh-host-key

SSH host keys for openssh-server setup.

```bash
ssh-keygen -t ecdsa -f ssh_host_ecdsa_key -q -N ""
ssh-keygen -t ed25519 -f ssh_host_ed25519_key -q -N ""
ssh-keygen -t rsa -f ssh_host_rsa_key -q -N ""

ssh-keygen -t rsa -f ssh_wden_rsa_key -q -N ""

chmod 600 ssh_*
```
