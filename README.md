# credential-generator

The Credential Generator -project aims at developing a capability to turn the application profiles created with the Data Vocabularies -tool (https://github.com/VRK-YTI) into different flavors of W3C conformant Verifiable Credential definitions.  

Business case for the solution

Interoperability on all levels is a key factor for making digital identites and wallets useful for both natural and legal persons in their life events or business activities. Presently a very dominant part of the work regarding interoperability of digital wallets is, however, focused on the technical interoperability between the different components of the digital wallet infrastructure that would guarantee an ability to exchange proofs of all kinds between different commercial implementations of the architectural framework that the upcoming EU regulation in this area will enforce. In the recently published Architecture Reference Framework 1.0 (ARF) for the development of an interoperable EUDI Wallet solution it is simply stated that: "(Q)EAA Schema Providers publish schemas and vocabularies describing (Q)EAA structure and semantics. - - Common schemas, including by sector-specific organisations are critical for wide-spread adoption of (Q)EAAs."  

https://digital-strategy.ec.europa.eu/en/library/european-digital-identity-wallet-architecture-and-reference-framework   

As an issuer of a proof of any kind decides to create the definition of the proof in question, it would be tremendeously important for the semantic interoperability of this proof that it would be created based on some internationally acknowledged domain specific standard. Even if there is a standard or a reference data model (RDM) of some kind present, the use of these standards require in general lot's of manual work by the implementer, since the standards for the semantics are usually published either as a simple PDF-document, an Excel-sheet, a UML diagram or something similar. In a handful of situations the proposed standard to be followed is published in a W3C Linked Data enabled format (RDF/OWL, JSON-LD or similar), which makes it possible to provide the issuers of the proofs with the capability of either creating standards or RDM 

Description of the process for creating semantically interoperable credential definitions

The first part of the process is already enabled by the Interoperability Platform, developed by the Finnish Ministry of Finance in cooperation with DVV (The Finnish Digitalization Agency). It encompasses the creation of domain specific terminologies in the form of SKOS ontologies by defining concepts and their relationships that are relevant 

Issuers of electronic attribute attestations should 
