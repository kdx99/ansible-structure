# ansible-structure
A starting help for ansible beginners

Edit the hosts file and enter your server(s).

## Secrets
If you want to use ansible-vault:
$ echo "password-of-my-choice" > .secret
$ chmod 600 .secret

If you don't want ansible-vault:
Comment the vault_password_file entry in ansible.cfg
