# Iniciator

### Install

`curl -LO https://raw.githubusercontent.com/Tedezed/iniciator/master/bin/initiator && chmod +x initiator && sudo mv ./initiator /usr/local/bin/initiator`

### Support

* [x] Docker
* [x] Ansible
* [ ] Python

### Tree

##### Docker

```
├── Dockerfile
├── Makefile
├── README.md
├── prod.yaml
├── dev.yaml
├── custom
│   ├── entrypoint.d
│   │   └── 00-init.sh
│   ├── executable
│   │   └── bash
│   │       └── entrypoint.sh
│   └── files
├── env
│   ├── dev.env
│   └── prod.env
└── volumes

```

##### Ansible

```
├── base.yml
├── hosts
├── README.md
├── roles
│   └── install
│       └── tasks
│           └── main.yaml
├── credentials
└── test
```