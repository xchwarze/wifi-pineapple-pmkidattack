## PMKIDAttack

The module automates PMKID attack for NANO/TETRA 2.7


**Module installation for Tetra:**
```
opkg update && opkg install git git-http
cd /pineapple/modules/
git clone https://github.com/xchwarze/wifi-pineapple-pmkidattack PMKIDAttack
chmod +x -R /pineapple/modules/PMKIDAttack/scripts
```

**Module installation for NANO:**
```
opkg update && opkg --dest sd install git git-http
cd /sd/modules/
git clone https://github.com/xchwarze/wifi-pineapple-pmkidattack PMKIDAttack
chmod +x -R /sd/modules/PMKIDAttack/scripts
```
