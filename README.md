# Raspberry Pi automation

- [Temperature and fan tasks](rpi_get_cpu_temp/)
- [Node exporter installation](rpi_install_node_exporter/)
- [PoE HAT fan configuration](rpi_poe_hat_conf/)

Read each project's variables and supported distribution assumptions before use. These historical examples are not a verified description of a current Pi cluster.

The node exporter installer now requires node_exporter_checksum in sha256:HEX form, separately verified against the release selected by download_url. It verifies the download, reloads systemd and restarts on binary/unit changes. Confirm the architecture and exporter version before running; no Pi deployment was performed for this change.

Each included project has its own LICENSE file. Check those terms rather than assuming a new blanket root license.
