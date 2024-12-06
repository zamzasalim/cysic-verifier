<p style="font-size:14px" align="right">
<a href="https://t.me/airdropasc" target="_blank">Join our telegram <img src="https://user-images.githubusercontent.com/50621007/183283867-56b4d69f-bc6e-4939-b00a-72aa019d1aea.png" width="30"/></a>
</p>

<p align="center">
  <img height="300" height="auto" src="https://user-images.githubusercontent.com/109174478/209359981-dc19b4bf-854d-4a2a-b803-2547a7fa43f2.jpg">
</p>

# CYSIC-VERIFIER
## Register Node
- Join Testnet : https://testnet.cysic.xyz/m/referral/invite?code=9bf91 **( Limited Code )**
- Connect Wallet Metamask & Keplr
- Claim Faucet
- Done
## Running Node Verifier
- **Auto Install**
  ```
  bash <(curl -s https://data.zamzasalim.xyz/file/uploads/cysic.sh)
  ```
- **Cek Logs**
  ```
  sudo journalctl -u cysic -f --no-hostname -o cat
  ```
## Delete Node ( Jika sudah End )
```
sudo systemctl stop cysic
sudo systemctl disable cysic
sudo rm /etc/systemd/system/cysic.service
sudo systemctl daemon-reload
rm -rf ~/cysic-verifier
rm ~/setup_linux.sh
```
