# NFTRecords

Faculty blockchain project.

Application that tracks information about nft collections. The app will have an UI to show users for each collection a list of the "whales". Also the app will have an UI to show the ownership chain of a specific NFT. Also we will think for more features to be added for the users to incentivize the use of the app.

## Laboratory project requirements

- Authentication using one of the presented methods
- A table with the collections that have been added to the platform
- “Whale View” - See the top holders of a specific collection
  - Ideally, this view should be real-time
  - Use web3 subscribe (with Infura)
  - [https://www.covalenthq.com/platform/#/](https://www.covalenthq.com/platform/#/)
- “NFT Ownership Tracing” - See the entire ownership chain of a specific NFT of a collection

Suggestions:

- use Go, Node.js (w/ express), Java, Ruby, Python or whatever backend language you’re comfortable with
- use Next.js, Nuxt or any front-end framework
  - eg. mui (Material UI) for the component side of things
  - TailwindCSS should help you with styling (similar to Bootstrap, but superior, in my opinion)
- Postgres, Mongo or, if you’re feeling yourself ([https://rethinkdb.com/](https://rethinkdb.com/api/javascript/))

Optional

- If an API Key is obtained, you should implement a storing mechanism that receives (ETH network mainnet)
  - Item Listed event
  - Item Sold event
  - Item Transferred event
  - Item Canceled event

## TODO

... add later the roadmap of the project
