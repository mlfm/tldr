# ssh-keyscan

> Get the public ssh keys of remote hosts.

- Retrieve all public ssh keys of a remote host:

`ssh-keyscan {{host}}`

- Retrieve all public ssh keys of a remote host listening on a specific port:

`ssh-keyscan -p {{port}} {{host}}`

- Retrieve certain types of public ssh keys of a remote host:

`ssh-keyscan -t rsa,dsa,ecdsa,ed25519 {{host}}`