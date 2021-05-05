Ansible role for [mikrotik-exporter](https://github.com/nshttpd/mikrotik-exporter)

Sample config:
```yaml
mikrotik_exporter_devices:
  - name: router-core2
    address: 192.168.69.27
    user: telemetry
    password: pass
  - name: router-core1
    address: 192.168.69.26
    user: telemetry
    password: pass
mikrotik_exporter_features_bgp: true
mikrotik_exporter_features_conntrack: true
mikrotik_exporter_features_dhcp: true
mikrotik_exporter_features_dhcpl: true
mikrotik_exporter_features_dhcpv6: false
mikrotik_exporter_features_firmware: false
mikrotik_exporter_features_health: true
mikrotik_exporter_features_routes: true
mikrotik_exporter_features_poe: false
mikrotik_exporter_features_pools: true
mikrotik_exporter_features_optics: false
mikrotik_exporter_features_w60g: false
mikrotik_exporter_features_wlansta: false
mikrotik_exporter_features_wlanif: false
mikrotik_exporter_features_monitor: true
mikrotik_exporter_features_ipsec: true
mikrotik_exporter_features_lte: false
mikrotik_exporter_features_netwatch: false
```
