# Realistic-Solution-to-Supply-Chain

Objective

The Project Intent and motive is to apply the blockchain concept in the Supply Chain industry. In a way that creates transparency in the authenticity of the original product manufacturer creating the trusted environment cleaning the fake / pirated products from the market. We are going to implement a distributed solution in which from the manufacturer of the product to all the suppliers in the chain will be recorded in the blockchain creating an open market for end-user to verify the legitimacy of the product. Right now for testing purpose, all the actions like add_product, add_product_state are open without any authentication of manufacturer and supplier. Our next phase is to implement login & registraction system so that only regsitered manufacturer & supplier can add the information to the blockchain.

Problems faced by supply chain & logistics?

Previously, supply chains were relatively easy and simple because commerce was local, but now it’s done globally, which makes it incredibly complex.Due to globalization, payments between the involved parties (vendors, suppliers and customers) might take several days to get processed while contracts being reviewed by bankers and lawyers comes with extra cost and delays. Moreover, cargo passes through several geographical locations national/international before arriving at its destination, it often becomes difficult to trace where the product actually came from, as the documents can be lost or forged.

Currently, it’s very difficult for customers/buyers to truly know the value and origin of products because there is lack of transparency in the present supply chain system. Also it’s extremely difficult to investigate if there is happening of any illegal or unethical practices in the system.

Due to high complexity and lack of transparency in the current supply chain, businessmen’s are anxious to explore the possibilities of blockchain technology to transform the supply chain and logistics industry.

Solution Approach

The logistics & supply chain industry has been one of the primary fields for blockchain adoption these days. Various big giants companies like- Walmart, British Airways, Maersk, FedEx and Visa etc. are keen to get on the bandwagon of the blockchain are looking into the implementation of blockchain technology to ease the process of delivery and make the supply chain more efficient and traceable. This transforming technology is a useful tool for tamper-proof,product tracing for any supply, from tomatoes to diamonds.

From order tracking to dispute resolution, blockchain has the answer to every problem that has been plaguing the logistics industry for decades.

Solution

We have developed the implementation of supply chain process in Etherium Smart contract. Which has following options: - Manufacturer - Can add a Product - Supplier - Can add state / position to given product - Customer - Can see the product details by quering the blockchain

Technology Stack Used

Ganache - for local Personal Etherium Blockchain testing - Remix - for writing, compiling and deploying our smart contract - MetaMask - for providing the access of local blockchain hosted with Ganache to browser based Remix platform - Frontend - for user interaction, made in HTML, CSS, JavaScript

Following are the ways in which blockchain can help

Trackability & Transparency Adopting blockchain in supply chain could boost trust,enhance transparency, and predictability by enabling users to track where a shipment/ order is at any given time.

Automation Usage of smart contracts will enable companies to automate their purchasing process, which leads to cutting costs and saving time. Smart contract will also improve the transaction flow and security in the supply chain.

Accessibility Using blockchain, sellers can store their product origin, place of storage, authenticity, product certificates and record, etc. on a single ledger. All of the important information being in one place will make accessibility of data much more easier, which not only create more transparency in the supply chain but also helps in decreasing the amount of frauds and cargo theft that occurs.

Security Since a blockchain is an immutable distributed ledger, changes in ownership and possession of goods at any point could be entered into the ledger permanently and instantaneously.As the blockchain technology is cryptographically protected and is decentralized, shipping, possession and ownership of data could be better protected from tampering or hacks.

Quick Payments Implementing blockchain technology to the payment system could help in reducing friction in commercial financing, thus eliminating the trade disputes.

Saves Cost and Time

Transport providers will be able to post information about availability of storing capacity and routes, which will reduce transport costs and time.Consumers can know the origin of the products, manufacturer, date, time, etc, instantly and will benefit from reduced costs and shipping times.

Please refer to the powerpoint presentation attached for details along with pictorical representation and detailing information etc...

## Solution Detailing Information
We have developed the implementation of supply chain process in Etherium Smart contract. Which has following options:
- Manufacturer - Can add a Product
- Supplier - Can add state / position to given product
- Customer - Can see the product details by quering the blockchain

## Technologies or Tools used
- Ganache - for local Personal Etherium Blockchain testing
- Remix - http://remix.ethereum.org/ for writing, compiling and deploying our smart contract
- MetaMask - for providing the access of local blockchain hosted with Ganache to browser based Remix platform
- Frontend - for user interaction, made in HTML, CSS, JavaScript

## Next Phase
Right now for testing purpose, all the actions like add_product, add_product_state are open without any authentication of manufacturer and supplier. Our next phase is to implement login & registraction system so that only regsitered manufacturer & supplier can add the information to the blockchain.

## Future Plan
There is one roadmap we have seen on one Medium article by Zebi,

![Image of SupplyChain & Logistics](https://miro.medium.com/max/2640/0*ESvVyCvkJUR2yZ9s)
###### Image Credit to [@Zebidata]( https://medium.com/@Zebidata ) ( [Blog Link]( https://medium.com/@Zebidata/blockchain-in-supply-chain-logistics-6cdfe36ffe88 ) )

By studying this diagram we have built a json representation of blockchain for each transaction in above process.
Like for example, the transaction between Manufacturer & Supplier will consists of following data:
( This transaction generally consists of one type of products from manufacturers to supplier )
- manufacturer detail
- supplier detail

- batch_id
- batch_product_number_from
- batch_product_number_to
- product_count
- product details
- menufecturing cost
- sell price
- certificate of origin
- weight

- dispatch from location
- dispatch to location
- batch dispatch date
- batch received date

The transaction between Supplier & Logistics will consists of following data:
( This transaction generally consists of many type of products collected from many manufacturers to be shipped to one location per transaction )
- supplier detail
- logistics detail

- order_id
- detail of one type of products collected from many manufacturers combined togather
- purchased cost from manufacturer
- sell price
- weight

- dispatch from location
- dispatch to location
- batch dispatch date
- batch received date

If we move further, logistics will arrange the orders of many suppliers and fit them in containers to be shipped through Shipping line. Which will then be received at the receiver port and further distributed to local supplier and end user.
But the data generated by this is detailed and can be tracked at each stage of the supply chain. This system can take some time to build but is Robust on which supplychain and import export businesses can join into.

## Frontend
Here are some of the images of the project frontend.

![]( https://github.com/Apollo9999/Realistic-Solution-to-Supply-Chain/blob/main/images/1.png )
![]( https://github.com/Apollo9999/Realistic-Solution-to-Supply-Chain/blob/main/images/2.png )
![]( https://github.com/Apollo9999/Realistic-Solution-to-Supply-Chain/blob/main/images/3.png )
![]( https://github.com/Apollo9999/Realistic-Solution-to-Supply-Chain/blob/main/images/4.png )
![]( https://github.com/Apollo9999/Realistic-Solution-to-Supply-Chain/blob/main/images/5.png)
![]( https://github.com/Apollo9999/Realistic-Solution-to-Supply-Chain/blob/main/images/6.png )

