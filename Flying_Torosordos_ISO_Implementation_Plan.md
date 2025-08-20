# **Flying Torosordos: Information Security Management System (ISMS) Implementation Plan**

### **Project Overview**

This document outlines a strategic plan for **Flying Torosordos** to establish an **Information Security Management System (ISMS)** in alignment with **ISO 27001**. Given the company’s global presence with projects on four different continents, adopting a globally recognized standard is a strategic priority. This plan identifies key security gaps and maps them to specific ISO 27002 controls to build a robust and compliant security program.

### **1\. Context of the Organization (ISO 27001, Clause 4\)**

Flying Torosordos is a tech startup developing a sign language project management platform. The company operates globally but is housed within a larger company, which dictates its use of a public Wi-Fi network. This unique operational environment, combined with its mission to support the Deaf community, requires a security program that is both robust and flexible.

### **2\. Current Security Posture and Risk Assessment**

A balanced analysis of the company's security posture reveals both key strengths and significant vulnerabilities. This assessment guides the selection of controls for the ISMS.

#### **Security Strengths**

* **Robust Asset Security System:** The company has a strong asset security system with established backups that follow industry standards. This is a critical strength for disaster recovery and business continuity.  
* **Strong Financial Controls:** The company has strong internal financial controls, including the segregation of duties, which is in compliance with ISO 27001 requirements.  
* **Asset Inventory:** The company maintains a living, active inventory of all assets, a foundational component of an effective ISMS.

#### **Security Gaps and Risks**

* **Physical Access:** The lack of controlled access to the office space is a major physical security vulnerability that exposes assets to unauthorized personnel.  
* **Data Integrity:** The database is not implemented with a least privilege policy, allowing for untracked and unauthorized changes, which poses a significant risk to data integrity.  
* **Confidentiality:** Shared accounts and passwords, coupled with reliance on a public Wi-Fi network, create a high risk of data interception and account compromise.  
* **Hardware Failure:** The hard drives used for data storage are not housed in a secure, climate-controlled area, which increases the risk of premature hardware failure and data loss.  
* **Phishing Attacks:** The company is facing an increase in **spear-phishing** and **whaling** events, which are targeted attacks on employees and senior leadership. These threats pose a significant risk of credential compromise and data theft.

#### **Risk Prioritization Matrix**

The following matrix visually represents the severity of each identified risk.

| Risk Area | Likelihood | Impact | Priority |
| :---- | :---- | :---- | :---- |
| **Physical Access** | High | High | Critical |
| **Data Integrity** | High | High | Critical |
| **Confidentiality** | High | High | Critical |
| **Hardware Failure** | Medium | High | High |
| **Phishing Attacks** | High | High | Critical |

### **3\. Cyber-Threats Section**

A thorough analysis of the company’s security posture requires understanding the external threat landscape in addition to internal vulnerabilities. A company like Flying Torosordos, as a tech startup with a unique product, is a high-value target for various cyber threats.

* **Spear-Phishing & Whaling:** As already identified, the company faces an increased risk from targeted phishing attacks. Threat actors may target key personnel with the goal of gaining access to sensitive data or financial information.  
* **Intellectual Property Theft:** As a startup with a unique product, the company's intellectual property, including its software code, design files, and unique communication methods, is a prime target for theft. A breach could expose this data and compromise the company's competitive advantage.  
* **Software Supply Chain Attacks:** The company's reliance on a cloud-based platform and third-party contractors makes it vulnerable to a supply chain attack. An attacker could compromise a vendor's system and use it as a vector to gain access to the company's network.  
* **Malicious Insider Threats:** While internal controls are in place, a disgruntled employee or a threat actor who has gained access to the network could intentionally or unintentionally compromise data.

### **4\. Strategic Controls Implementation (Based on ISO 27002\)**

To mitigate the identified risks and achieve ISO 27001 certification, the following controls from ISO 27002 have been selected and implemented in a phased approach.

#### **Cost/Benefit Analysis**

The cost of implementing these security measures is a worthwhile investment given the high potential costs of a security incident. The cost of a data breach, intellectual property theft, or service disruption far outweighs the cost of the proposed controls.

