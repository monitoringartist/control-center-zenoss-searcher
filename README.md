Zenoss Searcher Control Center template
=======================================

[Dockerized Zenoss Searcher](http://monitoringartist.github.io/zenoss-searcher/)
template for [Zenoss Control Center](http://controlcenter.io/)

[![Paypal donate button](http://jangaraj.com/img/github-donate-button02.png)]
(https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=8LB6J222WRUZ4)

Installation
============

- Import provided template
- Deploy Zenoss Searcher Application
- Start and use it - default vhost zenoss-searcher

Known issues
============

- health checks are failing

Troubleshooting
===============

Check if app is running:

```
[ccuser@ccmaster] curl -sk --header 'Host: zenoss-searcher.local' 'https://127.0.0.1:443' | grep 'github.com/monitoringartist/zenoss-searcher'
    <a href="https://github.com/monitoringartist/zenoss-searcher" target="_blank" class="forkme">
```

If you can see this output in command line '<a href="https://github.com/monitoringartist/zenoss-searcher" target="_blank" class="forkme">' and you are not able to see app in your browser, then you have some problem with DNS records/hosts file.

Author
======

[Devops Monitoring zExpert](http://www.jangaraj.com 'DevOps / Docker / Zabbix / Zenoss / Monitoring'), who loves monitoring 
systems, which start with letter Z. Those are Zabbix and Zenoss.

Professional monitoring services:

[![Monitoring Artist](http://monitoringartist.com/img/github-monitoring-artist-logo.jpg)]
(http://www.monitoringartist.com 'DevOps / Docker / Zabbix / Zenoss / Monitoring')
