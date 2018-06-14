**General Info**
Enzycoin is a new coin type that's built on litecoin targeting to provide sharding on bitcoin protocol and accounting of transactions in descendant blocks to enable light wallets that doesn't need to store entire chain but rather account based storage.

It is a protocol designed to work with litecoin network that could be taken as a new process  mode of litecoin that could seamlessly work with litecoin that blocks of enzycoin could be stored also inside normal non sharded litecoin's chain but the dedicated blocks for account information might be present only in nodes implementing enzycoin protocol.

The integration structure with other coin chains would be added in time and design is in progress to enable a plugin based architecture to code base to enable seamless integration with other coin types and providing just only sharding service layer to different proof of work/stake methods included by different protocol designs. 


**Targeted feature sets:**

* Sharding feature for light wallets
* Dedicated blocks that stores state information of accumulated transactions to erase the necessity of secured datacenters on blockchain networks 
* Integration with other chains to enable a general sharding service
* Default integration capability with litecoin on which this software is built upon


**Version management:**
The main master branch would hold the very initial litecoin based implementation and feature sets and/or change requests would be managed under new branches. The branch naming rule is:
ft_{short feature name}

**CI management:**
The CI environment as exemplified from litecoin would be travis-ci solution. Details would be added here.

**Notes**
This document is in development, major parts might be missing. To be updated.

