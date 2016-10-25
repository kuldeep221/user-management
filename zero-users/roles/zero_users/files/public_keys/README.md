Public Keys Directory
=====================

This directory contains the public keys of all users configured in this project.

Directory structure
===================

* Create a directory with name as <username> of user.
* Add the public key of user in the newly created directory with filename: id_rsa.pub

Example
=======

For user kuldeep, the following needs to be done:

```bash
    $ mkdir kuldeep 
    $ cp <path_of_user_public_key> kuldeep/id_rsa.pub
```
