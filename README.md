# Aluisyo Explorer
Block explorer for Aluisyo CryptoNote based cryptocurrency.

#### Installation

1) It takes data from daemon aluisyod. It should be accessible from the Internet. Run aluisyod with open port as follows:
```bash
./aluisyod --enable-cors="*" --enable_blockexplorer --rpc-bind-ip=0.0.0.0 --rpc-bind-port=19000
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.

### Development
Thanks To
Devs: @taegus @katz @devopsralf

### Note
A lot of this code is from the great Karbovanets/Karbowanec-Blockchain-Explorer
