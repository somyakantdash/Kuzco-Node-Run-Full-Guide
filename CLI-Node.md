# CLI Node Run Full Guide (PC and VPS for Both)

### Offical Docs Guide - https://docs.inference.supply/quick-start

## Make Account

1. Register at [kuzco.xyz/register](https://kuzco.xyz/register)
2. Verify your email

1️⃣ Dependencies for WINDOWS & LINUX & VPS
```
sudo apt update
sudo apt upgrade -y
```

For VPS Only
```
apt install screen -y
```

2️⃣ Download Some Files
```
curl -fsSL https://kuzco.xyz/install.sh | sh
```

For VPS Only
```
screen -S kuzco
```

3️⃣ Initialize your Kuzco worker
```
kuzco init
```
Then Put Your Registered Email ID & Password
Then Put your Worker name & Press Enter

For VPS Only
```
PRESS CTRL+A+D (to run ur node continuously)
```


## 🔶For Next Day Run This Command

#1 Open WSL and Put this Command 
```
kuzco init
```
Then Put Your Registered Email ID & Password
Then Put your Worker name & Press Enter
