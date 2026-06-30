# **The EU Artificial Intelligence Act (AI Act) — Regulation (EU) 2024/1689**

## **1\. Executive Summary & Overview**

The European Union Artificial Intelligence Act (AI Act) is a historic, landmark piece of legislation. Approved in 2024, it represents the world's first comprehensive, horizontal legal framework specifically regulating Artificial Intelligence. The AI Act adopts a **risk-based approach**, imposing proportional requirements depending on the threat level an AI system poses to fundamental human rights, safety, and societal values.

For data ethics practitioners, the AI Act shifts AI ethics from "voluntary self-regulatory guidelines" to "enforceable compliance mandates," changing how algorithms are researched, developed, deployed, and monitored in the European market.

## **2\. Defining "Artificial Intelligence" (Article 3\)**

The AI Act aligns its definition with the OECD to ensure international compatibility and future-proofing:

An **"AI System"** is a machine-based system that, for explicit or implicit objectives, infers, from the input it receives, how to generate outputs such as predictions, content, recommendations, or decisions that can influence physical or virtual environments.

## **3\. The Risk-Based Classification Framework**

The cornerstone of the AI Act is its division of AI systems into four tiers based on their potential risk:

1) **UNACCEPTABLE RISK** (Prohibited): social scoring, biometric categorization.  
2) **HIGH RISK** (Highly Regulated): critical infra, hiring, credit scoring.
3) **LIMITED RISK** (Transparency obligations): chatbots, deepfakes, generative AI.
4) **MINIMAL RISK** (No obligations): spam filters, video games.

### **3.1. Category 1: Unacceptable Risk (Prohibited AI Systems — Article 5\)**

These systems pose an absolute threat to the safety, livelihoods, and rights of people. They are strictly banned within the EU. Examples include:

* **Cognitive Behavioral Manipulation:** Systems that deploy subliminal techniques to distort a person’s behavior, causing physical or psychological harm.  
* **Social Scoring:** Classification of natural persons by public or private entities based on social behavior or personality traits leading to detrimental or disproportionate treatment.  
* **Predictive Policing:** AI systems used to assess or predict the risk of an individual committing a criminal offense based solely on profiling or personality traits.  
* **Untargeted Scraping:** Scraping facial images from the internet or CCTV footage to build or expand facial recognition databases.  
* **Emotion Recognition in Sensitive Areas:** Use of AI to infer emotions of natural persons in workplace environments and educational institutions.  
* **Biometric Categorization:** Systems that categorize individuals based on biometric data to deduce sensitive traits (race, political opinions, sexual orientation).

### **3.2. Category 2: High-Risk AI Systems (Highly Regulated — Chapter III)**

These systems are permitted but are subject to strict legal obligations before they can be placed on the market. They are classified into two sub-categories:

1. **AI as safety components of products** already subject to third-party conformity assessments (e.g., medical devices, aviation, cars).  
2. **Standalone AI systems in specific annexed areas:**  
   * Biometric identification and categorization of natural persons.  
   * Management and operation of critical infrastructure (e.g., water, gas, electricity, road traffic).  
   * Education and vocational training (e.g., grading systems, admissions software).  
   * Employment, worker management, and access to self-employment (e.g., CV ranking tools, promotion algorithms).  
   * Access to and enjoyment of essential private and public services (e.g., credit scoring, eligibility for welfare benefits).  
   * Law enforcement, migration, asylum, and border control.  
   * Administration of justice and democratic processes.

#### **Strict Obligations for High-Risk AI:**

* **Risk Management System:** Establishment of a continuous, iterative risk management process throughout the AI lifecycle.  
* **Data Governance:** High-quality training, validation, and testing datasets (checking for biases, representation, and data lineage).  
* **Technical Documentation:** Ex-ante documentation demonstrating compliance to supervisory authorities.  
* **Record-Keeping:** Automated logging of system events (traceability).  
* **Transparency and Provision of Information:** Clear instructions to deployers on how to use the system.  
* **Human Oversight:** High-risk AI must be designed to enable natural persons to supervise, intervene, or override decisions.  
* **Accuracy, Robustness, and Cybersecurity:** High level of resilience against errors, feedback loops, and malicious third-party attacks.

### **3.3. Category 3: Limited Risk (Transparency — Chapter IV)**

Systems presenting minor risks, primarily related to deception or lack of information.

* **Chatbots:** Users must be informed that they are interacting with an AI system unless it is obvious from the context.  
* **Generative AI & Deepfakes:** Content generated or manipulated by AI (images, audio, video) must be watermarked or disclosed as artificially generated.  
* **Emotion Recognition:** Users must be informed when such a system is active (where not prohibited).

### **3.4. Category 4: Minimal or No Risk**

Includes the vast majority of AI systems currently used in the EU (e.g., AI-enabled search, spam filters, inventory management). They face no mandatory requirements, though the EU encourages the voluntary adoption of codes of conduct.

