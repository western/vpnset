# vpnset

setup openvpn and wireguard server

## how

wget https://raw.githubusercontent.com/western/vpnset/dev/vpnset && chmod +x vpnset

./vpnset

## when you run

you can choose this options:
* "init"

  if you primary get code and setup server
* "wireguard_status"

  systemctl status wg-quick@wg0.service
* "wireguard_new_client"

  make new client file
* "openvpn_status"

  systemctl status openvpn@server
* "openvpn_new_client"

  new ovpn file generate
* "quit"
