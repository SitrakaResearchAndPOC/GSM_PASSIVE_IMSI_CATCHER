# GSM_OSMOBTS_PASSIVE_IMSI_CATCHER
* ADVANTAGES : it's legal 
* INCONVENIENTS: capturing only, IMSI only, traffic cipher, not efficient

# Devices : RTL_SDR
# OS : DragonOS R30
* [uses](https://www.youtube.com/watch?v=uU7JrwAgmuE)
* [Installation](https://www.youtube.com/watch?v=e66_7ABKMnQ)

# Use netmonitor on android or cellmapper or arfcncalculator
* [cell_mapper](https://www.cellmapper.net/arfcn?net=GSM&ARFCN=977&MCC=0)  
grgsm_scanner  
grgsm_scanner --help  
grgsm_scanner --args=rtlsdr -v -d  
grgsm_livemon -f 945.0M --args=rtlsdr  
python3 ./simple_IMSI-catcher.py  --sniff  


