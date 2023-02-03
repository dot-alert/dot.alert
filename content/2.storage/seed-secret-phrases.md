---
description: >-
  A description of the purpose of seed/secret phrases and their management in
  the Polkadot ecosystem.
---

# Seed/Secret Phrases

## What are Seed/Secret Phrases?

Seed/Secret phrases are the human-readable representation of the cryptographic key (also called "private key") that secures the access to an account. They come in a set format of 12 to 24 English words that are listed in a specific sequence for each account.

{% hint style="info" %}
**Derived accounts do not have a seed/secret phrase because they are branching out of a "Main" account.**&#x20;
{% endhint %}



A Polkadot account can be created from a variety of cryptography types based on the same seed/secret phrase. It is this seed/secret phrase that will be used to re-create/import the account across different wallets and/or different devices, provided there is support for the cryptography type used upon creation.

<figure><img src="../../.gitbook/assets/S_SPPJSApps.JPG" alt="Polkadot-JS Apps showing some cryptography types and their corresponding seed/secret phrase."><figcaption><p>An overview of some cryptography types and their corresponding seed/secret phrase on <a href="https://polkadot.js.org/apps/?rpc=wss%3A%2F%2Frpc.polkadot.io#/accounts"><em>Polkadot-JS Apps</em></a>.</p></figcaption></figure>



### How do Seed/Secret Phrases work?

When you create a Polkadot account, your [wallet](../../useful-tools/wallets.md) generates a seed/secret phrase for that specific account. You must note down this seed/secret phrase carefully, as it is the actual "key" needed to gain access to your assets. It is also possible to create new accounts from an existing account without generating additional seed/secret phrases: this is done via a process called "derivation".&#x20;

<figure><img src="../../.gitbook/assets/S_SPEnkrypt.JPG" alt="A view of main and derived accounts on Enkrypt wallet."><figcaption><p>Main and Derived accounts on <a href="https://www.enkrypt.com/"><em>Enkrypt wallet</em></a>.</p></figcaption></figure>



Some wallets only give you one chance to note down your seed/secret phrase at the beginning, after which they will not display it anymore. Other wallets allow you to see your account's seed/secret phrase at anytime by getting you to set up a password to lock your wallet's information beforehand. As a security measure, you will be asked to re-enter that password right before you can view any account's seed/secret phrase.

<figure><img src="../../.gitbook/assets/S_SPFearless (1).jpg" alt="The Fearless Wallet&#x27;s interface that requests users to a enter a PIN code."><figcaption><p>Account security setup on <a href="https://fearlesswallet.io/">Fearless wallet</a>.</p></figcaption></figure>

Features like email addresses and phone numbers that are offered by Centralised exchanges can never be used as substitute for a seed/secret phrase, because they are separate from the cryptographic keys of an account. For this reason, we say that wallets which provide a seed/secret phrase are "non-custodial", whereas wallets that do not generate a seed/secret phrase are "custodial" (i.e _"Not your keys, not your coins"_).



### Why are Seed/Secret Phrases Important?

Always remember that it is your seed/secret phrase (**not** your wallet!) that holds your assets. Therefore, you must write your seed/secret phrase on a paper and keep it in a safe physical location as soon as you create an account in a wallet; as this will be your backup for recovering your assets. Previously, some users have made the mistake of skipping this step and uninstalling the wallet from their device. Later on, they weren't able to retrieve their assets because they had no seed/secret phrase for their account.

<figure><img src="../../.gitbook/assets/S_SPParallel.JPG" alt="The interface of Parallel wallet displaying the seed/secret phrase of an account."><figcaption><p>Validating a seed/secret phrase backup on <a href="https://parallel.fi/"><em>Parallel wallet</em></a>.</p></figcaption></figure>



Since a seed/secret phrase is made of a unique sequence of random English words, it is important to store these words in the correct order and with the correct spelling. Users who have a visual impairment, dyslexia, and/or who are not proficient in written English might find it challenging to copy the words on a piece of paper one-by-one, but they must take the time to do so properly. Storing a screenshot and/or a copy of a seed/secret phrase in a digital device is not recommended, because these files can be accidentally leaked and/or deleted.

<figure><img src="../../.gitbook/assets/S_SPPolkawallet.jpg" alt="The interface of Polkawallet app asking users to confirm that they backed up their seed/secret phrase."><figcaption><p>Checking a seed/secret phrase sequence on <a href="https://polkawallet.io/">Polkawallet</a>.</p></figcaption></figure>

