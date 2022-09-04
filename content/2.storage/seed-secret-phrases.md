# Seed/Secret phrases

## What are they?

Seed/Secret phrases are the human-readable representation of the cryptographic key (also called "private key") that secures the access to an account. They come in a set format of 12 to 24 English words that are listed in a specific sequence for each account.

{% hint style="info" %}
**Derived accounts do not have a seed/secret phrase because they are branching out of a "Main" account.**&#x20;
{% endhint %}



A DotSama account can be created from a variety of cryptography types based on the same seed/secret phrase. It is this seed/secret phrase that will be used to re-create/import the account across different wallets and/or different devices, provided there is support for the cryptography type used upon creation.

![An overview of some cryptography types and the corresponding seed/secret phrase on Polkadot-JS Apps.](../../.gitbook/assets/S\_SPPJSApps.JPG)



## How do they work?

When you create a DotSama account, your wallet generates a seed/secret phrase for that specific account. You must note down this seed/secret phrase carefully, as it is the actual "key" needed to gain access to your assets. It is also possible to create new accounts from an existing account without generating additional seed/secret phrases: this is done via a process called "derivation".&#x20;

![Main and Derived accounts on Enkrypt wallet.](../../.gitbook/assets/S\_SPEnkrypt.JPG)

Some wallets only give you one chance to note down your seed/secret phrase at the beginning, after which they will not display it anymore. Other wallets allow you to see your account's seed/secret phrase at anytime by getting you to set up a password to lock your wallet's information beforehand. As a security measure, you will be asked to re-enter that password right before you can view any account's seed/secret phrase.&#x20;

![Account security setup on Fearless wallet.](<../../.gitbook/assets/S\_SPFearless (1).jpg>)

Features like email addresses and phone numbers that are offered by Centralised exchanges can never be used as substitute for a seed/secret phrase, because they are separate from the cryptographic keys of an account. For this reason, we say that wallets which provide a seed/secret phrase are "non-custodial", whereas wallets that do not generate a seed/secret phrase are "custodial" (i.e _"Not your keys, not your coins"_).



## Why are they important?

Always remember that it is your seed/secret phrase (**not** your wallet!) that holds your assets. Therefore, you must write your seed/secret phrase on a paper and keep it in a safe physical location as soon as you create an account in a wallet; as this will be your backup for recovering your assets. Previously, some users have made the mistake of skipping this step and uninstalling the wallet from their device. Later on, they weren't able to retrieve their assets because they had no seed/secret phrase for their account.

![Validating a seed/secret phrase backup on Parallel wallet.](../../.gitbook/assets/S\_SPParallel.JPG)

Since a seed/secret phrase is made of a unique sequence of random English words, it is important to store these words in the correct order and with the correct spelling. Users who have a visual impairment, dyslexia, and/or who are not proficient in written English will find it challenging to copy the words on a piece of paper one-by-one, but they must take the time to do so properly. Storing a screenshot and/or a copy of a seed/secret phrase in a digital device is not recommended, because these files can be accidentally leaked and/or deleted.

![Checking a seed/secret phrase sequence on Polkawallet.](../../.gitbook/assets/S\_SPPolkawallet.jpg)

