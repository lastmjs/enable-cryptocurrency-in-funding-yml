# Enable cryptocurrency in FUNDING.yml

This repository's purpose is to gather the interest that the community has in adding cryptocurrencies as a funding platform for GitHub Sponsors. Star this repo if you'd like to see cryptocurrencies added as official options to the FUNDING.yml file for GitHub Sponsors. We can show the social proof to GitHub and hopefully they will respond positively.

## Proposal

This proposal focuses on the two most popular cryptocurrencies, Bitcoin and Ethereum. More could come, but adding these two would be a great start. The proposal is as follows:

Add `bitcoin` and `ethereum` fields to the `FUNDING.yml` file for GitHub Sponsors.

In addition to the platforms already available in the `FUNDING.yml` file, the following would be added:

| Platform | Syntax |
| --- | --- |
| Bitcoin | `bitcoin: ADDRESS` |
| Ethereum | `ethereum: ADDRESS | NAME` |

The `NAME` for the `ethereum` field would be an [`ENS`](https://ens.domains/) name that resolves to the correct address.

## Result

Bitcoin and Ethereum would have a native home with GitHub Sponsors. This would help raise awareness of cryptocurrency as a viable way to fund open source projects. Donations could come in through individual contributors clicking on the `Sponsor` button and manually paying out, or other projects could parse out the addresses and provide automated solutions for donating cryptocurrency.
