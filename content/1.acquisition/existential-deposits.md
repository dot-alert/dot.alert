# Existential deposits

## _What are they?_

Existential deposits (ED) are a specific number of coins needed to ensure that your account is kept "alive" on the network, whether it be a Relay chain (Polkadot, Kusama), a Parachain (Parallel Finance, Interlay) or a Common Good parachain (Statemine, Statemint).&#x20;

{% hint style="info" %}
**An account is activated on a network once its balance is **_**above**_** the existential deposit.**&#x20;
{% endhint %}

Since each chain sets its own existential deposit, users rely on wallets to keep track of existential deposits alongside their balances. Most wallets have in-built mechanisms to prevent accounts from falling below the existential deposit of their respective networks. Still, certain wallets and dapps allow users to make custom decisions regarding existential deposits.

![Management of existential deposits on Polkadot-JS Apps.](../../.gitbook/assets/A\_EDCustomSend.JPG)



## _How do they work?_

Existential deposits work as an anti-spam measure on the networks. If your account's balance drops below this amount, your account will be deactivated and any balance that was left will be sent to the network's Treasury. You can always reactivate an account at a later date by receiving an amount greater than the required existential deposit.

![Polkadot's existential deposit requirements on Polkadot Gifts.](../../.gitbook/assets/A\_EDGift.JPG)

It is important to note that existential deposits apply to account balances altogether. You will not suffer deactivation or loss of funds if the account has:

* **locked** balances (ex: vote with conviction, linear vesting)
* **bonded** balances (ex: staking/unstaking funds, proposing treasury spends)
* **reserved** balances (ex: vote delegations, on-chain identity, proxy setups)

## Why are they important?

Before you can receive custom assets on Common Good parachains, you will need to activate your account on these Common Good networks. Being aware of existential deposit requirements for these networks will prevent delays and mishaps while transacting.

![Statemine accounts need an existential deposit to receive assets from Karura.](<../../.gitbook/assets/A\_EDStatemine (1).JPG>)

Numerous DotSama projects use data related to active accounts and on-chain activity as a benchmark when running their rewards and airdrop campaigns. An account that is accidentally deactivated, even for as little as a few minutes, could therefore disqualify you from receiving these extra perks.

In the past, many users have made the mistake of keeping fractions of the existential deposit after spinning a new account, and then lost their funds. Because they didn't know about existential deposits, they concluded that their wallet was hacked or that the network was faulty. Also, given the fluctuations in coin valuations, what might have been a small amount at the time of the loss could very well become a substantial sum that will never be recovered.

