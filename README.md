# ic-it simple ldap authentication

Configure a simple ldap authentication for a linux server.

## Requirements

None

## Role Variables

| Variable           | Description                                    | Default value |
| ------------------ | ---------------------------------------------- | ------------- |
| trusted_group_name | The name of the group that is allowed to login | IC-IT-Unit    |
| trusted_group_id   | The id of the group that is allowed to login   | S11914        |

## Dependencies

None

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ic_it.simple_ldap_authentication, trusted_group_name: IC-IT-Unit, trusted_group_id: S11914 }

## License

BSD

## Author Information

Emmanuel Jaep (emanuel (dot) jaep (at) epfl (dot) ch)
