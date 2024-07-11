# ansible-role-prometheus

## Role

Install prometheus 2.53.1 and Grafana, only tested with ubuntu 22.04.

## Role variables :

## Usage :

```
---

- hosts: prometheus 
  become: yes
  vars:
  roles:
      - ansible-role-prometheus

```
