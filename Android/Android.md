# AhaDNS Android setup guide

## Android 9 Pie and higher

Private DNS is available on Android 9 Pie and newer. It will enable encrypted DNS-over-TLS on your Android device on both Wi-Fi and cellular networks.  
Follow the instructions below:

1. Go to Settings → Network & internet → Advanced → Private DNS.
2. Select the Private DNS provider hostname option.
3. Enter any of the AhaDNS DoT endpoints that can be found at [ahadns.com/dns-over-tls/](https://ahadns.com/dns-over-tls/)
   - i.e. `dot.nl.ahadns.net` for using the Netherlands server.

## Older than Android 9

On older devices, it's only possible to change DNS server for your Wi-Fi networks.  
You can change your Wi-Fi network DNS by following these instructions:

1. Go to Settings → Wi-Fi.
2. Long-press the network you are connected to then tap Modify Network.
3. On some devices, you may need to check the box for Advanced to see further settings. To adjust your DNS settings, you will need to switch the IP settings from DHCP to Static.
4. Enter any of the AhaDNS server IP addresses for DNS 1 and DNS 2.
