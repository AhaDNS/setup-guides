# AhaDNS iOS setup guide

## iOS 14 or newer

We've created pre-configured mobileconfig files that will enable encrypted DNS-over-HTTPS on your iOS device on both Wi-Fi and cellular networks.  
Download links can be found below:

- [Netherlands DNS mobileconfig](https://raw.githubusercontent.com/AhaDNS/setup-guides/master/downloads/ahadns-nl.mobileconfig)
- [India DNS mobileconfig](https://raw.githubusercontent.com/AhaDNS/setup-guides/master/downloads/ahadns-in.mobileconfig)

### Mobileconfig instructions

1. Press “Allow” if asked to allow download.
2. In iOS, go to Settings -> General -> Device Management.
3. Press on the newly downloaded profile named “AhaDNS {Location}”.
4. Press “Install” in upper right corner.
5. Fill in your password and press “install” until complete.
6. Done! You’re now using encrypted DNS over HTTPS in all your networks!

## Older than iOS 14

On older devices, it's only possible to change DNS server for your Wi-Fi networks.  
You can change your Wi-Fi network DNS by following these instructions:

1. Open the Settings app, then go to Wi-Fi.
2. Tap on the ⓘ icon on the right-hand side of the Wi-Fi network of your choice.
3. In the DNS section, go to Configure DNS.
4. Select Manual.
5. In the DNS SERVERS list, remove all addresses (if any) then add any of the AhaDNS server IP addresses.
6. Tap Save.
