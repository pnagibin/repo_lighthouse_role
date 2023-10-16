
# README
  
---
## Role Name
  
repo_lighthouse_role  
  
---
## Description
  
Данная роль устанавливает на целевой машине сервис lighthouse
  
---
## Dependencies
  
> role: repo_clickhouse_role  
  
  
---
## Information
  

|Author|Company|License|Minimum Ansible Version|
| :---: | :---: | :---: | :---: |
|Nagibin Pavel|None|license (BSD, MIT)|2.1|



# Tasks
---

# main.yml

* NGINX | Install package

* NGINX | Copy lighthouse static files


# install_nginx.yml


* Install EPEL repo

* Install NGINX


# configure_lighthouse.yml


* NGINX | insert lighthouse static content

# Handlers


# main.yml


* Start NGiNX