## **4\. General Purpose AI (GPAI) & Foundation Models**

To address the rise of large-scale generative models (like GPT, Claude, or Midjourney), the AI Act introduces specific provisions for General Purpose AI:

* **Baseline Rules for all GPAI:** Providers must maintain technical documentation, comply with EU copyright laws, and publish summaries about the content used for training.  
* **GPAI with Systemic Risks:** Models trained with massive computational power (exceeding ![][image1] FLOPs) face extra obligations, including model evaluations, adversarial testing ("red-teaming"), tracking of energy consumption, and reporting of severe incidents to the European AI Office.

## **5\. Governance and Enforcement**

* **National Level:** Each EU Member State appoints a market surveillance authority (such as the *Agencia Española de Supervisión de la Inteligencia Artificial* \- AESIA in Spain) to oversee local compliance.  
* **EU Level:** The **European AI Office** is established within the European Commission to coordinate the application of GPAI rules and oversee cross-border issues.  
* **Sanctions:** Fines are highly punitive and calculated as a percentage of global turnover:  
  * Up to **€35 million or 7% of global annual turnover** for deploying prohibited AI practices.  
  * Up to **€15 million or 3% of global annual turnover** for non-compliance with High-Risk AI requirements.  
  * Up to **€7.5 million or 1.5% of global annual turnover** for supplying incorrect or misleading information to authorities.

## **6\. Implications for Data Ethics Practitioners**

1. **Mandatory Bias Audits:** Data ethicists must develop and execute robust bias-detection and mitigation pipelines on training data, specifically under high-risk categories like HR algorithms.  
2. **Watermarking and Trust Infrastructure:** Implementing secure, cryptographic, or metadata-based watermarks for generative models to comply with transparency requirements.  
3. **Human-in-the-Loop (HITL) Architectures:** Ethicists must design operational workflows that don't just put "human rubber stamps" on AI decisions, but enable meaningful, active human oversight.

[image1]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACQAAAAZCAYAAABZ5IzrAAADSUlEQVR4XrVWPWgUURDeS0SjKKjJ+XO3u2/fXWLwQAsrBZGQQhQbLcRCVCQIkkJBSKGFtRILkdhpISqKhfEPIol2GixEJVgJgmBjkUYlBAQ5v7l97272vdnkAvGDYed9M2/m29m3excEOSi4hEGDF4Kc4jmWV0oNwg6GYbjaUP8Tre5JkhxG48ewz7ARJugarK5imFLvy+Vy2NzOIdxsAy0+L4MjzQmjsBfNnmPVWS6Vu+F/gw1RjARB7IFKpbINyw6+20e2Z0GpWGcYhjiOT6D4BGwa9khrrVhsL7if4DbTGnVuQcSkmdzVnmJxbatSDuzzjqKoZMY9BRv3coLGXQ7HSn2qVqubaA0Bl8H9sGsXptZt8lH7CvZeoEnBPmBvRRw+cQiew4YZJI7B/jQFsQ101+DnkXu0xQYdOBPfwY8wrrEN+TvBz+EQ7yAO/nGdJFvIR6+LWE/w/CzsmAA0mCNBbhK4IVidGjn8K4h8ybn+/v51qDOldbKP17FtsOcI3Rz8QlZOpqsRpFJBbtxMr47HE1mOwip9o37jrrtsPh7NWKzimtk3WCqV1iD+BbabOFyPgZ+1dRaEFSRMaJwEJWbsFmj8kPgwiqokKI4VPf6ziU4GkkQP0NlBWif8GfjraQ+udyD6pjgcl/MfWeqhyKQkCNx9vE11XLfD9sD+Up753pBdohK4HsLe07jeg42CWsHrNCFMovXIsvwLaqx9QdSgjsPbZzm3ZgbuBBwqXbAACcIhfcJSLH/XTGKrwz8gQfjydktKeH0OQRfzWFQSRMC4r1NjmE6ZdBPlEh/kfH0FLYHIZihHEJo/bTEpwJ0ygnY5+W8wubf+XebAhL0sjzBIBelnbhyT2IDYL1xPWq5Wq60ENwvuPM9twC1gKc4LORn09fauQoN52OtASE/Sn5ZpuJ20hpAzeJs+gu/ykhdEnirjoyj9V3lnxNTp8OI78RX+VLHYk/lB1FrvBz+qGodc3cDbtbEZzHscHnii4PsVBNWen6W8iEc4PZkvpOag/cwUpqO3zSOWgiWoXjwnLyOPD/JCWVbOMRCCZlAOIVDe3oLMLeovgrZTpfptb24by1ZROIwcwoylGxQJL2jg1cxLdOClecTy4R/j1a7vFDLx5AAAAABJRU5ErkJggg==>
