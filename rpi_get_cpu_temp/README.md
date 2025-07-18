# Get RPI CPU (& GPU) Temperature Info
## Raspberry Pi cluster project
![Raspberry Pi](https://img.shields.io/badge/-Raspberry%20Pi-C51A4A?style=flat&logo=Raspberry-Pi)
[![playbook](https://img.shields.io/badge/Ansible%20Playbook-grey?stype=flat&logo=ansible&logoColor=EE0000)](site.yml)
![GitHub last commit](https://img.shields.io/github/last-commit/lpwoodhouse/rpi_get_cpu_temp)
![GitHub repo file count](https://img.shields.io/github/directory-file-count/lpwoodhouse/rpi_get_cpu_temp)
![GitHub top language](https://img.shields.io/github/languages/top/lpwoodhouse/rpi_get_cpu_temp)
[![GitHub](https://img.shields.io/github/license/lpwoodhouse/rpi_get_cpu_temp)](LICENSE)
## Purpose

Gathers information of current CPU/GPU temperatures on rpi hosts.

## Requirements

None

## Role Variables

Available variables are listed below, along with default values (see ```defaults/main.yml```)
```shell
inc_fan_settings: true
```
## Dependencies

None

## Example Playbook
```yaml
    - hosts: all
      roles:
        - rpi_temps
```

## Author Information

This role was created in 2022 by [Lee Woodhouse](https://www.leewoodhouse.com/)
