Здесь представлены шаблоны виртуальных машин для vRA (VMware Aria Automation)

Конфигурация происходит при помощи cloud-init. Протестировано на Ubuntu cloud image

Для сокращения кода в INPUTs использованы "Группы свойств" $ref: /ref/property-groups/ (https://techdocs.broadcom.com/us/en/vmware-cis/aria/aria-automation/8-17/assembler-on-prem-using-and-managing-master-map-8-17/maphead-designing-your-deployments/property-groups-general/property-groups-inputs.html).
Можно заменить в inputs укзав через oneof/enum. Или явно указать в resources:properties:

cloud-config можно закодировать в base64 и передать через user-data
