## *I*nter*P*lanetary *F*ile *S*ystem
 
### IPFS Offline Access
Data can be read off an IPFS address that was offline whilst the data were created.
* Data are given an address that is characterised by the information, thus an address generated offline will have the same address as if it were online. When the node rejoins the network it can merge changes into the latest Distributed Hash Table (the DHT contains addresses of data) that is distributed across the network.

### Honeypots
If data are stored in a honeypot, i.e. a lot of data available at one address, then access to the private key will allow unimpeded data access. However, data loss is readily mitigated using available functionality e.g.:
1. Smart Contracts
  * Data accessible only when conditions defined in the smart contract are met.
2. Dynamic Addressing
  * Data can be pushed to a new address that is generated automatically so data loss limited to specific address.
3. Underlying Protocols
  * Data can be shared by the kB using smart payments that stream payment from one account to another, allowing the OEM to pay for the data in realtime or the customer to pay for music in realtime.

### Unauthorised Access to Keys
From the **Practical Proof of Kernel Work & Distributed Adaptiveness** (A Resilient & Scalable Blockchain 
Platform for Dynamic Low-Energy Networks) yellow paper:

 *"...cryptographic protocols that manage keys require keys themselves. This circularity is resolved by noting that the most important secrets are actually stored in unencrypted form: these are the keys for which no other keys protect their storage and retrieval. **Risk Management** of systems better be aware of this inescapable fact."*
 
  #### Risk Management 
 It is possible to apply strategies effectively used with pre-existing data access control systems e.g. Active Directory with a server and users. Some approaches can be adapted to be more flexible or secure.
 * Enable 2FA, in effect making the keys useless without the missing component.
 * Programatically set permissions to limit data access (e.g. access time, file type, size, number of times accessed, total bandwidth used)
  
### General Benefits
* **Data Integrity**
Decentralisation secures the data in case of a computer outage or virus. Backups can secure data only until the backup was taken. This may be daily but can be less frequent. An typical automotive engine test cell can generate many 100's of GB of files in a day before it is backed up off-site. Instant, robust and continous transfer of data into the decentralised network would minimise potential data loss.
* **Lower Bandwidth**
Number of network nodes between data source and client is two in the case of IPFS (sender and receiver), reducing total data processed for a transaction compared to http. A smaller bandwidth overhead can increase potential traffic for a given network capacity.
* **Integrated Functionality**
Various protocols and features can be developed on top. One existing example is Publish-Subscribe, which notifies a *subscribed customer* when IPFS data containing a specific message is *published*. This could ensure the end user is always in possession of the most recent data without having to query the sender (IHU firmware upgrades).
