# Vanced LX-Source
- Modded lx-source js, resolved abnormal NetEase link parsing with api address 150.158.43.171:3000 (Maybe using another one deployed by vercel: https://neteasecloudmusicapi.vercel.app)

- And got local music files strean automatically across devices, hooray!

    You need to set a nginx autoindex or webdav server on the host that stored musics    

```
Basically just set the server on the device which to store your musics, and reroute requests for local files to the server, yep a minor one, but here just for convenience!
```

### (You need to alternate the API_LOC param in the js script)

Star me if this helped you! uwu~

(tbh i should fork the original source but its not a dedicated repo for that, so be it..
