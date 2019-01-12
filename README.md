# Ansible Semaphore Packer/Terraform Deployment Scripts

[![CircleCI](https://circleci.com/gh/corystein/openldap-packer-terraform.svg?style=svg)](https://circleci.com/gh/corystein/openldap-packer-terraform)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/16c908be11684e4eba5b2696efa8a765)](https://www.codacy.com/app/corystein/openldap-packer-terraform?utm_source=github.com&utm_medium=referral&utm_content=corystein/openldap-packer-terraform&utm_campaign=Badge_Grade)

## Links

- [Open LDAP](https://www.openldap.org/)
- [Packer](https://packer.io)
- [Terraform](https://terraform.io)
- [Azure](https://portal.azure.com)

## Introduction

This project includes scripts to deploy [Open LDAP](https://www.openldap.org/) using [Packer](https://packer.io) and [Terraform](https://terraform.io). Packer script deploys the latest Ansible Semaphore into a single VM image.

## Packer Image

- Provider: [Azure](https://portal.azure.com)
- OS: Linux CentOS 7.5
- Ansible Semaphore: v2.5.1

## Getting Started

TODO: Guide users through getting your code up and running on their own system. In this section you can talk about:

1. Installation process
2. Software dependencies
3. Latest releases
4. API references

## Build and Test

TODO: Describe and show how to build your code and run the tests.

## Contributing

PR's & UX reviews are welcome!

Please follow the [contribution](https://github.com/ansible-semaphore/semaphore/blob/develop/CONTRIBUTING.md) guide. Any questions, please open an issue.

## License

The MIT License (MIT)

Copyright (c) 2019 Cory Stein

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
