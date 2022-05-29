# Crpytokuneho

A crypto exchange for exchanging satoshis (BitcoinLN - using [lightning](https://lightning.network/)) to fiat and vice versa. 

## Idea

[PWA](https://web.dev/progressive-web-apps/) to place bids and connect to the bidder via telegram (PWA).

## Database

#### List of Fiat Wallets

 - List of fiat wallets that is identified to a person. 

#### List of Satoshi Wallets

 - Used to identify type of wallet (to be used for statistical data analysis). 

#### Bids

   - Amount Satoshis for exchange
   - Currency for exchange (Currency + Amount)

#### Telegram Usernames

  - stored to match bids to telegram seller/buyer

Might need the following to encourage trust:

#### Verified List

  - People who published their identification cards as part of KYC.

#### Verifications ??

  - Used to store id's and selfies of people who verified themselves.
 
## Dispute Resolution

What if someone sends satoshis and the other party does not pay the fiat / vice versa? Ideally there would be a [lightning-based escrow system](https://lightningescrow.io/).  

## Alternatives

Alternative solution right now is just to use [t.me/bitcoinp2pmarketplace](https://t.me/bitcoinp2pmarketplace). 

Or Binance's p2p system (KYC required) [tutorial here](https://www.binance.com/en/blog/p2p/intro-to-peertopeer-trading-what-is-p2p-trading-and-how-does-a-local-bitcoin-exchange-work-421499824684901839).

[Other best bitcoin peer to peer websites](https://thinkmaverick.com/7-best-peer-to-peer-p2p-bitcoin-exchanges-private-secure-low-fees/)
