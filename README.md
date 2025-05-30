# zbx7-auto-reg

The independent work - Vagrant and Zabbix Agent2 7.0 LTS - Auto-registration to Appliance

# Zabbix Appliance monitoring Ubuntu by Agent2

V adresáři Ubuntu máte připraven Vagrantfile z prvního pololetí se scripty
pro registraci na server enceladus.

## Požadované známkované úkoly

- Použijte svůj Zabbix server - Zabbix aplliance, kde máte z minuleho zadání funkční interní síť 192.168.1.0/24
- Upravte Vagrantfile tak, aby se Vám vytvořil virtuální server, který bude mít druhou síťovou kartu a nastavte na ni IPv4 adresu 192.168.1.3 - intnet
- Vytvořte v Zabbbix GUI Appliance auto-registracni pravidlo na základě HostMetadata=SPOS - (Hostgroup, Tag, Template).
- Upravte instalační a konfigurační scripty tak, aby jste nainstalovali Zabbix agent2 verze 7.0 LTS a nastavili konfiguraci pro auto-registraci agenta na váš Zabbix server (již existující Zabbix Appliance s Alma Linux).
- Výsledný registrovaný host s unikátním jmenem vložte jako Screenshot do adresáře Images.
- Upravte Ubuntu/README.md tak, aby informace v něm odpovídaly upravám ve scriptech.

# Nápověda

- Zabbix [Version 7.0 LTS - repo](https://www.zabbix.com/download?zabbix=7.0&os_distribution=ubuntu&os_version=22.04&components=agent_2&db=&ws=)
- Vagrant [virtualbox internal network](https://developer.hashicorp.com/vagrant/docs/providers/virtualbox/networking#virtualbox-internal-network)

...
