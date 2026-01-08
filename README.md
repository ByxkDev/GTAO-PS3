9# GTAO PS3

> **Note:** This server currently supports **PS3 only**. **Xbox 360 support is not implemented**, as testing hardware is unavailable.

## Running on VPS

To test the server on VPS, GTA Online needs to be redirected to certain Rockstar endpoints from your server. This can be done trough **IIS Manager** and **Caddy** on your **Windows OVH VPS**.  
Domains to redirect:

- `ros.gtao.ca`
- ros -> GET Reqeust to `tunables.gtao.ca`
- ros -> POST Reqeust to `prod.ros.gtao.ca`
  
U can point ur **VPS IP** to your domains in **IIS Manager**

Install **Caddy** make a config file called **caddy.json**

**redirect your ros sub-domain to the other sub-domains in caddy.json**

cmd -> Caddy Run --config caddy.json

## Required Files

You will need this to run your server:

[U can patch the domain in eboot with this code](https://github.com/Safauri/patch_eboots/)

**Point it to your ros sub-domain, u need to buy a normal domain first** 

[U can buy a Windows VPS here](https://www.ovhcloud.com/en/vps/) 

[U can buy cheap domains here](https://spaceship.com)

## Contributions

Contributions are welcome. You can help by:

- Implementing endpoints  
- Fixing bugs  

## Contact

For any issues or questions, you can reach out to **Byxk on Discord** or contact me here -> **cutzpaypal@gmail.com**

## Credits

Thanks to the following contributors:

- Snow  
- Atlas  
- Dread  
- Avieah
- Ventura **(check.json, eventschedule-en.json)**
- SkyDreamMoDz **(AUTH And XUID Fixes, tracks.json)**
- ByxkDev **(VPS Tutorial, UGC Publish + Discord Embed Function)**
