Project used to simulate a intranet using docker

###

== Para testar ==

ntp: ntpdate -q 172.18.0.3

ngix: Abrir o navegador em http://localhost

samba: smbclient //localhost/Public -U <username>%<password>

ssh: ssh root@localhost -p 3022
     a senha é "root"

bind9: nslookup <nome_do_servico>.<nome_da_zona> <ip_do_dns_server>
   ex: nslookup sshDocker.ghostDev.ua 172.18.0.6