# bitnami-pg-upgrade

This is a PoC for using pg_upgrade inside `bitnami/postgres-ha` from 14 to 15 -- learn from it, adapt it for your needs; don't expect it to work as-is!

(Source for this image is available at https://github.com/exfly/bitnami-pg-upgrade .)

[ref blog](https://exfly.github.io/postgres-upgrade-bitnami-ha/)

## Usage

Dependense on [kind](https://kind.sigs.k8s.io/) [docker](https://docs.docker.com/engine/install/)

```
bash test.sh
```

## Ref

- [Better documentation needed on major version upgrades](https://github.com/bitnami/charts/issues/14926)
