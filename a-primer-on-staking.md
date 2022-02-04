### ✨ A Primer on Staking

You can relax, because this one is simple. Staking is the profit distribution mechanism of TwzFinance.
It is designed as one of the dominant strategy for participants; besides bonding the best thing to do will likely be to just stake, hold, and compound.

Let’s go over how it works:

### Staking

To stake ZONE, you go to our website and select “stake.” You will send your ZONE to the staking contract and receive TWLT at the rate determined by the current rebase.

### Unstaking

To unstake ZONE, you go to our website and select “unstake.” 
You send TWLT back to the staking contract to receive ZONE at the rate determined by the current rebase.

### Rebase

The protocol distributes tokens by sending them to the staking contract without asking for TWLT back. 
This increases the ratio of ZONE staked to TWLT outstanding, and results in a rebase to correct the difference.

### For example: 

```
    there are 500K ZONE staked and 500K TWLT outstanding. The protocol produced $5k profit for the day, which it uses to mint and back 5k ZONE. 
    It sends those ZONE to the staking contract; there are now 505k ZONE staked and 500K TWLT outstanding. TWLT supply needs to increase by 5k, 
    or 1%, to return to balance. So, TWLT is rebased up by 1%.

```

The only caveat is that rebases occur retroactively. The end of epoch 100 triggers a rebase of profits from epoch 99. 
This delay lets you see what you’re missing if you want to unstake or what you’ll get if you want to stake.

### Conclusion

Staking is how we distribute profits equitably to participants. Through TWLT, everyone receives the same percentage profit per epoch. 
Rebasing also allows us to compound yield with no need to harvest or do anything except hold.
