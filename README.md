# Managing IP Addresses in Linux

## To manage IP addresses on your Linux system, you can use the following commands:

+ Adding an IP Address
  ```bash
  ip addr add 10.22.30.44/16 dev wlan2
  ```

+ Remove the specified IP address from the network interface
  ```bash
  ip addr del 10.22.30.44/16 dev wlan2
  ```

+ Remove all IP addresses from the specified network interface
  ```bash
  ip addr flush dev wlan2
  ```
