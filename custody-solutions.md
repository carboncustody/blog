![Custody Solutions](https://raw.githubusercontent.com/carboncustody/blog/master/images/custody-solutions/custody-solutions.jpg)

Custody Solutions
=================

If you're an organization or a group looking to 3rd parties for cryptocurrency cold storage, there are two main types of custody solutions that you need to be aware of.

  1. **Private key custodians**: The custodian has full access to the private keys of your cryptocurrencies. You have to trust their systems, people and processes. 
  2. **Hybrid custodians**: You maintain control of your private keys, the custodian uses public keys to create wallets and manage payments.

Private Key Custodians
----------------------

Most private key custodians are using a system called Shamir's Secret Sharing. This is a way of dividing private keys into parts which can be stored on paper.

![Shamirs Secret Sharing](https://raw.githubusercontent.com/carboncustody/blog/master/images/custody-solutions/shamir-secret.png)

The paper fragments can be locked away safely, unlocked, and recombined when a payment needs to be made.


> Consider, for example, the method that the Winklevoss twins use to safeguard their bitcoin stash. It includes holding distributing paper fragments of their private key across multiple storage boxes. _Invostopedia_

The process of creating paper fragments is relatively straightforward. There are tools online that demonstrate the technique.

Recombining the fragments to retrieve the private key is also straightforward. However, making a cryptocurrency payment from the private key is difficult to do safely. The recombining phase is called a signing ceremony.

Specialized software is required to create the payment and sign that payment using the private key fragments. The software for signing the payments needs to run on hardware that is present when all fragments are combined.

When the fragments are combined, safeguards need to be in place to ensure the employees present at the signing ceremony cannot misappropriate the funds.

### How do private key custodians manage payout requests? 

A typical payout scenario would be as follows.

  1. You contact your custody provider's support channel.
  2. They do some kind of ID verification. This might be a video call, for example.
  3. They then contact additional members of your organization for verification.
  4. The custody provider generates the payment transaction. This can be done using standard wallet software provided by each currency.
  5. A set number of employees of the custody provider retrieve the private key fragments from the vaults. i.e. 3 fragments by 3 employees from 3 vaults.
  6. Software running on trusted hardware combines the fragments and signs the payment.
  7. The payment is sent to the network.


### Private key custodians who use multi-signature wallets.

At least one provider, BitGo, is using a mechanism similar to Shamir's secret sharing, but using the multi-signature facilities built into most currencies.

This provides an extra level of security above paper fragments as BitGo is able to do a final check of the payment that was signed by the individuals at the vault.

If the individuals were dishonest or an honest mistake was made the payment would not be fully signed and your funds would stay secured.

### Questions to ask Private Key Custodians

It's important to know how your provider implements procedures around the storage, retrieval and payment signing.

  1. How are our private keys stored?
  2. Which technique is used so that no one individual has access to our funds?
  3. Which software is used to create payments and how can we be sure it is secure?
  4. What procedures are used to identify people from our organization?
  5. How quickly can we make withdraw funds in a fast moving market?

Hybrid Custodians
-----------------

![Hybrid Custody Solutions](https://raw.githubusercontent.com/carboncustody/blog/master/images/custody-solutions/custody-dashboard-screenshot-min.png)

Hybrid custodians use the multi-signature facilities built into most cryptocurrencies so that they don't need access to your private keys.

> Multisignature in cryptocurrencies. Multisignature (often called multisig) is a form of technology used to add additional security for cryptocurrency transactions. 

> Multisignature addresses require another user or users sign a transaction before it can be broadcast onto the blockchain.

Hybrid custodians shift the emphasis of trust from the 3rd party to members of your own organization. 

The custodian takes care of payment creation, adding signatures to a payment and payment broadcasting to the relevant blockchain.

To achieve this the organization designates team members to be trusted with private keys. Private keys can be managed in one of 3 ways.


  * Encrypted client side with the browser. This is similar to the technique used by blockchain.com to manage single user wallets.
    * Advantages. Very easy to manage for less technical users.
    * Disadvantages. Requires the hybrid provider to be very secure.
    
  * Smartphone signing. Private keys are held on each members smartphone. To sign a payment confirming with the phone when requested. 
    * Advantages. Very easy to manage for not so technical users.
    * Disadvantages. Smartphones are more secure than ever, but not totally secure environments.
    
  * Hardware wallets. Similar to signing with a smartphone, but in a much more secure environment. 
    * Advantages. The most secure way to sign multi-signature payments.
    * Disadvantages. A little bit more technical and lost devices are sometimes slow to replace.

 
## Advantages of Hybrid Custodians
 
 * Funds cannot be held or delayed. As your organization holds the private keys, wallets can be reconstructed independently of the 3rd party custodian. It's not possible for the custodian to hold funds for political and market manipulation.
 
 * As the custodian is only managing public keys, you're less reliant on their systems and procedures. 
 
 * Funds can be moved quickly. Hybrid solutions don't require a signing ceremony from the custody provider. Your trusted employees can remotely sign payments on your timescales.
 
Conclusion
----------
 
The trade-off in choosing a custody solution is whether you want to fully trust a 3rd party with your private keys and therefore your funds, or if you want to maintain control.
 
 
 
 
