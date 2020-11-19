Indicio Transaction Author Agreement 

Version 1.3

11/10/2020

**Summary:**

This summary is to help you understand your obligations when writing to the Indicio Network, which is composed of a TestNet, DemoNet, and MainNet. It does not have any legal effect or replace the full legal text of the agreement provided below it.



*   We define the Transaction Author role (or any role described in this statement that performs the functions of a Transaction Author) as one of using an application to add transactions to the Indicio Network for the purpose of issuing Credentials.  
 
Credential issuing transactions include, but may not be limited to, writing Schema and Credential Definitions, unprivileged DIDs, altering DID attributes, creating Revocation Registries, and updating Revocation Registries. 

*   This agreement grants you the Transaction Author permission to write data to the Indicio Network and its component Networks, the Indicio TestNet, DemoNet, and MainNet under certain terms and conditions.  

*   You represent and warrant that the data you are writing does not violate any applicable laws or infringe the rights of any other party.

     

*   You understand the data you write to the TestNet and DemoNet is public but not permanent, and in accordance with the Indicio TestNet agreement will be erased by periodic resets of the TestNet and DemoNet. 

*   You understand that any data you write to the MainNet is public and permanent and cannot be erased. This includes public keys.  

*   If it is determined that the data you wrote violated this agreement, Indicio can impose penalties, including suspension or termination of this agreement, and may take steps to block public access to this data through creating a Tombstone.  

*   Indicio makes no promises about the reliability or correctness of the data stored on the Indicio Network or the operation of the Indicio Network. 

**Agreement.**

This Transaction Author Agreement (the “**Agreement**”) is entered into on the date you accepted this Agreement (the “**Effective Date**”) between Indicio Inc., a Benefit Corporation organized under the laws of the State of Delaware, United States of America (“**Indicio**”), and you (“**Transaction Author**”), either an entity or a natural person acting as an Individual. 

Indicio and the Transaction Author are individually referred to herein as a “Party” and collectively as the “Parties.” All references to “you” throughout this Agreement will include that person or entity. You represent that you are authorized to accept this Agreement on that person’s or entity’s behalf, and in the event you or the person or entity violates this Agreement, the person or entity agrees to be responsible to Indicio. 

By clicking “Accept” or similar or writing Transactions to the Indicio Network, the Transaction Author agrees to be bound by this Agreement and all terms incorporated by reference. If the Transaction Author does not agree to this Agreement in its entirety, do not click “Accept” or write Transactions to the Indicio Network. 

If Indicio makes material changes to this Agreement, we will notify you by posting a notice on our website prior to the effective date of the changes. By continuing to act as a Transaction Author or by otherwise writing Transactions on the Indicio Network after we post changes to our website, you agree to be bound by the revised Agreement. 


WHEREAS, the Transaction Author desires to write Transactions to the Indicio Network

(each a “**Transaction**”); and 

WHEREAS, subject to the Transaction Author complying with the terms and conditions of this Agreement, Indicio grants permission to the Transaction Author to write Transactions to the Indicio Network; 

FOR GOOD AND VALUABLE CONSIDERATION, THE SUFFICIENCY OF WHICH IS HEREBY ACKNOWLEDGED, THE PARTIES AGREE AS FOLLOWS: 


## 1. 	Definitions

*Pertaining to the network:*



1. 	The **Indicio Governance Framework** refers to Indicio’s governance public benefit mission, policies, and rules available at LINK or any successor website.  


2. 	The **Indicio Ledger** is the collective term for all the ledgers on the Indicio Network, including the MainNet, DemoNet, and TestNet, and their sub ledgers, viz., pool, admin, main, config., etc. 


3. 	The **Indicio Network** is a public, permissioned network built on Hyperledger Indy, Aries, and Ursa, and consisting of a MainNet, DemoNet, and TestNet. It is run by Indicio—the genesis node operator for the Network—and the Node Operators, of which Indicio is also a member. Public refers to being able to read and permissioned refers to the ability to write to the ledger. 


*Network terminology:* 



4.	A **Credential** is a digital assertion containing a set of claims about the identity attributes of an entity (as per ​IETF RFC 3986, Uniform Resource Identifier (URI)​, an entity is a resource of any kind that can be uniquely and independently identified). 



5. 	A **Credential Definition** is a machine-readable definition of the semantic structure of a Credential based on one or more Credential Schemas.  



6. 	A **Credential Schema** is a machine-readable definition of the semantics of data structure. Schemas define the attributes in a Credential Definition.  



7. 	A **DID** is the acronym for decentralized identifier, a unique, permanent URL for an identity. 



