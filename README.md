# mock

An Ansible role that installs mock and adds user to mock group.


## Role Variables

Available variables and their default values are listed below:

* `mock_user: ''` - a user to be added to the mock group.

The role will only install mock package if `mock_user` is not specified.


## Example Playbook

```yaml
    ---
    - hosts: all
      roles:
        - { role: ezamriy.mock, mock_user: vagrant }
```


## License

MIT


## Authors

* [Eugene Zamriy](https://github.com/ezamriy)
