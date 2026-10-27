password  -> projeto

enable
configure terminal
hostname NOME
banner motd #MENSAGEM#
enable secret class
interface gigabitEthernet 
description NOME
ip address IP MASCARA
no shutdown
exit
show running-config
show ip interface brief
show interfaces gigabitEthernet 
show ip route
copy running-config startup-config
tracert IP