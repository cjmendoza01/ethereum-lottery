# Simple Lottery

 * Player Tier starts to buy tickets(Function to buy ticket/s)

 * Admin Tier starts the lottery and indicates the deadline(Only the Owner can start and set the deadline of the lottery), Ticket Closing(ticket closes automatically once the set deadline is finished), Draw Winner(Winner is revealed)

 * Player Tier Checks Draw/Outcome(Player will be notified if he/she won any prizes)

 * Admin Tier Transfer winning prize(Admin sends the prize to the winners of the lottery)

 * Player Tier Claim Prize(Player will be receiving the prize thru their accounts)

____

# RNG Lottery

### Customer Tier
```
Start
Choose draw schedule of the lottery
Buy ticket
```

### Owner Tier
```
Start
Set ticket time and schedule of lottery
Set revealing time and schedule of lottery
Draw winner
Transferring of winners prize
```

### Chaincode Tier
```
Check Schedule and time of lottery
Submit commitment (if any ticket was bought)
Revealing period
Get randomized winning numbers
```

# Recurring Lottery

### Customers Tier
```
Start
Set numbers of tickets to buy
Buy tickets
```

### Owner Tier
```
Start
Set lottery duration
Set ticket price
Draw winner
Transfer prize to winner
```
### Chaincode
```
Check round expiration
Get list of ticket buyers
Get randomized winning numbers
```
___

# Powerball Lottery

### Customer Tier
```
Start
Select lottery number
buy tickets
Prize will be given to account once he/she wins with her tickets
```

### Owner Tier
```
Start
Verify tickets
Draw winning ticket
Verify winner
Give prize to the winner
```

### Chaincode Tier
```
Verify Round expiry
Update tickets
Start lottery draw numbers
Check if count matches
Calculate number of matches
```
