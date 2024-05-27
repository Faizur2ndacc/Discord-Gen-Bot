<br/>
<p align="center">
  <a href="https://github.com/VatosV2/Nexus-MultiTool">
    <img src="https://cdn.discordapp.com/attachments/1209895707675205653/1209919950689411092/RmDJt7xVhNFTA6yvy3EWfsTbki45EeI67K93h75F_1.png?ex=66499303&is=66484183&hm=71e465675a795e95734ca80f5c82830917e77e532c2d9d7b98cedcf48214fcc0&" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">[Nexus Gen Bot] - discord.gg/nexustools</h3>

  <p align="center">
    Nexus Gen bot - Take your Gen server to the Next level.
    <br/>
    <br/>
    <a href="https://discord.gg/nexustools">Discord</a>
  </p>
</p>
<h3 align="center";">Please Star To support this project for free! ⭐</h3>
<h3 align="center";">Linux is Supported! ✅</h3>

## Screenshot
![ss](https://media.discordapp.net/attachments/1202027634037620786/1242813184994443385/8AA85B1D-7AC2-4380-9BFD-BBEB4D81CE16.jpg?ex=664f3379&is=664de1f9&hm=b8644b5f608481ab9b1a95bf772f998361ce957652765300173b316d1787531a&=&format=webp&width=1246&height=701)

## Release
- 25 Stars For Release ⭐ ✅
- 50 Stars For V2 ⭐ ❌

## Functions
```yaml
/add_service {gen_type} {service} {file(optional)} ✅ 

/gen                         ✅
/booster_gen                 ✅
/premium_gen                 ✅

/stock                       ✅    
/booster_stock               ✅
/premium_stock               ✅

/restock_free_gen            ✅
/restock_booster_gen         ✅
/restock_premium_gen         ✅

/remove_free_service         ✅
/remove_booster_service      ✅
/remove_premium_service      ✅

/clear_free_stock            ✅
/clear_booster_stock         ✅
/clear_premium_stock         ✅

/whitelist                   ✅
/unwhitelist                 ✅
/get_log_file                ✅

Free Gen If Vanity in status ✅
Status Change Logs           ✅
Logs                         ✅

```

## Config
```json
{
    "bot_token": "bot_token",
    "owner_id": 1234567891011121134,
    "server_id": 1234567891011121134,
    "bot_status": "discord.gg/nexustools",
    "free_gen": {
        "free_gen_role": 1234567891011121134,
        "free_gen_channel": 1234567891011121134,
        "free_gen_status": "discord.gg/nexustools",
        "status_log_channel": 1234567891011121134,
        "free_gen_cooldown": 120,
        "free_gen_folder": "stocks/stock"
    },
    "boost_gen": {
        "boost_gen_role": 1234567891011121134,
        "boost_gen_channel": 1234567891011121134,
        "boost_gen_cooldown": 60,
        "boost_gen_folder": "stocks/boost_gen_stock"
    },
    "premium_gen": {
        "premium_gen_role": 1234567891011121134,
        "premium_gen_channel": 1234567891011121134,
        "premium_gen_cooldown": 120,
        "premium_gen_folder": "stocks/premium_gen_stock"
    },
    "logs": {
        "free_gen_log_webhook": "Discord Webhook To log Free gen",
        "booster_gen_log_webhook": "Discord Webhook To log booster gen",
        "premium_gen_log_webhook": "Discord Webhook To log premium gen",
        "admin_commands_log_webhook": "Discord Webhook To log admin commands"
    }
}
```
