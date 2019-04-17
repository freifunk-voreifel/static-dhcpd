# static-dhcpd
Configuration files for static clients in Freifunk Voreifel

Die Konfigutration des Supernodes erfolgt mit Ansible, daher werden die Clients in der Datei **static-hosts.yaml** definiert.

Für jeden Client ist ein Eintrag unter **static_hosts** erforderlich.

## Mustereintrag

```
static_hosts:
    cpi0:
        name: cluster-pi-0
        MAC: b8:27:eb:bd:c0:b9
        IPv4: 10.152.64.100
```

