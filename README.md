# dig_DNS

1- Toutes les adresses IPv4 de www.wildcodeschool.com :
ubuntu@ubuntu-VirtualBox:~$ dig wildcodeschool.com +nocomments
; <<>> DiG 9.18.12-0ubuntu0.22.04.2-Ubuntu <<>> wildcodeschool.com +nocomments
;; global options: +cmd
;wildcodeschool.com. IN A
wildcodeschool.com. 300 IN A 104.21.79.167
wildcodeschool.com. 300 IN A 172.67.146.155
;; Query time: 27 msec
;; SERVER: 127.0.0.53#53(127.0.0.53) (UDP)
;; WHEN: Fri Aug 25 00:17:03 CEST 2023
;; MSG SIZE rcvd: 79

2- Toutes les adresses IPv6 d'odyssey.wildcodeschool.com :
nslookup -query=AAAA odyssey.wildcodeschool.com
Server: 192.168.1.1
Address: 192.168.1.1#53
Non-authoritative answer:
odyssey.wildcodeschool.com canonical name = ghs.googlehosted.com.
Name: ghs.googlehosted.com
Address: 2a00:1450:4007:80e::2013
