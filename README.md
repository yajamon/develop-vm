# develop-vm
my develop virtual machine

## Requirement

- Vagrant
- Virtual Machine Provider
    - VirtualBox
    - VMWare
    - etc...

## Usage

```bash
git clone https://github.com/yajamon/develop-vm.git develop-vm
cd develop-vm
vagrant up
```

## Development

### Requirement

#### vagrant plugins

- sahara
    - `vagrant plugin install sahara`

### setup

```bash
cd develop-vm
vagrant up --no-provision
vagrant sandbox on
```

### main

1. Edit playbook
2. Rollback
    - `vagrant sandbox rollback`
3. Provision
    - `vagarnt provision`

### Restart

```bash
cd develop-vm
vagrant destroy
```
