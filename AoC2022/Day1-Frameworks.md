
# History 
"McSkidy looked at the puzzle and recognised some of the pieces as the phases of the *Unified Kill Chain, a security framework used to understand attackers."


> EN: **Security frameworks** are documented processes that define policies and procedures organisations should follow to establish and manage security controls. They are blueprints for identifying and managing the risks they may face and the weaknesses in place that may lead to an attack. 

> PL: Frameworki bezpieczeństwa to udokumentowane procesy określające polityki i procedury, które organizacje powinny stosować w celu ustanowienia i zarządzania środkami kontroli bezpieczeństwa. Są to plany identyfikacji i zarządzania ryzykiem, na które mogą być narażone oraz słabościami, które mogą doprowadzić do ataku.

# Additional rooms from THM in this TOPIC

1. [MITRE room](https://tryhackme.com/room/mitre).
2. [Cyber Kill Chain room](https://tryhackme.com/room/cyberkillchainzmt).
3. [Unified Kill Chain](https://tryhackme.com/room/unifiedkillchain)
4. [Cyber Defence Frameworks module](https://tryhackme.com/module/cyber-defence-frameworks)

 Unified Kill Chain, Cyber Kill Chain, MITRE, or the whole Cyber Defence Frameworks module

# Security Frameworks - theory

## NIST Cybersecurity Framework - https://www.nist.gov/cyberframework ; https://www.nist.gov/cyberframework/framework-documents

The Cybersecurity Framework (**CSF**) was developed by the National Institute of Standards and Technology (**NIST**), and it provides detailed guidance for organisations to manage and reduce cybersecurity risk. The framework focuses on five essential functions: `**Identify**` -> `**Protect**` -> `**Detect**` -> `**Respond**` -> `**Recover.**` With these functions, the framework allows organisations to prioritise their cybersecurity investments and engage in continuous improvement towards a target cybersecurity profile.

## Documents: 

>PDF English: https://doi.org/10.6028/NIST.CSWP.04162018
>PDF Polish: https://doi.org/10.6028/NIST.CSWP.02122014pl%20
>Excel English: https://www.nist.gov/document/2018-04-16frameworkv11core1xlsx

## Video: 

![obraz](https://user-images.githubusercontent.com/90008283/205144563-3cc1b543-d634-4654-9f1e-29a188362301.png)

>Cybersecurity ramework Version 1.1  https://www.nist.gov/cyberframework/getting-started
>The Cybersecurity Framework https://www.nist.gov/cyberframework/getting-started

## In brief: 

Source: https://scasecurity.com/blog/nist-security-framework/

### 1. Identify 

Organizations must first fully **understand** their **current environment** to ensure they can successfully manage arising cybersecurity threats at various levels, **including data, systems, and assets.** Conducting a NIST Cybersecurity Framework assessment will help identify your risks within your industry or business context.


-   **Business environment** – Establish the organization’s mission, objectives (*założenie*) , general activities, and stakeholders (interesariuszy) .
-   **Asset management** – Identify devices, data, personal, facilities (*obiekty*) , and systems used to conduct (*wykorzystywaych*) the core company purposes.
-   **Governance** – The procedures, processes, and policies necessary to manage and monitor the company’s risk, legal, operational and regulatory needs.
-   **Risk assessment** – Understanding the specific cybersecurity risks that may face organizational assets, operations, and employees.
-   **Risk management plan** – Establishing a company’s risk tolerances, priorities, and constraints (*ograniczenia*) , and using that data to support critical operational decisions.

### 2.Protect: 

Once organizations have a better understanding of their cybersecurity risks, they can evaluate (*ocenić*) whether their cybersecurity safeguards (*zabezpieczenia*) offer sufficient protection, or if changes or additional controls are appropriate to ensure delivery of services. Hence, the NIST Cybersecurity Framework’s protect domain underpins (*stanowić podstawę*) the capability (*zdolnośc*) to contain (*do powstrzymania*) or limit any impacts arising from cybersecurity events.

-   **Access Control** – Limit access to your network and assets to ensure users have the least access possible they need to do their job roles.
-   **Training and awareness** – Provide sufficient (*wystarczające*) training and cybersecurity awareness to empower your team members to perform their responsibilities in alignment with your company’s [**information security compliance**](https://scasecurity.com/compliance/) policies and procedures.
-   **Data security** – Managing the organization’s critical data based on your [**risk assessment**](https://scasecurity.com/security/risk-assessment/) strategy designed to safeguard the confidentiality, availability, and integrity of critical data.
-   **Information protection procedures and processes** – The processes, policies, and methods used to protect the company’s information systems and assets effectively.
-   **Maintenance** (*konserwacja*) – Includes repairs of the information system elements done based on the company’s procedures and policies.
-   **Protective technology** – Using a mix of automated and manual tools to guarantee optimal information security and better resilience (*odporność*)


### 3. Detect 

Speed is critical in threat mitigation (zagrożenia) . The detection part of the NIST Cybersecurity Framework defines the essential processes necessary to identify cybersecurity events. Timely detection is crucial as it allows the proper response to be initiated.

-   Detecting any anomalies – Ensuring all events or anomalies are quickly detected
-   Continuous monitoring – Tracking your information and assets constantly to detect cybersecurity events rapidly
-   Detection processes – Maintain your detection processes to guarantee their availability and reliability to detect any anomalies

### 4. Respond 

The NIST Cybersecurity Framework also includes the response domain (*domna reagowania*)  that involves boosting the capacity of containing the adverse effects of cybersecurity events. It consists of all activities used by an organization once cybersecurity threats or incidents are detected.

-   Response planning – Ensure timely response using properly executed procedures and processes.
-   Communication – Covers (*obejmuje*) response activities related to communication between external and internal stakeholders
-   Analysis – Includes the reviews done while response actions are underway (*w trakcie realizacji*) to make sure correct procedures are followed
-   Risk mitigation – The activities that prevent the cybersecurity event from expanding while eradicating or neutralizing its effects
-   Improvements – Every time an organization deals with response activities, it presents new opportunities for strengthening the process by reviewing the lessons learned (*przegląd wycięgniętych wniosków*) and making improvements.

### 5. Recovery

This domain of the NIST Cybersecurity Framework allows you to highlight the best processes to achieve business resilience. It seeks to quickly restore impaired services, capabilities, and capacities to ensure everything is working as intended.

-   Recovery planning – Organizing recovery procedures based on priority.
-   Improvements – Review of events and response to update the recovery strategy.
-   Communication – Coordinating communication with all stakeholders to ensure the successful restoration (przywrócenia) of services.

## ISO 27000 Series

The International Organization of Standardization (**ISO**) develops a series of frameworks for different industries and sectors. The ISO **27001** and 27002 **standards** are commonly known for cybersecurity and outline (zarys) the requirements and procedures for creating, implementing and managing an information security management system (**ISMS**). These standards can be used to assess (*assess*) an institution’s ability to meet set information security requirements through the application of risk management.

## MITRE ATT&CK Framework

Identifying adversary plans of attack can be challenging to embark (*podjąć*) on blindly. They can be understood through the behaviours, methods, tools and strategies established for an attack, commonly known as **T****actics**, **Techniques** and **Procedures** (TTPs). The MITRE ATT&CK framework is a knowledge base of TTPs, carefully curated (*zapewnić*) and detailed to ensure security teams can identify attack patterns. The framework’s structure is similar to a periodic table, mapping techniques against phases of the attack chain and referencing system platforms exploited. 

This framework highlights the detailed approach it provides when looking at an attack. It brings together environment-specific cybersecurity information to provide cyber threat intelligence insights that help teams develop effective security programs for their organisations. Dive further into the framework by checking out the dedicated [MITRE room](https://tryhackme.com/room/mitre).

https://mitre-attack.github.io/attack-navigator//#layerURL=https%3A%2F%2Fattack.mitre.org%2Fgroups%2FG0008%2FG0008-enterprise-layer.json

[![[t3-attack-navigator.png]]](https://www.trellix.com/en-us/img/security-awareness/mitre-attack-cloud.png)


## Cyber Kill Chain

A key concept of this framework was adopted from the military with the terminology **kill chain**, which describes the structure of an attack and consists of target identification, decision and order to attack the target, and finally, target destruction. Developed by Lockheed Martin, the cyber kill chain describes the stages commonly followed by cyber attacks and security defenders can use the framework as part of intelligence-driven defence.

There are seven stages outlined by the Cyber Kill Chain, enhancing visibility and understanding of an adversary’s tactics, techniques and procedures.

[![[1e0cdd3b3f3c33c18d67f25aad84e618.png]]](https://www.trellix.com/en-us/img/security-awareness/mitre-attack-cloud.png)

Dive further into the kill chain by checking out the dedicated [Cyber Kill Chain room](https://tryhackme.com/room/cyberkillchainzmt).

## Unified Kill Chain

The Unified Kill Chain (UKC) can be described as the unification (*ujednoliczenie*) of the MITRE ATT&CK and Cyber Kill Chain frameworks. Published by Paul Pols in 2017 (and reviewed in 2022), the UKC provides a model to defend against cyber attacks from the adversary’s perspective. The UKC offers security teams a blueprint for analysing and comparing threat intelligence concerning the adversarial mode of working.

The Unified Kill Chain describes** 18 phases** of attack based on Tactics, Techniques and Procedures (TTPs). The individual phases can be combined to form overarching goals, such as gaining an initial foothold in a targeted network, navigating through the network to expand access and performing actions on critical assets.


#### CYCLE 1: In

The main focus of this series of phases is for an attacker to gain access to a system or networked environment. Typically, cyber-attacks are initiated by an external attacker. The critical steps they would follow are:

-   **Reconnaissance**: The attacker performs research on the target using publicly available information.
-   **Weaponisation**: Setting up the needed infrastructure to host the command and control centre (C2) is crucial in executing attacks.
-   **Delivery**: Payloads are malicious instruments delivered to the target through numerous means, such as email phishing and supply chain attacks.
-   **Social Engineering**: The attacker will trick their target into performing untrusted and unsafe action against the payload they just delivered, often making their message appear to come from a trusted in-house source.
-   **Exploitation**: If the attacker finds an existing vulnerability, a software or hardware weakness, in the network assets, they may use this to trigger their payload.
-   **Persistence** (*Trwałość*) : The attacker will leave behind a fallback (*awaryjna*) presence on the network or asset to make sure they have a point of access to their target.
-   **Defence Evasion**: The attacker must remain anonymous throughout their exploits by disabling and avoiding any security defence mechanisms enabled, including deleting evidence of their presence.
-   **Command & Control**: Remember the infrastructure that the attacker prepared? A communication channel between the compromised system and the attacker’s infrastructure is established across the internet.


This phase may be considered a loop as the attacker may be forced to change tactics or modify techniques if one fails to provide an entrance into the network.


#### CYCLE 2: Through  (*poprzez*)

Under this phase, attackers will be interested in gaining more access and privileges to assets within the network.
The attacker may repeat this phase until the desired access is obtained.

-    **Pivoting**: Remember the system that the attacker may use for persistence? This system will become the attack launchpad (*"trampolina"*) for other systems in the network 
-   **Discovery**: The attacker will seek to gather as much information about the compromised system, such as available users and data. Alternatively, they may remotely discover vulnerabilities and assets within the network. This opens the way for the next phase.
-   **Privilege Escalation**: Restricted access prevents the attacker from executing their mission. Therefore, they will seek higher privileges on the compromised systems by exploiting identified vulnerabilities or misconfigurations.
-   **Execution**: With elevated privileges, malicious code may be downloaded and executed to extract sensitive information or cause further havoc (*spustoszenie*) on the system.
-   **Credential Access**: Part of the extracted sensitive information would include login credentials stored in the hard disk or memory. This provides the attacker with more firepower for their attacks.
-   **Lateral Movement**: Using the extracted credentials, the attacker may move around different systems or data storages within the network, for example, within a single department.


#### CYCLE 3: Out


The Confidentiality, Integrity and Availability (CIA) of assets or services are compromised during this phase. Money, fame or sabotage will drive attackers to undertake (podejmować) their reasons for executing their attacks, cause as much damage as possible and disappear without being detected.

-   **Collection**: After finding the jackpot of data (*pula danych*) and information, the attacker will seek to aggregate all they need. By doing so, the assets’ confidentiality would be compromised entirely, especially when dealing with trade secrets and financial or personally identifiable information (PII) that is to be secured.
-   **Exfiltration**: The attacker must get his loot out of the network. Various techniques may be used to ensure they have achieved their objectives without triggering suspicion.
-   **Impact**: When compromising the availability or integrity of an asset or information, the attacker will use all the acquired privileges to manipulate, interrupt and sabotage. Imagine the reputation, financial and social damage an organisation would have to recover from.
-   **Objectives**: Attackers may have other goals to achieve that may affect the social or technical landscape that their targets operate within. Defining and understanding these objectives tends to help security teams familiarise themselves with adversarial attack tools and conduct risk assessments to defend their assets.


# Saving The Best Festival Company Practise



Having gone through the UKC with Santa’s security team, it is evident that better defensive strategies must be implemented to raise resilience against attacks.

Your task is to help the Elves solve a puzzle left for them to identify who is trying to stop Christmas. Click the **View Site** button at the top of the task to launch the static site in split view. You may have to open the static site on a new window and zoom in for a clearer view of the puzzle pieces.

![obraz](https://user-images.githubusercontent.com/90008283/205156714-a4f754bf-c204-4080-8156-03618d11ba10.png)

 Hello Santa. For years, you have delivered happiness and joy to millions around the world during the festivities. However, you have remained untested and the time has finally arrived to turn the Best Festival Company into Grumpy and Miserable. I have taken over your website and warehouse, and it is time to turn Christmas into Chaos.

So, want to play a game to know who is behind all the misery? 

### Cykle:  IN

![obraz](https://user-images.githubusercontent.com/90008283/205157129-0c9e1be6-680a-4363-90f8-be359e16aa6f.png)

### Cykle: Through

![obraz](https://user-images.githubusercontent.com/90008283/205157355-54d9d3a7-6174-492f-96eb-9f8a0b898526.png)

### Cykle: Out

![obraz](https://user-images.githubusercontent.com/90008283/205157602-d32ffd1e-00ce-43df-a7a6-d8072bdfb577.png)

### Flaga + ![obraz](https://user-images.githubusercontent.com/90008283/205157946-c24f31cd-daed-4e7c-8cf4-b216ee9e761e.png)

![obraz](https://user-images.githubusercontent.com/90008283/205157858-2a1f7dd0-53ec-43a7-9536-b020fac5bb60.png)








