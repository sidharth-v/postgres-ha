# PostgreSQL HA with pg_auto_failover

## Introduction

PostgreSQL(also known as postgres) is one of the most advanced open-source relational database management systems with SQL compliance. This repository will deploy  PostgreSQL-13.3 HA as Kubernetes Statefulsets as per pg_auto_failover guidelines(https://pg-auto-failover.readthedocs.io).

1. Fully managed PostgreSQL-13.3 statefulsets deployment using GitOps from Client Git repository.
1. Configure Master/Slave deployment for HA/DR capability
1. Store all database secrets in AppZ Vault
1. Database Changes(New database, user, schema, tables etc) deployed using GitOps
1. Built-in logging and monitoring using AppZ Dashboard



## Documentation : How to Use this stack

