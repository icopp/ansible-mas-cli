# ansible-mas-cli

Install the [`mas-cli`](https://github.com/argon/mas) utility and optionally log in with it.

## Role Variables

`apple_id` and `apple_id_password` will be used to log in to the Mac App Store if supplied.

## Dependencies

* [icopp.homebrew](https://github.com/icopp/ansible-homebrew)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.mas-cli
        apple_id: xxxxx@xxxxx.xxxxx
        apple_id_password: xxxxx
```

## License

MIT