* **Physical Controls:** A minor one-time investment with significant long-term security benefits.  
* **Technical Controls:** A small ongoing expense that provides a crucial layer of defense against a wide range of cyber threats.  
* **Policy & Training:** A minimal cost compared to the potential for human error to cause an incident.

#### **A. Physical and Environmental Security Controls**

* **A.7.1: Physical Security Perimeter:** The company has successfully negotiated a relocation to a more secure area within the larger building. The new location will have a restricted **physical security perimeter** with badged entry, with access limited to Flying Torosordos employees only.  
* **A.11.1: Secure Areas:** Within the office space, critical assets like servers and network equipment will be placed in a physically secure area with restricted access, and steps will be taken to ensure the area is **appropriately cooled to prevent hardware failure**.

#### **B. Access Control Controls**

* **A.8.2: User Access Management:** A formal process for user access has been established, including a semi-annual review of privileges. The database has been reconfigured with a **least privilege** policy, limiting editing permissions to two employees and restricting PII access to appropriate personnel.  
* **A.9.4: Access Control Policy:** A formal policy has been created to explicitly forbid account sharing. A **strong password policy has been implemented, and all employees are now required to use Multi-Factor Authentication (MFA)**.

#### **C. Human Resources and People Controls**

* **A.6.2: Security Awareness and Training:** A formal security training plan has been implemented to address the human element of security. This plan includes:  
  * **Asset Security:** Training on secure handling of company devices, proper data classification, and the importance of least privilege.  
  * **Physical Security:** A review of the new physical security perimeter and badged entry protocols.  
  * **Cyber Threat Awareness:** A comprehensive training module on identifying and responding to threats like phishing and social engineering.

#### **D. Cryptographic and Network Security Controls**

* **A.13.1: Network Security Management:** All internet traffic will be encrypted using a **VPN**. **Network segmentation** has also been implemented for each department to mitigate the risks of using public Wi-Fi. The company’s email system has been upgraded to an encrypted protocol with end-to-end encryption and zero trust.  
* **A.13.2: Information Transfer:** A formal policy for the secure transfer of data will be implemented.

### **5\. Continuous Improvement (ISO 27001, Clauses 9 & 10\)**

The ISMS is a continuous process of improvement, not a one-time project.

#### **Key Performance Indicators (KPIs)**

To measure the effectiveness of the implemented controls, the following KPIs have been established:

* **Access Control:** Track the number of unauthorized database changes and the time it takes to revoke access for terminated employees.  
* **Password Policy:** Monitor the percentage of employees using MFA and conduct regular audits for shared accounts.  
* **Security Training:** Track the completion rate for mandatory security training and the success rate of simulated phishing campaigns.

#### **Formal Audit Plan**

A formal audit plan has been established to ensure the continuous health and effectiveness of the ISMS. The plan includes:

* **Frequency:** Internal audits will be conducted semi-annually.  
* **Scope:** The audit will include a review of access logs, a check of physical controls, and an evaluation of adherence to new security policies.  
* **Reporting:** Audit results will be presented to management in a formal report that includes a risk assessment and recommendations for corrective actions.  
* **Management Review:** A management review of the ISMS will be conducted annually to ensure that the security program aligns with the company’s strategic objectives and business context.  
* **Corrective Actions:** Any nonconformities identified during audits or reviews will be addressed with a corrective action plan to continuously improve the ISMS.

### **6\. Strategic Transition to Cloud (Phased Approach)**

Flying Torosordos has made the strategic decision to transition to a fully cloud-based solution for scalability and secure storage. This will be implemented in a phased approach.

* **Immediate Action:** The company is currently negotiating with the larger company to install a dedicated, contained internet system. This is a critical first step to enabling a stable and secure connection for cloud migration.  
* **Phase 1: Cloud Migration:** Migrate all critical data and applications to a secure cloud platform. This will mitigate the risks associated with on-premises hardware and uncooled storage.  
* **Phase 2: Network Hardening:** Once a dedicated internet system is in place, implement a new network security policy that fully leverages the security features of the cloud platform.

### **7\. Additional Strategic Considerations**

To ensure the company's security program is fully mature and resilient, a comprehensive GRC strategy must also address the following:

