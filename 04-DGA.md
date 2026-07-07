# **The EU Data Governance Act (DGA) — Regulation (EU) 2022/868**

## **1. Executive Summary & Overview**

The Data Governance Act (DGA) is a critical pillar of the European Strategy for Data. Applicable since September 24, 2023, the DGA aims to boost the availability of data for use, building trust in data intermediaries and reinforcing data-sharing mechanisms across the EU. It is designed to create a secure, sovereign environment where data from the public sector, businesses, and individuals can be shared for societal and economic benefit without compromising privacy or proprietary rights.

While the GDPR protects the fundamental right to privacy, the DGA focuses on **fostering trust in the mechanics of data sharing** to unlock the value of non-personal data and carefully guarded personal data.

## **2\. The Four Pillars of the DGA**

The DGA addresses four distinct areas of data governance:

1. Re-use of Protected Public Sector Data.
2. Regulation of Neutral Data Intermediation Services (Neutrality).  
3. Data Altruism (Donating data for public good).
4. Establish the European Data Innovation Board (EDIB).

### **2.1. Re-use of Sensitive Public Sector Data (Chapter II)**

Public sector bodies hold vast amounts of data (e.g., commercial confidentiality, health records, intellectual property, statistical confidentiality) that cannot be shared under standard Open Data directives.

* The DGA does **not** force public bodies to share this data, but if they choose to, they must establish secure, non-discriminatory technical conditions.  
* **Anonymization & Secure Environments:** Public bodies must ensure that personal data is anonymized, and proprietary commercial data is protected before transmission. They can mandate the use of secure processing environments (similar to "clean rooms") controlled by the public sector.  
* Exclusive agreements for the re-use of public sector data are prohibited, unless necessary for providing a service in the public interest (limited to a maximum of 12 months).

### **2.2. Neutral Data Intermediaries (Chapter III)**

To prevent giant tech platforms from monopolizing data flows, the DGA introduces a regulated class of **Data Intermediation Services**. These are platforms that connect data holders (businesses or individuals) with data users.

* **The Strict Neutrality Requirement:** To build absolute trust, these intermediaries must remain completely neutral. They **cannot** monetize, analyze, or use the data they route for any other purpose (such as advertising, profile building, or developing their own products).  
* They must operate as structural utilities, charging flat transaction or subscription fees rather than taking a stake in the data itself.  
* They must register with national authorities and bear a specific EU label identifying them as "recognised data intermediation services providers."

### **2.3. Data Altruism (Chapter IV)**

The DGA establishes a legal framework for **Data Altruism**, allowing individuals and companies to make their data voluntarily available without compensation for purposes of general interest (e.g., medical research, climate change mitigation, traffic optimization).

* **Registered Entities:** Organizations managing altruistic data must register as a "Data Altruism Organisation recognised in the Union."  
* They must be non-profit, have independent governance structures, and maintain strict security standards.  
* **EU Consent Form:** The European Commission has created a standardized "European data altruism consent form" to allow citizens to easily give, manage, and withdraw consent for altruistic data donation.

### **2.4. European Data Innovation Board (EDIB \- Chapter VI)**

The DGA establishes the EDIB to facilitate cross-border consistency and sharing.

* It is composed of representatives from national authorities of all Member States, the European Data Protection Board (EDPB), and the European Commission.  
* Its role is to advise the Commission on data sharing, standardization of metadata, and the creation of common European data spaces (e.g., health, energy, agriculture).

## **3\. Interaction with GDPR**

The DGA is completely subordinate to the GDPR. Article 1(3) states that **Union and national law on the protection of personal data shall apply to any personal data processed in connection with this Regulation.**

* If an altruistic data transfer involves personal data, it must have a valid GDPR legal basis (typically Consent, Art. 6(1)(a)).  
* Intermediaries must ensure that data subjects can easily exercise their GDPR rights.

## **4\. Implications for Data Ethics Practitioners**

1. **Setting up "Clean Rooms":** Ethicists and data architects must design and audit secure execution environments that guarantee zero data leakage of sensitive public records while allowing researchers to query aggregate insights.  
2. **Consent & Sovereignty in Altruism:** Designing user-centric interfaces for altruistic data donations. Users must be fully aware of *who* is using their donated data and for *what* specific scientific or societal purpose, avoiding deceptive onboarding.  
3. **Evaluating Intermediary Neutrality:** Ensuring that corporate data exchanges do not secretly bundle data routing with analytical profiling tools, strictly adhering to the neutrality provisions of Chapter III.
