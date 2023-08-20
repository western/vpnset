# vpnset

setup openvpn and wireguard server

## how

wget https://raw.githubusercontent.com/western/vpnset/dev/vpnset && chmod +x vpnset

./vpnset

## when you run

you can choose this options:
1. "init"

  if you primary get code and setup server
  
2. "wireguard_status"

  systemctl status wg-quick@wg0.service
  
3. "wireguard_new_client"

  make new client file
  
4. "openvpn_status"

  systemctl status openvpn@server
  
5. "openvpn_new_client"

  new ovpn file generate
  
6. "wireguard_enable"

7. "openvpn_enable"
  
8. "quit"
