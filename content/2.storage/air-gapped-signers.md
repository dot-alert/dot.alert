# Air-gapped signers

## What are they?

Air-gapped signers are wallets that combine a non-connected mobile phone used as a vault for private keys with a third-party mobile or desktop app to sign transactions offline. Air-gapped signers are sometimes called "cold wallets" because they do not directly connect to Polkadot ecosystem dapps.

{% hint style="info" %}
**Air-gapped signers require mobile phones with a working camera because they make extensive use of QR codes for transaction signing.**
{% endhint %}



Air-gapped signers integrate a two-step functionality that separates key generation and storage from public blockchain data interactions. For this reason, they are considered a lot safer than mobile wallets which store the private keys in the same application used for browsing dapps on the same device.

<figure><img src="../../.gitbook/assets/S_ASParitySignerTransaction.JPG" alt=""><figcaption><p>Overview of the transaction signing UX on <a href="https://www.parity.io/technologies/signer/">Parity-Signer</a>. </p></figcaption></figure>



## How do they work?

There are two methods that you can use to set up your accounts with air-gapped signers. One is to use a single device for both key storage and transaction signing, but with two different applications installed. The other is to use two devices, each with their own separate apps and functionalities.&#x20;

<figure><img src="../../.gitbook/assets/S_ASAirGapVault.JPG" alt=""><figcaption><p><a href="https://airgap.it/">AirGap</a> Vault manages private keys through an offline device.</p></figcaption></figure>



Getting started with an air-gapped signer is a process very similar to onboarding with a mobile wallet, as you can immediately create a new account or import an existing one. However, before you can start to use your accounts on Polkadot networks, you will need to add them via QR code to a dapp that supports air-gapped signers.

<figure><img src="../../.gitbook/assets/S_ASStylo.JPG" alt=""><figcaption><p><a href="https://stylo-app.com/">Stylo</a> provides quick and secure onboarding with a 2-device setup.</p></figcaption></figure>



## Why are they important?

Air-gapped signers are accessible, portable and affordable and still offer strong security features comparable to costly cold storage devices. Additionally, they are flexible enough to allow usage with smartphones that are used everyday or spare/unused smartphones. Nevertheless, you cannot rely on physical devices alone to store your private keys for the long haul, as they can still get stolen, lost, and damaged.

<figure><img src="../../.gitbook/assets/S_ASParitySignerSecurity.JPG" alt=""><figcaption><p><a href="https://paritytech.github.io/parity-signer/about/Security-And-Privacy.html">Device security </a>is essential to air-gapped signers' functionalities.</p></figcaption></figure>



Even though air-gapped signers are designed to keep your private keys offline, they do not scan or screen your smartphone for vulnerabilities prior to running their software. Before re-purposing your smartphone for Polkadot assets storage, you will need to make sure that the operating system on your device is up-to-date, that there is no active SIM card, and that all internet connections are blocked.&#x20;

