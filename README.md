# phpLDAPadmin Helm Chart

phpLDAPadmin is a web-based LDAP admin tool.

## Install

```sh
$ git clone https://github.com/gengen1988/helm-phpldapadmin
$ cd helm-phpldapadmin
$ helm install .
```

## Configuration

Parameter    | Description                                   | Default
------------ | --------------------------------------------- | --------
replicaCount | Number of replicas                            | 1
env | See: https://github.com/osixia/docker-phpLDAPadmin#environment-variables | [see values.yaml]
service.type | Service type                                  | ClusterIP
ingress.enabled | Enable or disable the ingress              | false
ingress.path        |  |
ingress.annotations |  |
ingress.hosts       |  |
ingress.tls         |  |
