# zabbix-hddtemp

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

Disk temperature template for Zabbix via hddtemp

#Installation
1.Install hddtemp utility (apt-get isntall hddtemp)
2.Make sure Zabbix agent have access to run hddtemp (sudo chmod +s `which hddtemp` or add zabbix to sudo)
3.Copy hddtemp.conf to /etc/zabbix/zabbix_agentd.conf.d/
4.Import zbx_hddtemp.xml in Zabbix templates 

vovka@krevedko.su

