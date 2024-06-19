# ROAX: Rod of Asclepius eXchange

NOTE: I was the lead engineer to launch one of Singapore's First Telemedicine App, going through the government sandbox for telemedicine and liasing with hospitals and clinis across the island. The app was used by many users. The code base was also part of Vietnam's national telemedicine app during the pandemic.
I was also the core payments engineer for one of Singapore's largest online payments company. My partner, Ansel, that will be contributiong to this project is a Medical Doctor that has a Postgraduate for Computing and also a Post Graduate in Analytics.
I've have used the NUS research Library to do a thorough research before writing this paper. So if you think the technology is normal, it isn't.

Feel free to contact me for more questions: https://twitter.com/KernelKennethG or zhenhao.goh@comp.nus.edu.sg. :)

We are looking for people to build this community together.

[ROAX-whitepaper / "greenpaper"](https://github.com/DarkArtistry/roax-dmrx/blob/main/ROAX-greenpaper-version3.pdf)

A platform for doctors, medical professionals and patients to store verifiable medical records in a more secure, compliant and privacy preserving manner.

## Introduction

The healthcare industry faces significant challenges related to data security, record credibility, and a lack of incentives for medical professionals to cooperate. ROAX aims to address these challenges by providing a decentralized, immutable, and universally interoperable medical record system. This document outlines the vision, technical architecture, economic model, and potential applications of ROAX.

In the wake of previous medical system hacks, such as ransomware attacks and the SingHealth data breach, it has become evident that centralized storage of information presents significant security vulnerabilities. ROAX enhances security by ensuring that information is not only stored on a centralized authority but remains with the data owner. This decentralized approach significantly mitigates the risks associated with data breaches.

Furthermore, the credibility of medical records is crucial. Instances like a Singapore doctor who altered medical records for personal gain highlight the dangers of tampering with medical data. ROAX provides a secure and safer alternative through its immutable decentralized medical record system, ensuring that records cannot be altered without detection.

Another critical issue is the lack of sufficient incentives for doctors and medical professionals to actively contribute to the healthcare ecosystem. ROAX proposes a solution by creating an economic model that incentivizes medical stakeholders. By enabling a universally interoperable protocol, ROAX fosters cooperation and connectivity among various medical entities, promoting a more collaborative and efficient healthcare system.

ROAX is being built as a Layer 1 blockchain system focused on establishing a universal interoperable privacy-preserving medical record framework. This innovative approach offers numerous benefits:

- **Universal Interoperability:** ROAX provides a framework that allows Decentralized Medical (DeMed) applications, such as insurance services, to be built on top of the core blockchain layer, promoting widespread adoption and integration.
- **Immutable, Privacy-Preserving, and Verifiable Records:** The system ensures that medical records are immutable and verifiable while preserving patient privacy. Only a verifiable proof is submitted onchain, while the raw data is securely stored in the patient's hardware device / mobile device. (Inspiration from WhatsApp End-To-End Encryption). Anyone, that receives the shared record, by the patient or the authorised entitiy can easily verify the medical record onchain. The current way of storing medical data in healthcare system is preserved.
- **Patient Ownership:** Patients maintain ownership of their medical records in a secure manner, giving them control over their personal health information. In the case of a ransomware attack, patients can easily re-share their records and medical entities can verify them on chain. They can, without fees, locally share their medical records and any receiving entity can actually verify the records on chain.
- **Cooperative Incentives:** For the first time in many years, ROAX gives doctors and medical professionals a voice and a stake in the system, providing incentives to cooperate and contribute to a universal healthcare network. Medical professionals are incentivised to keep the network secure, anyone requesting information will have to pay a transaction fee. In comparison to most national healthcare record system that face difficulties to rally private medical practitioners to share patient's medical record. A entity submitting data to a requesting entity, can make use of the receiver's public key, encrypt the data into a trusted temporary data availability service, emit an event, the receiver can locally decrypt the medical record.
- **New Economy:** In face of monopolistic organisations that have rights over medical data in an AI driven world, this creates an economy that allows individuals to contribute and monetise their own data to projects, possibly allowing a more competition in the market. A new insurance economy (a large portion of finance) can also be spun off from the foundations of this network.

ROAX is not a disruptive technology; rather, it catapults the existing healthcare system into a universal interoperable network, evolving the current system into humanity’s next healthcare system. This transformative approach aims to enhance the security, credibility, and efficiency of medical records, ultimately benefiting patients, healthcare providers, and the entire medical ecosystem for humanity.

## Features

### Universal Interoperability

ROAX enables Decentralized Medical (DeMed) applications to be built on top of its core blockchain layer, allowing for the widespread adoption and integration of various medical services.

### Immutable, Privacy-Preserving, and Verifiable Records

The ROAX system ensures that medical records are immutable and verifiable while preserving patient privacy.

### Patient Ownership

Patients maintain ownership of their medical records in a secure manner, giving them control over their personal health information.

### Cooperative Incentives

ROAX provides doctors and medical professionals with a voice and a stake in the system, incentivizing them to cooperate and contribute to a universal healthcare network.

## Technical Architecture

ROAX is being built as a Layer 1 blockchain system focused on establishing a universal interoperable privacy-preserving medical record framework. This section will detail the technical architecture of ROAX.

## Economic Model

ROAX introduces an economic model that incentivizes medical stakeholders, fostering cooperation and connectivity among various medical entities. This section will provide an in-depth overview of the economic model, including tokenomics and staking mechanisms.

## Potential Applications

ROAX supports a range of applications, including:

- Patient Data Sharing
- Insurance Claims Processing
- Clinical Trials Management
- Supply Chain Management
- Pandemic Detection

These applications highlight the versatility and broad utility of the ROAX platform.

## License

To protect this decentralised ecosystem and community,



The [Business Source License](https://github.com/DarkArtistry/roax-dmrx/blob/main/LICENSE) (this document, or the "License") is not an Open Source license. However, the Licensed Work will eventually be made available under an Open Source License, as stated in this License.

## Contact

For more information, please contact us at [zhenhao.goh@comp.nus.edu.sg](mailto:zhenhao.goh@comp.nus.edu.sg).


