# Multisigwallet-smart-contract
Solidity code for MultisigWallet

![Copy-of-Multisig-wallet-775x500](https://user-images.githubusercontent.com/58028401/128411723-8dae5695-a06b-48a0-9bae-4c2dd0517adb.png)


# How does a multisignature crypto wallet work?
Imagine a bank vault that requires more than one key to open: That’s a little how multisignature cryptocurrency wallets work (and why multisignature wallets are typically called vaults).


You can choose how many keys are allowed to open the vault as well as the minimum number of keys needed to unlock it (e.g., you could have a 2-of-3 multisig where two out of three assigned private keys are needed, 3-of-5, 5-of-7, etc.).


Justin, Vittie and Craig each hold one of the three keys needed to unlock the multisig wallet.
It works like this: Justin, Vittie and Craig set up a multisignature crypto wallet where each holds one key and two of the three keys must be present to send a transaction. To make a payment, Justin would create a transaction and sign it with his key; he would then send this transaction to Vittie, who would sign it with her key. From here, Vittie can either send it back to Justin to finalize the transaction or send it to Craig for him to sign, too (though this last step is not necessary, considering only two of the three keys are needed to unlock the wallet).

Typically, hardware wallets (namely, Trezor, Coldcard and Ledger) are the go-to option for using a multisig setup because they are the safest way to store a private key. Once these wallets are combined into a multisig setup, they create an entirely new multisignature address that is independent of each individual hardware wallet.


# When would someone use a multisignature crypto wallet?
For retail investors, multisignature wallets are commonly used to secure bitcoin (BTC, +2.86%), but you can also use them for ether (ETH, +3.97%) and other cryptocurrencies.

Most notably, crypto exchanges, brokers/OTCs, investment funds and other crypto companies use multisignature storage to secure their cold storage funds. Exchanges, brokers and the like distribute admin keys for their funds in order to distribute the risk; if hackers want access to their reserves, they’re going to need several keys to do so. Similarly, multisig ensures no one person in the firm is able to unilaterally withdraw funds from the account. The more signatures you need to execute a transaction, the more distributed the decision-making process can be.

Other specific use cases may involve setting up a shared account among family members (for, e.g., a trust or estate) or an escrow account (for, e.g., a bet or a sale of property). Relatively speaking, multisig is still a niche custody practice among cryptocurrency holders. Still, that doesn’t mean your typical crypto user doesn’t use it to custody their coins.