8. 	A **DID** Document is a machine-readable document describing the public cryptographic keys, service endpoints, and other metadata associated with a DID. Each DID points to a unique DID document on a ledger.  



9. 	A **Revocation Registry** is a cryptographic data structure for recording the revocation of credentials. 



10.	**Permissioned Write Access** refers to a network state where “Public Write Access” is not permitted. In this state, Transaction Authors may only write transactions with a signature from an approving Transaction Endorser. 



11. **Public Write Access** refers to the state that a network is in when anyone can become a Transaction Author and write to the ledger. The Indicio Network does not, in its present state, allow Public Write Access.


12. **Public Read Access** means that anyone can access, audit, read, or download content on the Ledger, although there may be a fee to do so. 



13. A **Tombstone** is a technical means of blocking public access to a ledger record without erasing that record. It is used only in the event of impermissible public data being written to the ledger in violation of Transaction Author and Endorser agreements.   



14. A **Transaction** refers to the act of writing Schemas and Credential Definitions to the ledger for the purpose of issuing Credentials, creating Revocation Registries for the purpose of revoking credentials, updating Revocation Registries, creating a DID, adding or editing attributes to a DID, and rotating a DID’s key.   



15. A **Transaction Author** refers to an entity using an application to write records to the Indicio Network for the purpose of issuing credentials. Credential issuing transactions include, but may not be limited to, writing Schema and Credential Definitions, creating Revocation Registries, and updating Revocation Registries. They can also write DID transactions to the ledger including DID creation, attribute creation and editing, and key rotation. 



16. A **Transaction Endorser** refers to an entity that is authorized to approve a Transaction Author write to the ledger. 



17. A **Trustee** refers to a person authorized to administer the governance and maintenance of the network. Multiple Trustee signatures are required to perform certain administrative and maintenance functions.


*Pertaining to data privacy:*


18. **Data Controller**  is defined by the EU General Data Protection Regulation (GDPR), the natural or legal person, public authority, agency, or other body which, alone or jointly with others, determines the purposes and means of the processing of Personal Data.


19. **Data Processor** is defined by the EU General Data Protection Regulation (GDPR), a natural or legal person, public authority, agency, or other body which processes Personal Data on behalf of a Data Controller**.**


20. **Data Protection Laws** mean California’s Consumer Privacy Act (CCPA), the European Union’s General Data Protection Regulation (GDPR), and any other national or international data protection and privacy laws, regulations, and regulatory requirements applicable to a party under this Agreement.  



21. **Personal Data** means information that relates directly or indirectly to a data subject, including without limitation, names, email addresses, postal addresses, identification numbers, location data, online identifiers, or one or more factors specific to the physical, physiological, genetic, mental, economic, cultural or social identity of the data subject. 


22. **Node Data**​ means any information which includes any Personal Data that a Node Operator Processes through the Node.	


23. **Permissible Personal Data** refers to the Personal Data that a Transaction Author writes to the Indicio Network that is permitted under this Agreement and Indicio’s Governance Framework, namely, but not limited to, identification numbers and online identifiers. 



24. **Impermissible Personal Data** refers to personal data that is not covered under Permissible Personal Data and should not be written to the ledger 



25. **Process** or **Processing** means any operation or set of operations that is performed on Transaction data, whether or not by automated means, such as the access, collection, use, storage, disclosure, dissemination, combination, recording, organization, structuring, adaption, alteration, copying, transfer, retrieval, consultation, disposal, restriction, erasure and/or destruction of Transaction data. 




## 2. 	Permission to write to the Indicio Network 


1.	Indicio hereby grants to the Transaction Author a non-exclusive, non-assignable, non-sublicensable, royalty free, and revocable license to write to and use the Indicio Network in accordance with this Agreement and the applicable Indicio Governance Framework or Indicio TestNet Governance Framework. 


2.	Transactions can only be authored through Permissioned Write Access, whereby a Transaction Author can only write to the Indicio Network by using an authorized Transaction Endorser.  



3.	Once an initial Transaction has been written to one of the Indicio Networks by the Transaction Author, the Transaction Author is granted permission to make additional Transactions to update the state of a previous Transaction.



    An update transaction does not remove the initial transaction, which will remain on the Indicio Main Network (MainNet) due to the immutability of the ledger; and a transaction will remain on Indicio Test Network (TestNet) or Demo Network (DemoNet) until it is reset, which will occur at periodic intervals.  

    A Transaction Author may make an update transaction if and only if the Transaction Author was the author of the initial transaction. Update Transactions are Transactions and are subject to all the terms of this Agreement. 


