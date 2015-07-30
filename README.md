# devbox_rails

Vagrant box for software development with Ruby on Rails. It will have the
following main components:

- crul
- git
- RVM (user_install)
- Ruby 2.2.1
- Node JS
- Postgre SQL 9
- Redis 2
- PS1

## Installation

'''
$ bundle install
$ vagrant plugin install vagrant-berkshelf
$ vagrant up --provision
'''

## Contributing

1. Fork the repository on Github
2. Create a named feature branch (i.e. `add-new-recipe`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request

## License and Authors

Author:: Abner Carleto

License:: MIT
