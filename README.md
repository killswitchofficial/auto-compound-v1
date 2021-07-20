### Contract Role
```
Morroc (hub) = entry point for user to deposit / withdraw
Alberta (router) = helper for swapping given deposit to target asset or swapping asset to what user want
Izlude (vault) = entry point before send to stategy. this is where share calculation happen
Byalan (strategy) = contract to stake asset to farm and used to be call for compound
Prontera (masterchef) = reward killswitch token to user per share (jellopy)
PronteraCastle = where ksw token store and for recording withdraw amount from each category
Jellopy (shares) = user's shares from vault (vault lp)
```


### user flow
user (deposit/withdraw) => morroc => (alberta) => izlude => byalan