# Ansible Role: Debug

This role dumps all variables in the current session to a file on the host.

## Requirements

> This role has been tested on `Ubuntu 16.04` and `Ubuntu 16.10` only.

## Variables

- `debug_var_dump_path`: path on remote host to dump variables in.
  - Default: `/tmp/ansible.all`

## Usage Example

```yaml
- hosts: all
  roles:
    - thedumbtechguy.debug
```


## License

MIT / BSD

## Author Information

This role was created by [Stefan Froelich](https://thedumbtechguy.blogspot.com/).

## Credits

This role is based on information presented by [Iwade](https://coderwall.com/lwade) in the coderwall article [Dump all variables](https://coderwall.com/p/13lh6w/dump-all-variables).