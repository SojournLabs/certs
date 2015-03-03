# gcc
Docker container for dealing with openssl certificates.

Getting started
===============
Run `git submodule init` to pull the files you'll need to get started.

Command summary
===============
`ca_create` -- Create a root certificate authority.
`new_client` -- Create a certificate for a device that will connect to a server.
`new_server` -- Create a certificate for a server.
`new_peer` -- Create a certificate for a peer device (e.g., for `etcd`).
`new_user` -- Create a certificate for a person.
