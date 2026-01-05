# GTAO PS3

> **Note:** This server currently supports **PS3 only**. **Xbox 360 support is not implemented**, as testing hardware is unavailable.

## Running on VPS

To test the server on VPS, GTA Online needs to be redirected to certain Rockstar endpoints from your server. This can be done via **IIS Manager** on your **Windows OVH VPS**.  
Domains to redirect:

- `ros.gtao.ca`
- ros -> GET Reqeust to 'tunables.gtao.ca
- ros -> POST Reqeust to 'prod.ros.gtao.ca
  
U can point ur **VPS IP** to your domains in **IIS Manager**

Install **Caddy** make a config file with your **domains** and point it to your **VPS IP** in caddy.json

## Required Files

You will need one of these EBOOTs to run the server:

[GTA EBOOTs Collection](https://cdn.discordapp.com/attachments/1378496462693994618/1441881014287728701/GTA_eboots.rar?ex=69542f56&is=6952ddd6&hm=467da643afa946234dd57b42908720862831022c0442bcfc1ead5750a18204ec&)

[U can patch and build your own eboot with this code](https://github.com/Saufari/patch_eboots/)
**Point it to your ros domain u bought** [u can buy cheap domains here](https://spaceship.com)

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
- Bababoey88 **(UGC FIXES)**
- SkyDreamMoDz **(AUTH, XUID FIXES)**
