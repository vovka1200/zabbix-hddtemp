# zabbix-hddtemp
Disk temperature template for Zabbix via hddtemp

Installation:
1.Install hddtemp utility (apt-get isntall hddtemp)
2.Make sure Zabbix agent have access to run hddtemp (sudo chmod +s `which hddtemp` or add zabbix to sudo)
2.Copy hddtemp.conf to /etc/zabbix/zabbix_agentd.conf.d/
3.Import zbx_hddtemp.xml in Zabbix templates 

vovka@krevedko.su
