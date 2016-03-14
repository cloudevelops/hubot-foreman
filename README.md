# hubot-foreman

A hubot script for interaction with foreman api


# Commands:

```
foreman s|search <pattern> - search and list of hosts and their last reports
foreman c|classes <fqdn>  - show puppet classes assigned to host
```




## Sample Interaction

```
user1>> hubot foreman search host
hubot>>
1. host0.domain.lan  id: 111
https://foreman.domain.com/hosts/host0.domain.lan
https://foreman.domain.com/hosts/host0.domain.lan/reports/last
2. host1.net.lan  id: 175
https://foreman.domain.com/hosts/host.net.lan
https://foreman.domain.com/hosts/host.net.lan/reports/last
3. host2.net.lan  id: 179
https://foreman.domain.com/hosts/host.net.lan
https://foreman.domain.com/hosts/host.net.lan/reports/last

```
