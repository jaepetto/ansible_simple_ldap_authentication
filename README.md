# ic-it simple ldap authentication

Configure a simple ldap authentication for a linux server.

## Requirements

None

## Role Variables

| Variable        | Description                                  | Default value |
| --------------- | -------------------------------------------- | ------------- |
| login_group_id  | The id of the group that is allowed to login | S09213        |
| sudo_group_name | The name of the group that has sudo rights   | IC-IT-Unit    |

## Dependencies

None

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ic_it.simple_ldap_authentication, sudo_group_name: IC-IT-Unit, login_group_id: S09213 }

## License

BSD

## Author Information

Emmanuel Jaep (emmanuel (dot) jaep (at) epfl (dot) ch)
