# helium-validators

This repository contains scripts used for setup and maintenance of Helium network validators. The new validator script will update server packages, update bash aliases,
then launch a new validator in docker. To learn more about validators, visit: https://docs.helium.com/mine-hnt/validators/

To launch a mainnet validator on a new server: 
```
wget https://raw.githubusercontent.com/the-wildcard/helium-validators/main/new_validator
chmod 755 new_validator
./new_validator
```

To launch a testnet validator on a new server: 
```
wget https://raw.githubusercontent.com/the-wildcard/helium-validators/main/new_testnet_validator
chmod 755 new_testnet_validator
./new_testnet_validator
```

To update a mainnet validator: 
```
wget https://raw.githubusercontent.com/the-wildcard/helium-validators/main/update_validator
chmod 755 update_validator
./update_validator
```