## 3. 	Transaction Author obligations 


*Pertaining to all Transactions, a Transaction Author MUST:*



1. Comply with any requirements imposed by the Transaction Endorser on the Transaction Author.
1. Not write Impermissible** **Personal Data to the ledger. 
1. Not write data to the ledger that would violate the intellectual property rights of others. 






## 4.	Penalties for violating Transaction Author Agreement


1. 	In the event that the transaction author intentionally or inadvertently violates the terms of the Transaction Author and Transaction Endorser agreements and writes Impermissible** **Personal Data to the ledger, Indicio reserves the right to act on behalf of the Node Operators and block public access to that data through creating a Tombstone. 


2. 	Depending on the severity of an infraction or in the event of repeated infractions, Transaction Endorsers may be required to block endorsement of specific Transaction Authors by the Network Trustees. 



## 5.	Data processing and control under GDPR


1. 	Indicio will serve as the designated data controller for the Indicio Network; all roles and rules with respect to Transaction Endorsers complying with GDPR are explained in the Indicio Data Processing Agreement. 





## 6.	 Term and termination 


1. 	This Agreement commences on the Effective Date and shall remain in force until terminated by either Party pursuant to this **Section 6 (Term and Termination)**.  





2. 	Either Party may terminate this Agreement: (i) if the other Party has materially defaulted in the performance of any of its obligations under this Agreement and has not cured such default within fifteen (15) business days of receipt of written notice from the non-defaulting Party of such default or (ii) immediately in the event of any government sanctions or other legal measures that make it unlawful for Transaction Author to write Transactions to the Indicio Network.  



3.	Additionally, the Transaction Author may terminate this Agreement upon 30 days’ advance written notice to Indicio and ceasing all use of the Indicio Network. 


4.	The Transaction Author Agreement can be immediately terminated by Indicio if the Transaction Author writes Impermissible Personal Data to the ledger.


5.	Upon termination or expiration of this Agreement for any reason, the rights granted to the Transaction Author by Indicio under this Agreement automatically terminate. 


6. 	Specific instructions for relinquishing a validator node are described in the document “Node Operator Termination.” 



## 7. Representations and warranties; disclaimer 

a. By Indicio:


1. 	THE INDICIO NETWORK IS PROVIDED AS-IS WITH ALL FAULTS. TO THE FULLEST EXTENT PERMITTED BY APPLICABLE LAW, INDICIO MAKES NO REPRESENTATION OR WARRANTY CONCERNING THE ACCURACY, RELIABILITY, OR COMPLETENESS OF ANY INFORMATION OR DATA OBTAINED OR DERIVED THROUGH THE USE OF THE INDICIO NETWORK AS THE INDICIO NETWORK OPERATES ON A DISTRIBUTED NETWORK AND INDICIO DOES NOT CONTROL THE INFORMATION OR DATA WRITTEN TO THE INDICIO NETWORK. INDICIO DISCLAIMS ANY OTHER REPRESENTATIONS OR WARRANTIES, EXPRESS OR IMPLIED, INCLUDING WITHOUT LIMITATION, ANY WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE, NON-INFRINGEMENT, ACCURACY OR COMPLETENESS OF DATA. 



2.	As the architect of the Indicio Network and administrator of the Indicio Governance and TestNet Frameworks, Indicio is an independent controller of the Personal Data Transactions. In no event will the Indicio be held liable for the actions or omissions of Transaction Author arising out of any Impermissible** **Personal Data that Transaction Author writes to the Indicio Network in breach of this Agreement and the Indicio Governance and TestNet Governance Framework, including but not limited to any Impermissible Personal Data. Notwithstanding the foregoing, if Transaction Author writes Permissible Personal Data to the Indicio Network in express compliance with this Agreement and the Indicio Governance Framework, Indicio is responsible for the lawfulness of such Processing once such Permissible Personal Data is written to the Indicio Network. 



b. By Transaction Author. Transaction Author represents and warrants: 


3.	If a natural person, he or she is 16 years of age or older.  



4.	It has all necessary rights and permissions to write the Transactions. 



5.	The Transactions do not and will not violate any applicable law.  



6.	The Transactions will not contain data or information that infringes on or misappropriates the intellectual property rights of any third party. 



7.	It understands that the Indicio Network operates on a distributed network and that Indicio disclaims any responsibilities with respect to access of data from the Indicio Network. 



8.	It understands and acknowledges that Indicio does not control the transfer of data between Nodes and over communications facilities, including the internet, and that the Indicio Network may be subject to limitations, delays, and other problems inherent in the use of such communications facilities.  



