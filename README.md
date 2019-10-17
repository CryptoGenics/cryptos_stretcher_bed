# cryptos_stretcher_bed
Stretcher and Hospital Bed lay/push based off qalle-wheelchair
___

# Installation - Framework free
1. Clone this repository.
2. Extract the zip.
3. Change cryptos_stretcher_bed-master to cryptos_stretcher_bed
3. Put cryptos_stretcher_bed to your resource folder.
4. Add "start cryptos_stretcher_bed" in your "server.cfg".
5. Profit

# Installation - esx_ambulancejob version
1. Clone this repository.
2. Extract the zip.
3. move cryptos_stretcher.lua to esx_ambulancejob/client
3. open the esx_ambulancejob "__resource.lua"
4. Add 'client/cryptos_stretcher.lua'
5. client_scirpts should look something like this
```
client_scripts {
	'@es_extended/locale.lua',
	'locales/br.lua',
	'locales/en.lua',
	'locales/fi.lua',
	'locales/fr.lua',
	'locales/es.lua',
	'locales/sv.lua',
	'locales/pl.lua',
	'config.lua',
	'client/main.lua',
	'client/job.lua',
	'client/cryptos_stretcher.lua'
}
```
5. Profit

# Required resource
- es_ambulancejob (optional)
- stretcher used: https://www.lcpdfr.com/files/file/18046-body-bags/

# Made by
- CryptoGenics
- Based off qulle-wheelchair https://github.com/qalle-fivem/qalle-wheelchair
