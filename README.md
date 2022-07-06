# spec-tradetrust

Guidance for implementers on the use of TradeTrust extensions to the W3C verifiable credentials specification.

# Status

Raw - work has not yet started

# Goals

The Singapore government has developed OpenAttestation (see https://www.openattestation.com/) to enable documents issued with this technology to be cryptographically trustworthy and able to be verified independently. OpenAttestation provides the technology underpinnings of TradeTrust (see https://www.tradetrust.io) which is an open framework adapted for global trade practices to help the typically long chain of business partners achieve the ultimate objective of fully digitalising their business processes even across borders. Given the complexities of cross-border trade, success needs a multi-prong yet holistic approach. As such, with OpenAttestation providing the technology foundations, TradeTrust adds aspects such as acceptance by the global trade community and governments on the methods of document digitalisation as well as alignment on policy stances through G2G arrangements such as Digital Economy Agreements. These efforts have resulted in the following W3C verifiable credentials-related features being implemented:

* The Decentralised document rendering protocol enables users to choose their own document schema format, and to customise the look and feel of the trade documents produced.
* Selective Redaction provides a convenient method for intermediaries in the supply chain to hide sensitive data, which is critical for some use cases in the trade and traceability domains.
* The Title Transfer feature supports electronic transferable records and is designed to be compliant to the requirements laid out in UNCITRAL’s Model Law on Electronic Transferable Records (2017).
* The QR Code feature enables users to choose using paper or digital workflows, depending on their circumstances thus allowing issuers to execute digitalisation with minimal dependency on verifier technical capabilities. 

This repository provides guidance on the effective and interoperable use of TradeTrust protocols.

