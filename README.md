>В основе cjdns лежит вера в то, что социальные проблемы, такие как необоснованные изъятия доменов и массовые прослушки, являются результатом устаревших протоколов, дающих слишком большую власть в руки малого количества людей. © Caleb James DeLisle

### Чаты и мосты в разных сетях:
- TELEGRAM: [`@meshnet`](https://t.me/meshnet)
- MATRIX-gate: 
  - [`#ru.meshnet:feneas.org`](https://matrix.to/#/#ru.meshnet:feneas.org)
  - [`#ru.meshnet:matrix.org`](https://matrix.to/#/#ru.meshnet:matrix.org)
- IRC-gate: `irc.freenode.net:6667#ru.meshnet`

[Форум](https://www.reddit.com/r/ru_meshnet/)  
[Правила чата](https://docs.google.com/document/d/1FmnWIkqs499e25ndv-8EuvHiVKQVjjhJwRuGSYYW_oY/edit?usp=sharing) и список других чатов сообщества  
[Статистика чата](http://combot.org/c/-1001135587237)  

[Спасение интернета](https://golos.io/p2p/@foxcool/spasenie-interneta)  
[Проектирование Mesh-сетей](https://nag.ru/articles/article/102081/proektirovanie-mesh-setey.html)  
[Подробная статья о CJDNS и Hyperboria](http://netwhood.online/2018/10/21/cjdns-theory-and-practice/)  
[Yggdrasil — альтернатива CJDNS](http://yggdrasil-network.github.io/)  
[Briar — он вам не телеграм](https://briarproject.org/)  
[Handbook of Peer-to-Peer Networking](http://gen.lib.rus.ec/book/index.php?md5=1AED81BE347826A6CD6BB0523EF81768)   
[List of wireless community networks by region](https://en.wikipedia.org/wiki/List_of_wireless_community_networks_by_region)  
[Using CJDNS with ZeroNet](https://proxy.zeronet.a0z.ru/1N6zp6jCXPBktNMPfe7UJBpQGyfCq7k2M8/?Post:51:Using+CJDNS+with+ZeroNet)  
[oneweb.world](https://oneweb.world/)  
[skylink-astro.net](http://www.skylink-astro.net/)  

### Что такое меш сеть? ([перевод](https://www.youtube.com/watch?v=SXgeNHP0IEg), [оригинал](http://youtube.com/watch?v=cK73sYM3g0Q))
- https://yggdrasil-network.github.io/
- https://github.com/cjdelisle/cjdns
- https://github.com/cjdelisle/cjdns/blob/master/doc/Whitepaper.md
- https://github.com/cjdelisle/cjdns/blob/master/doc/nat-gateway.md
- https://github.com/hyperboria
- https://github.com/hyperboria/bugs

### Публичные пиры (ноды):
- https://peers.fc00.io
- https://cjdns.cupivan.ru
- https://lvlts.github.io/hyperboria-peer-check
- https://github.com/hyperboria/peers
- https://github.com/yggdrasil-network/public-peers

### Карты сети:
- https://h.snode.cjd.li
- https://h.fc00.org
- https://yggdrasil-map.cwo.fi

### Ресурсы сети:
- https://hia.cjdns.ca
- https://yggdrasil-network.github.io/services.html

### Форумы:
- https://distributed.earth/c/distributed-networking
- https://h.forum.meshnet.pl
- https://reddit.com/r/darknetplan

### Другие чаты нашего комьюнити:
- @distributed
- @idistributed
- @p2p_disturbed
- @SDR_discussion
- @btr_politics

### Чаты внутри сети:
- irc.fc00.io#cjdns (matrix gate matrix.to/#/%23fc00-irc_%23cjdns:m.trnsz.com)
- irc.hypeirc.net#hyperboria

### Полезные ссылки:
- https://handshake.org
- https://github.com/mwarning/KadNode
- https://ipfs.io
- https://github.com/ipfs/go-ipfs
- https://github.com/libp2p/rust-libp2p
- https://datproject.org
- https://github.com/beakerbrowser/beaker
- https://zeronet.io
- https://zerotier.com

### Обсуждаем создание нового чата (форума):
- [`@influence_dev`](https://t.me/influence_dev)
- https://docs.google.com/document/d/1c6heldTZ4HfIqDoZUQBn0jw5zb8nFlW-2NCpeEWxiaA/edit#heading=h.bphueay59cks
- https://github.com/distributed-community/peerun

### Каналы по теме блокировок, криптоанархии и пр.:
- https://t.me/alexmakus
- https://t.me/darkfox_info
- https://t.me/EvilWirelessMan
- https://t.me/parisburns
- https://t.me/roskomsvoboda
- https://t.me/gip_24
- https://t.me/usher2
- https://t.me/zatelecom

### DC-HUB (от whoami, требуется поддержка клиентом ADC и IPv6. Например: ncdc, airdcpp. Eiskaltdc++ не поддерживает IPv6): 
- ygg: adc://[202:9877:2815:cd91:336:2a16:bfd9:7258]:1511

### http proxy (от whoami, резолвит OpenNIC, Namecoin, Emercoin адреса, открывает .onion, .i2p):
- cjdns: proxy.on.hyperboria.name:8118
- ygg: [202:9877:2815:cd91:336:2a16:bfd9:7258]:8118

### socks5 proxy (от whoami, доступно только через сети cjdns/yggdrasil):
- cjdns: socks5://[fc0d:5bba:969:82b6:8f96:1721:a6d1:4e35]:1080
- ygg: socks5://[202:9877:2815:cd91:336:2a16:bfd9:7258]:1080

### shadowsocks proxy (от whoami):
- QR-code и данные для подключения ищите по хештегу #shadowsocks_whoami
- рекомендую использовать аддон Proxy SwitchyOmega, есть в Firefox и Chrome
- тестируйте ваш днс http://dnsleaktest.com, по дефолту днс запросы идут не через proxy, а через вашего провайдера
- Ставьте галку "Proxy DNS when using SOCKS v5" (в Firefox) или используйте dnscrypt-proxy

### Feed лента чата #ru.meshnet в matrix:
- https://code.briarproject.org/briar/briar/tags?format=atom
- https://github.com/TokTok/c-toxcore/releases.atom
- https://github.com/cjdelisle/cjdns/releases.atom
- https://github.com/jech/babeld/releases.atom
- https://github.com/meshbird/meshbird/releases.atom
- https://github.com/mwarning/KadNode/releases.atom
- https://github.com/openwrt/openwrt/releases.atom
- https://github.com/shadowsocks/shadowsocks-libev/releases.atom
- https://github.com/shadowsocks/shadowsocks-rust/releases.atom
- https://github.com/shadowsocks/simple-obfs/releases.atom
- https://github.com/tox-rs/tox/releases.atom
- https://github.com/yggdrasil-network/yggdrasil-go/releases.atom
- https://gitlab.gnome.org/GNOME/fractal/tags?format=atom
- https://www.open-mesh.org/projects/open-mesh/news.atom
- https://www.reddit.com/r/darknetplan/.rss
- https://www.reddit.com/r/ru_meshnet/.rss
- https://www.youtube.com/feeds/videos.xml?user=RosKomSvoboda
