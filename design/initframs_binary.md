# initframs_binary

Binary to execute on initframs to load zfs keys.

## Requisites

### Recover password

Connect to ssh server with private key and try to read password and/or/else manually (else/and -> continue, or -> throw error and abort)

### Inject password

```yaml
shell: zfs load key to allow system to boot.
when: ZFS encrypted
```

### Security

- just make executable on boot

### Extend

- Could be a minirust ansible
