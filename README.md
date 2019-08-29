# Enable cryptocurrency in FUNDING.yml

This repository's purpose is to gather the interest that the community has in adding cryptocurrencies as an officially supported funding platform for GitHub Sponsors. Star this repo if you'd like to see cryptocurrencies added as official options in the `FUNDING.yml` file for GitHub Sponsors. We can show the social proof to GitHub and hopefully they will respond positively.

## Proposal

This proposal focuses on the two most popular cryptocurrencies, Bitcoin and Ethereum. More could come, but adding these two would be a great start. The proposal is as follows:

### Syntax

Add `bitcoin` and `ethereum` fields to the `FUNDING.yml` file for GitHub Sponsors.

In addition to the platforms already available in the `FUNDING.yml` file, the following would be added:

| Platform | Syntax |
| --- | --- |
| Bitcoin | `bitcoin: ADDRESS` |
| Ethereum | `ethereum: ADDRESS \| NAME` |

The `NAME` for the `ethereum` field would be an [`ENS`](https://ens.domains/) name that resolves to the correct address. By simply allowing an Ethereum address, any cryptocurrency built on top of the Ethereum network would also automatically be supported. Stablecoins pegged to `USD` like `DAI` and `USDC` may be of particular benefit to open source project maintainers, as they would essentially be receiving `USD`.

### Presentation

When users click on the `Sponsor` button of a repository, hyperlinks to the platforms found in the `FUNDING.yml` file are automatically shown. Since Bitcoin and Ethereum are decentralized networks, there is no single official web presence to send a user to when clicking on an address. There are a few options for generating a hyperlink:

* No hyperlink could be generated. The user would just be presented with the plain text address
* A hyperlink to a popular block explorer could be added
  * Here is an example Bitcoin hyperlink that could be presented to the user: [bc1qar0srrr7xfkvy5l643lydnw9re59gtzzwf5mdq](https://btc.com/bc1qar0srrr7xfkvy5l643lydnw9re59gtzzwf5mdq)
  * Here is an example Ethereum hyperlink that could be presented to the user: [0xc9bc72fe58c5FAcc478514313FbA09d13ee3742b](https://etherscan.io/address/0xc9bc72fe58c5FAcc478514313FbA09d13ee3742b) 
* A hyperlink to a general explanatory page for Bitcoin or Ethereum could be presented, showing the user common tools and methods for donating Bitcoin or Ethereum, specific to the address linked to

## Result

Bitcoin and Ethereum would have a native home with GitHub Sponsors. This would help raise awareness of cryptocurrency as a viable way to fund open source projects. Donations could come in through individual contributors clicking on the `Sponsor` button and manually paying out, or other projects could parse out the addresses and provide automated solutions for donating cryptocurrency. Donaters to projects would have transparent access to allow incoming and outgoing transactions of an address, since Bitcoin and Ethereum both expose intimate details of most transactions.
