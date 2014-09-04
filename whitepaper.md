== Overview ==

In today's world, web applications represent the majority of software projects. These applications need a simple way to connect to Bitcoin and other cryptocurrencies. Over burdened developers do not have the time to learn new languages, or worse, convert to an entirely new development paradigm. To maximize their efforts developers should be able to use the tools and technologies they already know and understand.  These developers aren't looking for a new Internet, but they do want to start moving toward decentralized applications so as to take advantage of the new technologies. 

The Rubric Service Network (RSN) provides developers access to a variety of cryptocurrencies in a consistent manner. This is accomplished using open source tools and protocols. By leveraging existing tools we save significant time in development while creating an easier to use and maintain network for users and developers. Using existing standards also means applications developers are exposed to an interface which they are already familiar. This will enable the large number of existing web applications to quickly and easily implement innovative new applications that utilize cryptocurrencies and blockchains.

The RSN is designed to operate as a [https://en.bitcoin.it/wiki/Distributed_Autonomous_Community_/_Decentralized_Application Decentralized Autonomous Community]. Once initial development is completed, the network will generate fees and circulate those fees to the ones providing the infrastructure and development to ensure its continuation. The goal of the RSN is to incentivize running a Rubric as well as funding development and maintenance of the network. Without layers of management and marketing expenses, the RSN will be able to provide these services at a rate conventional businesses cannot provide. In addition, as it's decentralized, developers do not have to worry about a relying upon a single entity to provide the service.

== The Problem ==
There are many issues faced by web developers looking to incorporate Bitcoin and other cryptocurrencies into their application. These issues range from minor annoyances to major roadblocks. We are building a comprehensive solution to address all of the current issues while planning for new problems as they emerge. Here are some of the essential problems in the current cryptocurrency environment that the RSN seeks to solve:

# Existing blockchains don't allow storing sufficient data with the transaction.
#:Bitcoin allows a meager 40 bytes and Datacoin allows 128 kilobytes. 
#:There are solutions that use a blockchain as part of a storage solution for large files. However, developers do not get the full application framework and access to other cryptocurrencies.
# Storing large objects over time is not free.
#:Storage fees have to be paid up-front or as recurring payments in order to maintain the storage. 
#:Up front payments can be difficult if you don't know how long you need to store the file. There's also the possibility that the rubrics would spend all the advance funds and not be around to support long-term storage contracts.
#:Recurring billing is a hassle for application developers and the network to maintain. It does not support the "store it and forget about it" workflow desired.
# Allowing the execution of arbitrary scripts is inherently dangerous as they allow for malicious code that can harm transactions, files, or the rubric itself.
#:Some solutions have created their own execution environment and limited scripting language to address this. That forces application developers to adopt a whole new paradigm rather than their native environment. This creates system inefficiencies and increases the potential for errors of ignorance.

== The Solution ==

There are various products and offerings that can solve parts of these problems. The ideal solution would be able to solve all of them while maintaining flexibility to solve emerging problems as they arise, thus minimizing business risks while enhancing developer productivity.

As such, the ideal solution has the following properties:

* Blockchain agnostic. It should work with all other blockchains and cryptocurrencies while requiring none of them to function. The more systems a solution is dependent upon, the more likely it is for one of them to cause problems.

* Based on proven and familiar Open Source technologies. It is unrealistic for businesses to adopt entirely new paradigms and force their developers to learn new technology in the hope that their customers will follow them to this new market. If developers can integrate blockchain technologies into their existing applications, both sides win. The developers gain powerful new tools and the cryptocurrencies gain access to a huge market. 

* Sufficiently self-funded. Measures should be in place to ensure the continuation of the network. This includes making sure there are resources for ongoing development as well as a guaranteeing long-term storage commitments can and will be honored.

* Future-proof. It should support a normal software development life-cycle. The system should never have to depend upon all users upgrading on the same day.

* Secure, both today and tomorrow. The system should easily support integration of new cryptographic algorithms as they are developed.

== Assumptions ==

* Bitcoin is sufficient for general consumer transactions, and should remain the sole cryptocurrency used for that purpose. Multiple currencies in the consumer transaction space would confuse consumers.

* Blockchains provide an effective means maintaining an immutable decentralized ledger. There are many needs for ledgers outside of consumer transactions.

* It is possible to use blockchain technology without introducing another coin in the consumer space.

== Introduction ==

The Rubric Services empower a new generation of programmable smart wallets to create and manage transactions across multiple cryptocurrencies. The rubrics will provide a number of decentralized, trustless services. Combined, these services provide a consistent and extensible means of supporting contracts and advanced applications.

The design and architecture of our network has been heavily influenced by our team's vast experience in Internet and web development. Our goal was to create a bridge between current web applications and the new era of decentralized applications which utilize the principles of cryptocurrencies, namely the Bitcoin protocol, itself. Our focus has been, and will remain, the creation of an extremely simple method for web developers to integrate complex (or simple) cryptocurrency transactions into their existing web applications. Like any good bridge, the network also makes it easy for DApps connected to these cryptocurrencies to access a thriving web development community.

Primary Use Cases
* Store data related to a bitcoin transaction.
* Create a timestamped recording of a file, unrelated to Bitcoin.
* Execute code stored in the object to perform conditional signing.
* Store and access a Bitlov Pocket.

The majority of rubricoin transactions will be used to register and store object on the network. They can also be used to transfer rubricoin value from one address to another.

The [[Rubric Network]] is being developed as a [[DApp]] to provide [http://en.wikipedia.org/wiki/Platform_as_a_service Platform as a Service (PaaS)] products based on blockchain and [http://en.wikipedia.org/wiki/Distributed_hash_table Distributed hash table (DHT)] technology. It will provide developers with a consistent interface to create complex transactions using one or more crypto currencies.

Bitlov.com is the front facing dashboard and UI for both novice and advanced users who wish to take advantage of a streamlined interface to make any possible financial scenario a reality.

== Rubrics ==

Rubrics are computers that provide one or more services for the Rubric Service network. The Rubric's supported services and capacities are listed in the Rubric Registration Object. Its expected that some rubrics will provide more of one type of service than another, this lowers the barriers to participating in the RSN. Rubrics are compensated based on the amount of support they provide the network.

Rubric Services:

* Confirm Transactions
* Host the Rubricoin Blockchain
* Store Rubric Objects
* Provides the Rubric Compute Container (RCC)
* Executes Rubric Scripts in the RCC
* Provides Rubric Web Services

=== Trust Modes ===

Rubrics can be accessed in a variety of trust modes that all play different but equally important parts in the Rubric Network. The Rubric Client Software may interpret the results differently depending upon the level of trust assigned to a rubric. A single rubric server may provide services in all of these modes to different rubric clients. The levels from least to most secure are:
* Trustless
* Trusted
* Secure

==== Trustless Rubric ====

A trustless rubric is any rubric the client has no relation to or knowledge of. They can perform actions that don't require the client putting any trust in the rubric owner. Trustless rubrics are used by all parties in the RSN as well as the RSN itself to perform maintenance tasks.

Trustless Rubric Actions:

* Store rubric objects
* Provide inexpensive compute power
* Confirm results of trusted or secure rubrics
* Provide results for use in creating a consensus with other trustless rubrics
* Auditing other rubrics for the RSN
* Process rubricoin transactions

==== Trusted Rubric ====

Trusted rubrics are rubrics that a user believes to be trustworthy. Trusted rubrics may be used to break ties between trustless rubrics or raise flags when the result of the trusted rubric varies from the consensus of the trustless rubrics. These Rubrics might be run by business, organizations or clubs. Most consumers will want to configure their rubric client with the address of one or more trusted rubrics to perform actions with the same level of security as modern web applications. 

Trusted Rubric Actions:

* Provide rubric clients the address of a random trustless rubric. 
* Perform actions the rubric client is unable to perform
* Processing rubricoin transactions needing a higher level of security

==== Secure Rubric ====

A secure rubric is one that a user has complete control of. A company may create a secure rubric to more tightly integrate with their application. A secure rubric can also access files and services unavailable to public rubrics. An organization may run a secure rubric as a service to its members, although the members would probably consider it a trusted rubric.

Secure Rubric Actions:

* Process pocket transactions
* Integrate with ecommerce sites

===  Rubric Client ===
Rubric clients are run in web browsers and devices. They understand the RSN API and protocols and can locally execute Rubric Scripts. They don't store Rubric Objects or process service requests from other Rubrics.

== Rubricoin ==

Rubricoins are the medium of exchange within the Rubric Service network. It is important that they have value long-term so that people are motivated to run rubrics and support the long-term storage contracts.  

To ensure that:
# All fees to use the Rubric Service Network (RSN) must be paid in Rubricoin. 
# Rubric owners will only be be rewarded in Rubricoin.

The goal of rubricoin distribution is to take the incoming rubric fees and distribute them in a fair manner. The unspent coins in a transaction are given to the RSN for distribution. The network will automatically tune the fees involved and the outgoing payments to ensure its continuation.

There are a couple of constraints to the solution:

# The fees paid for storage must be distributed over the life of the storage contract.
# The Rubric system must not hold funds. If funds are accumulated anywhere there is the potential for theft or loss. Storing the funds also incurs the overhead of an accounting system of some sort.

=== Encumbered Coins ===

Encumbered Rubricoins are coins have a limitation on how they can be spent. These are important qualities unique to Rubricoin and are part of what makes it so powerful. They are similar to bitcoin transaction scripts but provide far more flexibility in defining the rules the spend transaction must follow. Encumbered rubricoin can even enforce their rules upon future generations of transactions.

Encumbrances:

* Maturation date and rules
* Possible output addresses
* Amounts of the outputs
* Unspent change address
* Minimum or maximum network fees
* Encumbrances on future coins

Encumbrances are written in JavaScript and stored in the Rubric Object. JavaScript provides a powerful programming language that web developers are very familiar with. By storing the script in the object we have space for even the the most complex encumbrances. The rubrics check the coins encumbrances when validating a transaction. If the transaction does not conform to the encumbrances, the transaction will not be accepted by the RSN. 

== Rubric Blockchain ==

The Rubric Blockchain is used to record the Rubricoin transactions. The Rubricoin Blockchain is similar to the Bitcoin blockchain. The OP_RETURN is used to store the hash of a Rubric Object if one is attached to the transaction request.

Our intent is to use a format as similar in possible to the Bitcoin block chain. 

== Rubricoin Transaction ==

At the blockchain level the Rubricoin transactions are identical to Bitcoin transactions. The process for transmitting and confirming the transactions is vastly different.

* Transactions submitted via web services
* Transactions are validated against potentially complex scripts
* The rubricoin may be worth only part of its face value

== Rubric Objects ==

Rubric Objects store the data related to the transaction as well as related meta data in a single file. The JWE format is borrowed from the JavaScript Object Signing and Encryption ([https://datatracker.ietf.org/wg/jose/documents/ JOSE]) IETF Working Group. All elements in the standard are supported, though only part of them are actively used by the Rubric Services. This document covers the the specific uses as implemented in the RSN. Developers should be familiar with the [[https://datatracker.ietf.org/doc/draft-ietf-jose-json-web-encryption/ JWE format] full specification].

=== Headers ===

The Rubric Services support are only concerned with a few of the headers. It is only concerned with public protected headers, though any unprotected headers provided will of course be included in the Rubric Object file hash. The use of private headers is discouraged, The additional authenticated data elements are better used for private extensions.

==== Public Protected Headers ====

Only public protected headers are used by the Rubric Services, this minimizes the complexity and chance of integration errors with other JWE applications.

===== Encryption Algorithm =====

The "alg" (algorithm) Header Parameter identifies the cryptographic algorithm used to encrypt the data. The default used by the RSN is HMAC using SHA-256 (HS256) though other standard [https://datatracker.ietf.org/doc/draft-ietf-jose-json-web-algorithms/?include_text=1 web encryption algorithms] are supported. 

If the algorithm is defined as "none", then the ciphertext is expected to contain unencrypted data. 

===== Type =====

The "typ" (type) Header Parameter is used to declare the MIME Media Type of this complete Rubric Service object.

Valid Rubric Object types:

* JOSE+JSON - used for the full uncompressed JWE representation.
* JWE - used for the compressed representation of the JWE.

===== Content Type =====

The "cty" (content type) Header Parameter is used to declare the MIME Media Type of the encrypted data. This can be any valid [http://www.iana.org/assignments/media-types/media-types.xhtml mime file type].

=== Ciphertext ===

This is the data that is being stored. It may or may not be encrypted, its' encryption algorithm and mime type will be stored in the public protected headers. In the case of it being a Rubric Registration Object the ciphertext would actual be a cleartext object defining the Rubric.

=== Additional Authenticated Data (AAD) ===

The meta data required about the object and transaction required by the Rubric Service Network.

==== Storage ====
The storage attribute array provides information about what the RSN has agreed to provide for this object. Multiple Rubrics must agree to these conditions before the transaction is accepted.

==== Storage Expiration ====

The storage expiration is an [http://www.iso.org/iso/home/standards/iso8601.htm ISO formatted] [http://en.wikipedia.org/wiki/Coordinated_Universal_Time UTC] date and time. After that time the file no longer needs to be stored by the RSN.

Storage may be terminated earlier by transferring the remaining storage value to a new transaction and object. The object itself cannot be updated without breaking the hash. To ensure the files are deleted the RSN contacts each rubric storing the file with a delete request. Rubrics that were unable to receive the delete request will eventually delete the file as part of its local auditing processes. It will check the Rubricoin Blockchain for a storage transfer transactions on all its stored files and delete any where the supporting fees have been transferred away.

During the transaction verification process the storage expiration is validated. There must be sufficient unspent funds to cover the storage costs, if not the transaction will be rejected by the network.

==== Storage Copies ====

Defines the number of copies the RSN has agreed to store until the storage expiration is reached. This number must be at least three. The actual numbers of copies stored may dip below this as nodes go offline, the system will detect this and create additional copies as needed.

==== Rubric Script ====

The Rubric Script contains the encumbrance rules, is run as part of the transaction verification process as well as when the rubricoin is spent.

==== Access Limits ====

The Access Limits define who can read the Rubric Object and how it can be accessed. These are meant to enforce workflow rules and reduce potential network traffic. Anyone in control of a Rubric can fetch any object on the network so this isn't meant to secure the contents of the object.

==== Rubric Object Type ====

This is the object meta type of the data as seen by the rubrics. It is not related to the mime type. There is a small number of supported rubric object types. The Rubric Scripts for all object types are always executed during transactions.

===== Standard Transaction Object (STO) =====

This is the most common type, it means the object has no special significance to the RSN. 

===== Replacement Object (REP) =====

This is used to signify a transfer of storage funds from one object to another. It must be a valid transaction that spends from a transaction with remaining storage funds. If no storage funds are available, or the funds are below the minimum storage limit a replacement transaction will not be accepted.

===== Pocket =====

These are the basis for the next generation of smart transactions. A pocket is a Rubric Object that contains contains private keys for one or more cryptocurrencies. It also contains list of related transactions and rules on how the keys and transactions can be accessed. It further contains scripts that can be run to create transactions automatically.

===== Rubric Registration Object (RRO) =====

This object type is used to register a rubric in the RSN. It is stored in cleartext since the information needs to be freely available. It defines a number of things about the rubric.

* The hostname within the rubric network, availability is verified during the transaction verification.
* The IP address of the rubric, this will be checked for a running Rubric during the transaction verification.
* The array of services the rubric offers along with its capacity. The services are checked during the verification and the capacity is believed to be true until evidence to the contrary is presented during audits. These are used to determine the Rubric Registration Fee for the new Rubric.

===== Supporting Object =====

A supporting object is one that purports to provide data related to a state of a previous object.

==== User Object Type ====

This is the object meta type assigned by the object creator. This is an optional value that can be stored in cleartext in an object to make it easier for rubric client applications to provide early processing, before the contained data is decrypted. This allows an application easily store various types of data in the RSN.

== Rubric Scripts ==

Rubric Scripts are written in JavaScript and run by Rubrics or Rubric Clients. These scripts are always run when an object is accessed by a Rubric. They are stored in cleartext inside the "script" element within the objects Additional Authenticated Data.

Script Capabilities:

* Access nested Rubric Objects
* Access objects stored anywhere on the RSN
* Create transactions across multiple coins
* Create new Rubric Objects and transactions
* Access web services and perform defined actions

== Rubric Compute Container (RCC) ==

The Rubric Compute Container provides a secure virtual container for the execution of Rubric Scripts. A Rubric Object is passed to the RCC, which then executes the scripts within it. Those scripts may access other Rubric Objects either nested in the object or stored on the RSN. The scripts within those objects can load other Rubric Objects. The amount of nesting is limited by the runtime limits of the original script. If the nested calls don't return in time the original object won't be able to access the result. Even after the original RCC has timed out child object spawned by it may continue to access or create new objects.

The RCC Process:

# A Rubric Object is passed into Rubric Docker application.
# The object is processed by the Node.js Rubric module.
# The object's Rubric Script is run.
# Either the script finishes and exits or the container's runtime limit is reached and the process dies.

== Rubric Web Services ==

The Rubric Web Services expose all of the power of the Rubrics through a simple RESTful API. This means that existing web applications already have the tools to integrate Rubric Services.

=== API ===

/transaction
POST Creates transaction
GET provides web form to create transaction
Accepts Rubric Object as attachment

/transaction/transaction_id
GET provides information on the transaction
POST creates a replacement transaction. Unused Rubric Fees get passed to the new transaction.

/object/object_id
GET returns full object as human readable JSON

/object/object_id/compressed
GET returns full object as compressed JSON

/object/object_id/public
GET returns public part of object

/object/object_id/private
GET returns private part of object
NO AUTH NEEDED

/rubric
GET Returns a random rubric id
POST creates a new Rubric Registration Object (RRO)

/rubric/rubric_id
GET returns a Rubric Registration Object
POST creates a replacement RRO

/rubric/rubric_id/compressed
GET returns full RRO as compressed JSON

/rubric/rubric_id/public
GET returns public part of RRO

/run/object_id
POST runs the public scripts if auth credentials are provided
GET returns the public scripts, NO AUTH REQUIRED

== Rubric Service Foundation (RSF) ==

The Rubric Service Foundation will be formed to provide ongoing support and guidance for the RSN and Rubricoin. We feel that for long-term success we need to have leadership in a  number of areas. The foundation will staff key skill positions and provide valuable services to the RSN.

=== RSF Funding ===

Initial funding of the RSF will be through crowdsourcing, those funds will be used to create the system. For ongoing funding the RSF will receive a share of the Rubric Fees collected by the RSN and by actively participating in the RSN.

=== RSF Charter ===

# Maintain one or more rubrics as required to host a copy of every current file in the RSN. The RSF will receive the fees from this service and disburse them as they see fit to the various RSF efforts. This will provide the RSF with approximately 10% of the outgoing storage funds and 10% of the Rubric Voting Rights. This ensures the RSF has a strong but not controlling voice in the operations of the RSN. It also ensure the RSF is directly affected by the Rubric Fee payouts to Rubric owners.
# Staff the RSF advisory positions 
#* Software Systems -responsible for leading programming efforts and managing bounty developers.
#* Security - specifically tasked with testing and maintaining all aspects of the RSN, they should not be conflicted with other RSN tasks or activities. 
#* Network Systems - responsible for advancing and supporting the lower level of the RSN stack, including supporting Docker, Node.js, Linux systems and Block Chain.
#* User Experience (UX) - responsible for defining the look and feel of the RSF and RSN web sites, tools and communications.
#* Evangelist - responsible for spreading the word about the RSN, their focus is external communication.
#* Community Manager - responsible for managing relations and voting with the RSN users, Rubric owners, Rubric developers and RSF staff. 
# Maintain RSN and RSF domain registrations
# Provide RSN and RSF web sites and hosting
# Provide a single point for media contact
# Manage Development Bounties

== Developer Friendly ==

The Rubric Service Network was designed by web developers and its been built from the ground up to speed development of cryptocurrrency powered web applications. The RSN uses proven open source technologies and builds upon them. The tools and languages used were chosen in part for their familiarity to web developers and network system administrators. 

Web applications access the RSN using web services. To aid developers that RSN provides a client-side JavaScript library and a PHP server side library, libraries in other languages may be added at a later date.
 
=== Open Technology Stack ===

By utilizing existing open source software and industry standards we provide developers access to a large suite of existing tools and libraries. This also allows for a large pool of pre-trained Rubric system developers and engineers. We borrow heavily much of the technology from the Linux and JavaScript communities. Many of the standards come from the [https://www.oasis-open.org/ Organization for the Advancement of Structured Information Standards] (OASIS).

==== Docker - Virtualization ====
	
[http://en.wikipedia.org/wiki/Docker_(software) Docker] provides a way to processes in isolation. This is used to run the Rubric Scripts in a secure manner.
	
'' The container technology in Docker can extend distributed systems so they run autonomously on a single physical machine or with a single instance per node. This enables the deployment of nodes as resources are available, thus providing seamless platform as a service (PaaS)–style deployments.''
	
Rubrics will support a small number of concurrent Docker images. This will allow use to support multiple versions of the Rubric Compute Container (RCC). This will support rolling updates to the RCC.

==== Web Payments ====

Web commerce is at our core and the Rubric transaction process is based on the latest [http://www.w3.org/ W3C] recommendation for defining and handling [https://web-payments.org web payments]. The RSN implements their protocol for all Rubric [https://web-payments.org/specs/source/secure-messaging/ communications] and [https://web-payments.org/specs/source/identity-credentials/ identification].

==== JavaScript ====
JavaScript is [http://w3techs.com/technologies/details/cp-javascript/all/all used on 90%] of the web sites. It's built into every major browser and is supported on almost every desktop, tablet and smartphone.

Regardless of whether a web developer programs primarily in PHP, Java, C#, Perl, Pyton or Ruby the chances are they know JavaScript. It's the only real choice for client side scripting so even if they are proficient in it they have certainly been exposed to it.

Since JavaScript has been around since 1995 and is used on so many sites there are a large number of Open Source libraries available. These will not only help in developing the Rubric Service, it will help web developers extend them in ways we never imagined.

==== Node.js - Web Server====

The Node.js web site defines Node.js as "using an event-driven, non-blocking I/O model that makes it lightweight and efficient, perfect for data-intensive real-time applications that run across distributed devices". It's Open Source, written in JavaScript, and has been used in production web development environments since 2010. Node.js runs on Linux, MacOS and Windows, as well as many other smaller OSes, allowing developers to use the operating system of their choice.

What all that means is that Node.js is ideal for powering a decentralized application. 

Node.js is used to power the Rubric Web Services as well as being the core component of the Rubric Compute Container. Using it in both environments provides a common ground between the Rubric Software developers and web developers consuming Rubric resources.

We use [https://www.npmjs.org/package/nexe nexe] to compile Node.js down to a single executable.

==== Sail - Framework ====

[http://sailsjs.org/ Sail] is an advanced JavaScript framework. We provide all network service through a web-based API, this include Rubric-to-Rubric (r2r) and Rubric-to-Client (r2c) communications. The BitLov web pockets application is written in Sail and provided as open source software.

==== Nools - Rules Engine ====

[https://www.npmjs.org/package/nools Nools] is a [http://en.wikipedia.org/wiki/Rete_algorithm rete] based rules engine written entirely in JavaScript. Th RSN uses this to process the transaction rules and encumbrances in a consistent manner.

''When rules are expressed in natural language, it is necessary to first define a vocabulary that contains words and expressions corresponding to business objects and conditions and the operations involving them. To make the rules executable by a rule engine, it is also necessary to implement the operations and conditions in a programming language. With a defined and implemented vocabulary, it is relatively easy to write rules in a BRMS. Changes can also be made quickly as long as they can be expressed in the existing vocabulary. If not, the vocabulary must be expanded accordingly.''

==== JSON - Data Format ====

JSON is an open standard, language-independent data format that uses human-readable text to store and transmit data objects. It was originally developed for use in JavaScript though now most software languages have modules or libraries for parsing and reading JSON. This makes it a perfect bridge between any existing web application and the Rubric Services.

===== JSON Schema =====

[http://json-schema.org/latest/json-schema-core.html JSON Schema] is used to define the elements within objects.

===== JSON-LD - Data Definitions =====

The data is formatted as [http://json-ld.org/ JSON-LD]. This permits defining context for the contained information without having to include all that additional data in the object. This technology allows Bitlov and other providers to power automation templates. It also reduces storage cost and bandwidth by allowing terms to be defined outside of the object.

===== Encrypted JSON =====

We leverage the work of leading industry groups that have already looked at ways to store objects on the network securely, specifically the [http://datatracker.ietf.org/wg/jose/ JSON Object Signing and Encryption (JOSE)] IETF working group. This allows the web developer to use the encryption algorithm of their choosing.

==== Business Process Execution Language (WS-BPEL) ====

[http://en.wikipedia.org/wiki/WS-BPEL WS-BPEL] provides a language for the specification of Executable and Abstract business processes. By doing so, it extends the Web Services interaction model and enables it to support business transactions. WS-BPEL defines an interoperable integration model that should facilitate the expansion of automated process integration both within and between businesses.

==== Universal Business Language (UBL) ====
[http://en.wikipedia.org/wiki/Universal_Business_Language UBL]  is a library of standard electronic XML business documents such as purchase orders and invoices. UBL is designed to plug directly into existing business, legal, auditing, and records management practices.[1] It is designed to eliminate the re-keying of data in existing fax- and paper-based business correspondence and provide an entry point into electronic commerce for small and medium-sized businesses.

This will be used in creating the pocket scripts. Wherever possible we attempt to use the same work flows, terminology and elements as the [http://docs.oasis-open.org/ubl/os-UBL-2.1/UBL-2.1.html standard].

==== Election Markup Language (EML) ====
[http://en.wikipedia.org/wiki/Election_Markup_Language EML] is an XML-based standard to support end to end management of election processes.

The [http://docs.oasis-open.org/election/eml/v7.0/eml-v7.0.html election definitions and codes] provided will be used in the DApp voting system.

Voting is used for:
* Hiring directors
* Prioritizing development 
* Offering bounties
* Approving protocol changes

==== Legal XML ====

[http://en.wikipedia.org/wiki/Legal_XML Legal XML] is a non-profit organization developing open standards for legal documents and related applications. Legal XML produces standards for electronic court filing, court documents, legal citations, transcripts, criminal justice intelligence systems, and others.

This will be used to model the legal aspects of [https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=legalxml-econtracts contracts] within the Rubric Object. The RSN does not utilize this information and its not used in creating contracts within the Rubric Script.

==== RESTful API Modeling Language (RAML) ====

RESTful API Modeling Language [http://raml.org/ (RAML)] is used to define the Rubric Web Services API. It is a simple and succinct way of describing practically-RESTful APIs.
