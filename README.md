Role Name
=========

Deploy [sshtrap](https://github.com/vrischmann/sshtrap).

Requirements
------------

Ansible 2.9+.

Role Variables
--------------

| Name               | Required | Description                                                                                 |
| --------------     | -------- | -----------------------------------                                                         |
| `sshtrap_version`  | yes      | Version of the binary. Can be found [here](https://github.com/vrischmann/sshtrap/releases)  |
| `sshtrap_checksum` | yes      | Checksum of the binary. Can be found [here](https://github.com/vrischmann/sshtrap/releases) |
| `sshtrap_binary`   | yes      | The path of the `sshtrap` binary. Defaults to `/usr/local/bin/sshtrap`                      |

Example
-------

```
    - hosts: servers
      roles:
         - vrischmann.sshtrap
```

License
-------

MIT
