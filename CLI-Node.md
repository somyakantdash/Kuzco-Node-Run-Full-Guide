# CLI Node Run Full Guide (PC and VPS for Both)



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

4️⃣ Start Node
```
aios-cli start
```

For VPS Only
```
PRESS CTRL+A+D (to run ur node continuously)
```

## Open Another Window for WSL or VPS

For VPS Only
```
screen -S cli-hyperspace
```

### Check Your Preference Model
```
aios-cli models list
```

1️⃣ Download Tier Model 
```
aios-cli models add hf:TheBloke/phi-2-GGUF:phi-2.Q4_K_M.gguf
```

2️⃣ Registered Your Tier
```
aios-cli hive login
```
```
aios-cli hive connect
```

3️⃣ Choose Your Tier (currently ranging from best to worst as 1-5)
```
aios-cli hive select-tier 5
```

4️⃣ To Check Your Current Multiplier and Points
```
aios-cli hive points
```

5️⃣ Check Your Node Status
```
aios-cli status
```

## If Node Not Working Then Kill Node and Reconnect
```
aios-cli kill
```
Then Start Node

## Import Your Private and Public Key
```
aios-cli hive whoami
```

## 🔶For Next Day Run This Command

#1 Open WSL and Put this Command 
```
source /root/.bashrc
```
Directly Run Start Command
```
aios-cli start
```
