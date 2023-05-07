MANTLE TESTNET DEPLOYED ADDRESS = "0xA8785B7219610F99Ac974DB85e55C87e1aab34BA"
SPHERON NETWORK DEPLOYED LINK = "https://bafybeiahon4y3fqidlddailqiwky2sgecroia4x35x3bgwj7o7swlg67ei.ipfs.sphn.link/x.html"

## Inspiration
Trail is a web tool which can be used to make transactions in BIT safely. People need to send funds to others and end up sending them to the wrong address because they didn't check the receiver address. Hence, it's important to have an escrow service as a tool which can be used to make day to day fund transfers on the mantle network

## What it does
Trail let's you send funds safely. It keeps the sent funds stored in a smart contract, and waits for the receiver to claim the funds. If, in case funds were transferred to a wrong account, you can revert the transaction and get their funds back. The receiver can claim the funds and smart contract will release the funds to the receiver.

## How we built it
We built it using solidity, html, css, javascript, browserify and web3js

## Challenges we ran into
It was difficult to figure out the exact flow of the escrow service, and how can we make it user friendly. Thankfully, we figured it all out as time progressed.

## Accomplishments that we're proud of
We are proud of the fact that our website is not just a proof of concept but something a day to day mantle network user can use to make BIT transactions safely.

## What we learned
We learned a lot about the mantle network and how to deploy websites on sphreron

## What's next for Trail 
We want to extend this functionality to app users, and develop an app for this service.
