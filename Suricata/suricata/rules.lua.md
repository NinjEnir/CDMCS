# LUA in rules

see:

* http://suricata.readthedocs.io/en/latest/rules/rule-lua-scripting.html


see also:
* https://github.com/regit/luaevilbit
* https://github.com/jvdroit/Suricata-rules
* https://github.com/EmergingThreats/et-luajit-scripts

exercises:

Implement TLS self signed certificates alert:
* https://www.stamus-networks.com/2015/07/24/finding-self-signed-tls-certificates-suricata-and-luajit-scripting/

Implement matching on a list of domains using lua.

For a list ["toto.com", "titi.com"], we want to alert on requests to  www.toto.com but not on "toto.comic.com"
Help on lua and DNS can be found in:
* http://archive.hack.lu/2014/hacklu-joker-presentation.pdf
