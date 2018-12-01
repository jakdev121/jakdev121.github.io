##################################################
### QR Code scanner for login hotspot MikroTik ###
################### Cara pakai ###################

1. Tambahkan button di login.html
```
<button onclick="window.location='jakdev.github.io';">QR Code</button>
```
2. Tambahkan script berikut di MikroTik via Terminal.
```
/ip hotspot walled-garden ip
add action=accept comment="Jak QR Code Scanner" disabled=no dst-host=jakdev.github.io
```
##################################################
##################################################