#### **A. Business Continuity and Disaster Recovery (BCDR)**

* **Business Impact Analysis (BIA):** The company will conduct a formal BIA to identify and prioritize critical business functions and the impact of a disruption. This will inform the development of a comprehensive **Disaster Recovery Plan (DRP)**.  
* **Disaster Recovery Plan (DRP):** A detailed DRP will be developed, outlining procedures for restoring systems and data after a disaster, a communication plan for notifying employees and customers, and regular testing of the plan.

#### **B. Data Privacy and International Regulations**

* The company is actively working with local experts in each country of operation to identify all relevant privacy laws and regulations.  
* A comprehensive privacy policy will be developed and communicated to all employees and customers, outlining how data is collected, stored, and used. The policy will be designed to ensure compliance with all identified international regulations, including **GDPR** (for European operations) and **CCPA/CPRA** (for operations in California).

#### **C. Supply Chain Risk Management**

* A formal process will be established to vet all vendors and third-party suppliers, including a security questionnaire and a review of their own security practices.  
* Security and privacy clauses will be included in all vendor contracts to ensure they are held to the same high security standards as the company.  
* **Formal Vendor Onboarding Process:** To make the vendor vetting process more concrete and actionable, a formal onboarding procedure will be implemented for all new vendors and contractors. This process will include a security questionnaire to assess their security controls, their use of Multi-Factor Authentication (MFA), and their data handling practices.  
* **Security Questionnaire for New Vendors:**  
  * **Security Controls:** What security measures do you have in place to protect our data? (e.g., firewalls, encryption, intrusion detection systems).  
  * **Data Handling:** What are your data handling practices? How is our data stored, used, and transferred? Do you have a data retention policy?  
  * **Access Control:** Do you have a formal process for granting and revoking access? Is Multi-Factor Authentication (MFA) used for all critical accounts?  
  * **Incident Response:** Do you have an incident response plan? How would you notify us in the event of a security incident?

#### **D. Relocation and Operational Autonomy Analysis**

Flying Torosordos is exploring the possibility of moving off-campus to gain full autonomy over its security and operations. This analysis provides a comparison of the security and cost implications of staying versus relocating.

* **Cost Comparison**  
  * **Staying:** The primary benefit is the free office space. However, this comes with long-term hidden costs, including time spent negotiating for infrastructure access and potential productivity loss due to an unstable internet connection.  
  * **Relocating:** The initial costs of rent, utilities, and setting up a new office would be a significant financial burden. In the long run, however, the enhanced security and operational autonomy would likely lead to increased productivity and a more predictable operational environment.  
* **Security Comparison**  
  * **Staying:** The company's reliance on the larger company's public Wi-Fi is a major confidentiality risk. The lack of control over physical access and the inability to install a dedicated network are also critical security gaps.  
  * **Relocating:** Moving off-campus would allow the company to implement a full-fledged security program that aligns with its needs and industry standards. They could install a private network, a robust physical security perimeter, and ensure all critical assets are stored in a secure, climate-controlled area.  
* **Recommendation:** The strategic benefits of moving off-campus outweigh the short-term financial advantages of staying. The enhanced security and operational autonomy would allow the company to scale and grow in a much more predictable and resilient manner.

#### **E. Security Culture Program**

To build a strong security culture that goes beyond a single training session, a new program is proposed.

* **Communication:** A program for regular security newsletters or internal blog posts will highlight a security topic each month, keeping security top-of-mind for all employees.  
* **Gamification:** Small, fun activities or challenges will be suggested to reinforce security principles, such as a contest for reporting the most phishing emails.  
* **Reinforcement:** Security will be a regular topic of discussion in team meetings, with clear support and reinforcement from senior leadership.

### **8\. Skills Demonstrated**

This project showcases a range of advanced GRC skills:

* **ISO 27001 Framework:** The ability to design and implement a security program that aligns with a globally recognized standard.  
* **Gap Analysis & Risk Management:** The ability to identify, assess, and mitigate risks in a business context.  
* **Policy Development:** The ability to translate strategic security objectives into actionable policies and procedures.  
* **GRC and Compliance:** A deep understanding of how to achieve and maintain compliance with a major security standard.
