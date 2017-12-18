# Ansible Role Redis

An Ansible role for installing Redis on target VM

## Role Variables

- `redis_version` - Redis version (default: `2:2.8.4-2`)
- `redis_bind_address` - Address Redis binds to (default: `127.0.0.1`)
- `redis_port` - Port Redis binds to (default: `6379`)
