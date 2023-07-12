# GSM_OSMOBTS_PASSIVE_IMSI_CATCHER
* ADVANTAGES : it's legal 
* INCONVENIENTS: capturing only, IMSI only, traffic cipher, not efficient

# Devices : RTL_SDR
# OS : DragonOS R30
* [uses](https://www.youtube.com/watch?v=uU7JrwAgmuE)
* [Installation](https://www.youtube.com/watch?v=e66_7ABKMnQ)

# Use netmonitor on android or cellmapper or arfcncalculator
* [cell_mapper](https://www.cellmapper.net/arfcn?net=GSM&ARFCN=977&MCC=0)
```
grgsm_scanner  
```
```
grgsm_scanner --help  
```
```
grgsm_scanner --args=rtlsdr -v -d  
```
```
grgsm_livemon -f 945.0M --args=rtlsdr  
```
```
python3 ./simple_IMSI-catcher.py  --sniff  
```
# Perspectives
* Passive sniffing could capture call without hopping frequency and with A51 cracking
* Sniffing call could be done with motorola phone
* Sniffing conference by [kartsen nohl et sylvain Minaut](https://www.youtube.com/watch?v=lsIriAdbttc&pp=ygUTZ3NtIHNuaWZmaW5nIDogMjdjMw%3D%3D)
* Table could be found at [infocon](https://infocon.org/rainbow%20tables/A51/) or [srslab](https://opensource.srlabs.de/projects/a51-decrypt/files) or [0xh4di](https://github.com/0xh4di/GSMDecryption)
* Tutorial of [Crazy Danish Hacker](https://www.youtube.com/playlist?list=PLRovDyowOn5F_TFotx0n8A79ToZYD2lOvsniffing)
* Tutorial of [VK8FOES](https://www.youtube.com/playlist?list=PLRovDyowOn5F_TFotx0n8A79ToZYD2lOv)
* Tutorial of [Bastien baranoff](https://www.youtube.com/watch?v=eRIC3QhOO2Q&pp=ygUIZ3NtIGRla2E%3D)
* Real time cracking [brmlab](https://brmlab.cz/project/gsm/start) and [deka](https://brmlab.cz/project/gsm/deka/start)

