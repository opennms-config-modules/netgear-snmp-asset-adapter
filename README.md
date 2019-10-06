# netgear-snmp-asset-adapter

Will fill out the asset fields

* manufacturer
* modelNumber
* description
* serialNumber
* operatingSystem

## how to install

* install Asset snmp provisioning adapter:  `yum install opennms-plugin-provisioning-snmp-asset`
* copy the config package provided in config.xml into `snmp-asset-adapter-configuration.xml`
* make sure, SNMP is working correct on OpenNMS server and client side
* restart required
