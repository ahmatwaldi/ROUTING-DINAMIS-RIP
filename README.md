🔹 Hari 4: Routing Dinamis dengan RIP
🎯 Tujuan:
Mempelajari dan memahami konsep Routing Dinamis menggunakan protokol RIP (Routing Information Protocol) untuk pertukaran informasi jaringan secara otomatis antar router.

🧠 Konsep:
RIP memungkinkan router untuk saling bertukar informasi jaringan tanpa perlu menambahkan routing manual.

RIP bekerja menggunakan hop count (maks. 15 hop).

Ideal untuk jaringan kecil-menengah.

🧩 Topologi:
2 Router (Router A & B)

2 Switch

4 PC

IP antar router: 10.10.10.0/24

IP LAN A: 192.168.1.0/24

IP LAN B: 192.168.2.0/24


⚙️ Konfigurasi RIP (pada masing-masing router):

-ROUTER A

Router(config)# router rip

Router(config-router)# version 2

Router(config-router)# network 192.168.1.0

Router(config-router)# network 10.10.10.0


-ROUTER B

Router(config)# router rip

Router(config-router)# version 2

Router(config-router)# network 192.168.2.0

Router(config-router)# network 10.10.20.0





