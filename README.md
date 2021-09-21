# blockchain-developer-bootcamp-final-project
Final Project will be a smart contract that allows for shared custody of a digital asset.
The assest itself is intended to be non-fungible like a house, a boat, productive machinery, farmland, ect.
But ownsership can be fractional such as with shares in a corporation. This project is imagined to embody 
the principles of cooperativism within a blockchain framework.

In this example we will focus on the application of fractional ownership to home ownership.
Ownership of the house is tokenized. The contract should include the identity of the participants, the payment terms, 
and the amount of shares each participant is entitled to. As people living in the house make monthly payments 
like in a mortgage, they recive equity little by little in the form of fractional equity shares. If each tenant stays
long enough they will own their entitled share of the property out right. If such as person chooses to leave the property 
then they can sell their share to someone else who wants to move in. 

The contract will have an 'attractor' final state defined by the ratio/composition of fractional ownership decided on by the community.
It will also have an initial state, and a current state that will constantly change until reaching the attractor or something else changes.

The identities of the members, their stake in the community, will all have to be set initially.
The workflow should allow for situations where the members all form an LLC to purchase the property or if a single member or couple holds
a traditional mortgage at first.


If there is more time I would like to add a feature for community financing. So home buyers can leverage their personal network of 
friends and family in perhaps a consortium blockchain to help them through a form of crowd sourced home financing. 

Another exciting possibility would be to have the option to leverage decentralized finance for the same purpose. From a personal perspective I would
prefer to prioritize aqcuring debt from my personal network before using public DeFi, but it could certainly help close the gap.
