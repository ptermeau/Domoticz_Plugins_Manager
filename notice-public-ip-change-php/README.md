# Notice Publique IP Change

Prévenir l'utilisateur que l'ip publique de domoticz vient de changer

![Preview img](screen/ip_domoticz.png)

# Configurations

config.json
```json
{
	"active": true,
	"notice_free":{
		"active": true,
		"user": "********",
		"pass": "********",
		"msg": "[ALERTE DOMOTIQUE] IP Publique change to -> %IP%"
	},
	"notice_mail":{
		"active": true,
		"from": "domoticz@no-reply.fr",
		"mail_to": "aur.loy@gmail.com",
		"msg": "[ALERTE DOMOTIQUE] IP Publique change to -> %IP%"
	},
	"notice_domoticz":{
		"active": true,
		"widget_id" : 123
	}
}
```

# Liens
[Raspberry Pi 3] (http://www.amazon.fr/gp/product/B01CCOXV34/ref=as_li_tl?ie=UTF8&camp=1642&creative=19458&creativeASIN=B01CCOXV34&linkCode=as2&tag=aureli-21)<br />
[Domoticz](https://domoticz.com/)<br />

# TODO
- [ ] Nouveaux scripts
