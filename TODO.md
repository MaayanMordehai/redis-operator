TODO
====

Basic
-----

- [ ] adding the templates
- [ ] assertion checking in playbook/role
- [ ] make role ansible-galaxy ready - why can not be both ansible galaxy role and oprator role
- [ ] status in crd
- [ ] make 0 replicas option
- [ ] combine the configmaps into one ? do we even want configmaps ? 
- [ ] check about statefulset volume claim
- [ ] add liveness and readiness


Backups
-----------

- [ ] add backup pause option
- [ ] should we keep backup pvc always ? should we keep it when changing to cache? should we create restore pod in redis cache when there is backup pvc?

Documention
-----------

- [ ] document scaling
- [ ] document modules
- [ ] document which images can change


CI/CD
-----

- [ ] start ci cd using github piplines / travis

prometeuse
----------

- [ ] add exporter for redis
- [ ] add auto adding to prometuse using operator
- [ ] grafana dashboard? 