9.	It understands and acknowledges that there is regulatory uncertainty regarding the Indicio Network’s compliance with Data Protection Laws as it relates to Permissioned Write Access, Public Write Access, and Personal Data, including cross-border transfers of data, Processing of Personal Data, the right to effective erasure of data, as well as the scope and nature of Personal Data itself.  



10.	It understands and acknowledges that Indicio may modify, at any time, the terms of this Agreement and any other agreement or document related to the Indicio Network based on new information, guidance, or Data Protection Laws; and  



11.	It understands and acknowledges that a Node Operator and/or Indicio may obscure a Transaction if (i) the Node Operator or Indicio is required to do so by a court order or applicable law or (ii) the Node Operator or Indicio has evidence that the Transaction violates the terms of this Agreement or any applicable law.





## 8.	 Indemnification 


1.	To the fullest extent permitted by applicable law, a Transaction Author will indemnify and hold harmless Indicio, and each of its respective officers, directors, agents, partners and employees (individually and collectively, the “**Indicio Parties**”) from and against any losses, liabilities, claims, demands, damages, expenses or costs (“**Claims**”) brought by a third party arising out of or related to (i) Transaction Author’s access to or use of Indicio Network in violation of this Agreement; (ii) Transaction Author’s violation, misappropriation or infringement of any rights of another (including intellectual property rights or privacy rights); or (iii) Transaction Author’s violation of applicable law.


2.	A Transaction Author agrees to promptly notify the Indicio Parties in writing of any Claims, cooperate with the Indicio Parties in defending such Claims and pay all fees, costs and expenses associated with defending such Claims (including attorneys’ fees). Transaction Author also agrees that the Indicio Parties will have sole control of the defense or settlement, at Indicio’s sole option, of any Claims. This indemnity is in addition to, and not in lieu of, any other indemnities set forth in a written agreement between Transaction Author and Indicio or the other Indicio Parties. 




## 9.	 Governing law and forum 

This Agreement is governed by the law of the State of Delaware, without reference to conflict of laws principles; provided that, if Transaction Author is a governmental entity, this Agreement is governed by the law in which such governmental entity is established. All disputes arising out of or in connection with this Agreement shall be finally settled by binding arbitration under the Rules of Arbitration of the International Chamber of Commerce (the “**Rules**”) by a single arbitrator appointed in accordance with said Rules. Arbitration proceedings will be held in Washington, DC. Unless the Parties otherwise mutually agree, such arbitration shall be conducted in the English language by electronic exchange of documents and by video conference. The arbitrator shall issue a reasoned decision, including findings of fact and conclusions of law. The arbitrator shall require exchange by the Parties of documents relevant to the issues raised by any claim, defense, or counterclaim or on which the producing Party may rely in support of or in opposition to any claim, defense, or counterclaim, with due regard for eliminating undue burden and expense and the expedited and lower cost nature of arbitration. At the request of a Party, the arbitrator may at his or her discretion order the deposition of witnesses. Depositions shall be limited to a maximum of three depositions per Party, each of a maximum of four hours duration, unless the arbitrator otherwise determines. Demand for arbitration may be initiated by either Party on fifteen (15) days written notice by email to the other Party’s designated representative, together with a written specification of the grounds for the dispute and the relief requested. By agreeing to binding and non-appealable arbitration, each party understands that they each forever give up and waive any right which each Party may have to resolve any such claim, difference or dispute by court or jury trial. Notwithstanding the foregoing, either Party may bring a proceeding seeking equitable or injunctive relief solely and exclusively in the state and federal courts located in Wilmington, Delaware, to prevent the infringement of .intellectual property rights or the disclosure of confidential information. Each Party hereto consents to the exclusive jurisdiction of such courts for the adjudication of any such equitable or injunctive relief, as well as for any such matters that are excluded from or fall outside of this arbitration provision. 


## 10. 	Limitation of liability 

EXCEPT IN THE EVENT OF EITHER PARTY’S GROSS NEGLIGENCE, WILLFUL MISCONDUCT OR FRAUD, IN NO EVENT SHALL EITHER PARTY BE LIABLE FOR ANY INDIRECT, INCIDENTAL, EXEMPLARY, PUNITIVE, SPECIAL, OR OTHER CONSEQUENTIAL DAMAGES UNDER THIS AGREEMENT, INCLUDING, WITHOUT LIMITATION, ANY LOST PROFITS, BUSINESS INTERRUPTION, LOSS OF PROGRAMS OR DATA, OR OTHERWISE, EVEN IF THE OTHER PARTY IS EXPRESSLY ADVISED OF THE POSSIBILITY OR LIKELIHOOD OF SUCH DAMAGES. 

