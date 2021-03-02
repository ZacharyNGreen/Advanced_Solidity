# Advanced_Solidity

My company has created a new token, Puppercoin in otder to help fund network development and the tokens are being offered via a crowdsale. The crowd sale is ran utilizing the PupperCoin.sol and PupperCoinCrowdsale.sol solidity files. 

The PupperCoin.sol file is utilized to create the tokean and the PupperCoinCrowdsale.sol file is utilized to administer the crowdsale. In order to run the crowdsale, the files should both be uploaded to Remix and the the PupperCoinCrowdsale should be run, it will reference the PupperCoin file. In order to successfully administer the crowdsale, users will need to pass a wallet address (from Ganache) to the PupperCoinCrowdsale and assing it to the toke_sale_address variable. The crowdsale file leverages the openzeppelin library to complete the crowdsale.

After users pass their wallet address to the crowdsale file, Puppercoin should appear in the user's metamask account. 