EXCEPT IN THE EVENT OF EITHER PARTY’S GROSS NEGLIGENCE, WILLFUL MISCONDUCT OR FRAUD, IN NO EVENT SHALL EITHER PARTY’S LIABILITY UNDER THIS AGREEMENT EXCEED $250,000 USD IN THE AGGREGATE, PROVIDED THAT THERE WILL BE NO DOLLAR CAP ON LIABILITY FOR DAMAGES ARISING FROM VIOLATIONS OF DATA PROTECTION LAWS. IN THE EVENT OF EITHER PARTY’S GROSS NEGLIGENCE, SUCH PARTY’S LIABILITY UNDER THIS AGREEMENT SHALL NOT EXCEED $500,000 USD IN THE AGGREGATE. IN THE EVENT OF EITHER PARTY’S WILLFUL MISCONDUCT OR FRAUD, THERE SHALL BE NO DOLLAR CAP ON SUCH PARTY’S LIABILITY UNDER THIS AGREEMENT. 


## 11. 	Miscellaneous 



1.	Notice. Any notice, payment, demand or communication required or permitted to be delivered or given by the provisions of this Agreement shall be deemed to have been effectively delivered or given and received on the date personally or electronically delivered to the respective Party to whom it is directed, or when deposited by registered or certified mail, with postage and charges prepaid and addressed to each respective Party. For the Transaction Author, notices will be sent to the agent service endpoint of the Transaction Author’s DID as long as the Transaction Author authorizes such a connection or sent via another mechanism agreed to by the parties. For Indicio, notices will be sent to Indicio Inc., 1225 13th St. NW, suite 205, Washington, DC, USA. 



2.	Severability. If any provision of this Agreement is held invalid, illegal, or unenforceable, the validity, legality, and enforceability of any of the remaining provisions of this Agreement shall not in any way be affected or impaired.  



3.	Relationship of the Parties. This Agreement does not create a partnership, franchise, joint venture, agency, fiduciary or employment relationship between the Parties. Neither Party will represent that it has any authority to assume or create any obligation, express or implied, on behalf of the other Party, nor to represent the other Party as agent, employee, franchisee, or in any other capacity. There are no third-party beneficiaries to this Agreement. Neither Party shall make any proposals, promises, warranties, guarantees, or representations on behalf of the other Party or in the other Party’s name.  



4.	Assignment. Neither Party will voluntarily, or by operation of law, assign or otherwise transfer this Agreement without the other Party’s express prior written consent which will not be unreasonably withheld, provided that no such consent is required for an assignment or transfer to a wholly or majority owned subsidiary or to a successor in interest by reason of merger or consolidation or sale of all or substantially all of the assets of such Party relating to the subject matter of this Agreement.  



5.	Waiver. The waiver by either Party of a breach, default, delay or omission of any of the provisions of this Agreement by the other Party will not be construed as a waiver of any subsequent breach of the same or other provisions. 



6.	Entire Agreement. This Agreement, including all documents incorporated into this Agreement by reference, constitutes the entire agreement of the Parties with respect to the subject matter of this Agreement, and supersedes any and all prior agreements and understandings of the Parties, whether written or oral, with respect to such subject matter. This Agreement supersedes all prior Transaction Author Agreements between Indicio and the Transaction Author with respect to the subject matter hereof.  



7.	Modification of This Agreement. Indicio reserves the right to modify this Agreement at any time in accordance with this provision, including, but not limited to, changes in applicable law or guidance from any jurisdiction. Indicio will post an amended version of this Agreement on its website at least thirty (30) days prior to the date on which all Transaction Authors must begin operating under the amendment (the “**Amendment Cutover Date**” ). If a Transaction Author continues to Author Transactions to the Indicio Network after the Amendment Cutover Date, such continued use will constitute acceptance of the amended Agreement.  



8.	Counterparts. This Agreement may be executed in two or more counterparts, each of which will be deemed an original, but all of which taken together will constitute one and the same instrument.  



9.	Survival. Any terms that by their nature survive termination or expiration of this Agreement shall survive.  



10.	Governmental Entities. If Transaction Author is a governmental entity and it determines that GDPR does not apply to it and its Processing of Transactions, then:  



    a.	to the extent that the GDPR requirements referenced in this Agreement are equivalent to the requirements under Data Protection Laws in its own jurisdiction, it will comply with any such requirements; and  



    b.	to the extent that GDPR requirements referenced in this Agreement differ from requirements under Data Protection Laws in its own jurisdiction, it will comply with the requirements under its own legislation.  

