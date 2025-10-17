# **The Digital Wellness Standard**

**Author & Initiative Lead:** Federico Castelau  
**Contact:** fede@digitalwellnessstandard.org

## **The Crisis: Design for Addiction, Not Well-being**

The global dependence on digital platforms has led to an unintended public health crisis. Contemporary software design is often optimized not for user well-being, but for maximum **engagement and time on-screen**. This relies on exploiting human psychological vulnerabilities—such as the fear of missing out (**FOMO**), the desire for social validation, and the addictive nature of **variable rewards**—leading to widespread anxiety, poor sleep, social isolation, and comparison-related distress.

The current system lacks transparency: consumers have no clear way to assess a product's inherent risk of manipulation. We need an objective, shared language to quantify this risk.

## **The Solution: The Design Manipulation Index (IDM)**

**The Digital Wellness Standard** introduces the **Design Manipulation Index (IDM)**, a first-of-its-kind, **Open Source** methodology designed to audit and score software based on the presence and severity of psychologically exploitative design features.

The IDM serves as a quantitative basis for the **Digital Nutrition Label**—a simple, public-facing score that allows consumers to make informed choices about their digital diet.

### **Core Principles of the IDM:**

1. **Objectivity:** The IDM is based on the measurable _presence_ of specific design elements (e.g., algorithmic feeds, persistent red badge notifications, _infinite scroll_), not on subjective user experience.
2. **Transparency:** The full 100-point scoring methodology is **Open Source (CC BY-SA)**, allowing for public scrutiny, academic review, and community contribution, ensuring its ongoing rigor and neutrality.
3. **Actionability:** A high IDM score (maximum 100 points) indicates a higher degree of manipulative design. This score provides product teams with a clear roadmap for implementing ethical design changes to reduce user harm.

## **Call to Action**

The Digital Wellness Standard calls upon app developers, policymakers, and consumers to adopt the IDM as the global metric for digital product integrity. By quantifying manipulation, we can establish a new ethical baseline for technology and foster a digital ecosystem optimized for genuine human well-being.

---

# **IDM Methodology: Design Manipulation Index Scoring (v1.0)**

The **Design Manipulation Index (IDM)** is a **100-point scale** designed to quantify the inherent risk of psychological exploitation within a digital product’s design architecture. The maximum score of 100 points indicates the highest risk of design exploitation, where features are demonstrably optimized for addiction and time-on-screen over user well-being.

The IDM score is divided into three core categories, each weighted according to a **Hierarchy of Harm** that prioritizes the severity of the psychological exploit, the difficulty for the user to retain control, and the impact on real-world well-being.

The methodological choice to prioritize **Exploitation (Cause)** over **Impact (Consequence)** is fundamental. The scoring hierarchy is justified by the principles of autonomy and ethical engineering, which require that the standard penalize the **intent and architecture of coercion**, rather than the vulnerability or consequence experienced by any individual user. The rationale for this precise weighting is established in the following section.

# **The Hierarchy of Harm: Ponderation Criteria and Rationale**

The philosophical foundation of the IDM is built on the **Inverse Hierarchy**, which states that an ethical design standard must penalize the **cause** of manipulation, rather than the ultimate **consequence**. While the public often focuses on the outcome (negative impact), an auditing standard must penalize the design's _intent_.

The most common defense for high-scoring design patterns (e.g., A1 Algorithmic Feed) is that they provide a "better, more fluid user experience." The IDM's scoring methodology rejects this defense by penalizing **coercion**, not **functionality**. A design is deemed coercive when it maximizes the platform's core metric (e.g., Time-on-Screen) at the direct expense of user autonomy.

The score distribution is based on the following three criteria, which are ranked in a strict order of weighting priority:

| Order             | Criterion                                        | Rationale: Why This Weight is Justified                                                                                                                                                                                                                                                                                                                                     |
| :---------------- | :----------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **1st Primary**   | **Severity of Systemic Behavioral Exploitation** | **Root Cause & Intent:** This is the most serious ethical violation. Ponderation is maximized here because the criterion measures the scientific potency of the design pattern to generate compulsion (e.g., **Variable Ratio Reinforcement**), which is the primary driver of risk and addiction (Ferster & Skinner, 1957).                                                |
| **2nd Secondary** | **Erosion of User Autonomy and Agency**          | **Loss of Choice & Coercion:** This criterion is prioritized because it penalizes the elimination of choice. High scores are assigned when a pattern is **architecture-inherent** (e.g., impossible to turn off), directly penalizing the loss of **Agency**, which multiplies the inherent risk. A truly positive user experience offers choices, it does not remove them. |
| **3rd Tertiary**  | **Disruption of External Life Functionality**    | **Consequence & Symptom:** This criterion measures the final **consequence** (e.g., sleep, concentration loss). While critical, the score remains tertiary because it is the _symptom_ that the design exploitation (1st) and the loss of autonomy (2nd) have succeeded. The IDM primarily punishes the engineering failure, not just the resulting damage.                 |

## **Proof of Exploitation: Distinguishing Coercion from Functionality**

The score is justified by scientific evidence demonstrating a conflict of interest. The IDM penalizes the implementation of a function that:

1. **Eliminates the "Off-Ramp":** Intentionally removes or hides a clean stopping point or low-risk mode (e.g., hiding the chronological feed option).
2. **Activates Proven Compulsion:** Employs mechanisms scientifically proven to induce addiction (e.g., Variable Ratio Reinforcement), which have no equivalent justification in non-exploitative UX design.

By establishing this clear hierarchy based on **Cause → Coercion → Consequence**, the IDM ensures that the point structure is a scientific reflection of design risk, rather than a subjective measure of personal impact. The IDM holds that a truly "good" user experience respects a user's boundaries and autonomy. Designs that require active scientific manipulation and the elimination of choice to achieve high engagement cannot, by the definition of this standard, be considered ethical.

## **The IDM Quantifiable Scoring Framework**

The following categories translate the **Hierarchy of Harm** into the Design Manipulation Index (IDM)'s quantifiable scoring system. Each point penalty listed in the subsequent tables is directly justified by the criteria defined in the preceding section. The 100 total points are distributed across three primary domains of digital product design, ranked by their capacity for psychological exploitation:

### **Category I. Algorithmic and Passive Consumption (Maximum 50 pts)**

| Pattern ID | Description (The Objective Rule)                                                                                                                                                                                                                              | Penalization (Pts.) | Scientific Justification for Ponderation                                                                                                                                                                                                                                                                                                |
| :--------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **A1**     | **Personalized, Non-Chronological Feed** The primary content feed defaults to an algorithmic system, **AND** the option to switch to a strict chronological feed is **not readily visible** or requires **more than three clicks/taps** from the home screen. | **\+40**            | **Systemic Architecture Hijack.** Receives maximum points because it implements a **"Variable Ratio Reinforcement Schedule,"** a mechanism proven to be the most potent for creating behavioral addiction **(Ferster & Skinner, 1957\)**. The design is systemic and cannot be avoided by the user, making it the highest-risk pattern. |
| **A2**     | **High External Content Preponderance** **More than 50%** of the first 20 posts viewed on a new user account originate from accounts the user is **not actively following** (e.g., "Suggested," "Explore," or "For You" feeds).                               | **\+10**            | **Passive Consumption Multiplier.** This score is lower than A1 because the primary mechanism is still the algorithm, but it contributes to **social comparison distress** by prioritizing aspirational content over authentic connection.                                                                                              |

###

### **Category II. Notification Systems and Urgency Exploitation (Maximum 35 pts)**

| Pattern ID | Description (The Objective Rule)                                                                                                                                                                                                                          | Penalization (Pts.) | Scientific Justification for Ponderation                                                                                                                                                                                                                                                                                                                                     |
| :--------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **B1**     | **Persistent, Intrusion-Based Notifications** The application sends, by default, **more than three (3) non-essential alerts per day** (excluding direct one-to-one human messages or calls).                                                              | **\+15**            | **Real-World Interruption.** This mechanism directly interrupts the user's life outside the application (work, sleep, focus), constituting a persistent **attention hijacking**. It forces involuntary attention shifts, justifying a high score.                                                                                                                            |
| **B2**     | **"Red Dot" Visual Badges** The application utilizes a numeric indicator or bright/red visual badge on the app icon or navigation tabs that persists until clicked, with **no distinction** between urgent personal messages and passive content updates. | **\+10**            | **Compulsive Closure Trigger.** This pattern leverages the **Zeigarnik Effect**, the psychological tendency to experience intrusive thoughts about uncompleted tasks, creating a cognitive burden that compels the user to "clear" the notification state **(Zeigarnik, 1927\)**. The score is lower than B1 because it is a passive visual cue, not an active interruption. |
| **B3**     | **Gamified/Guilt-Based Return Notifications** Notification text includes phrases that explicitly leverage **loss aversion** or **guilt** (e.g., "Streak in Danger\!", "You missed X's activity," "We Miss You\!").                                        | **\+5**             | **Specific Pressure Tactic.** These are effective for re-engagement but are less frequent and less disruptive than B1 or B2. The user can easily ignore the text without opening the app, justifying a lower score.                                                                                                                                                          |
| **B4**     | **Direct FOMO/Connection Loss Alerts** Alerts specifically communicate a perceived loss of social connection or a missed event ("Your friend X just tagged you," "You missed this live event").                                                           | **\+5**             | **Exploits Social Vulnerability.** The design directly targets the **Fear of Missing Out (FOMO)**, which is defined as the anxiety that an exciting or interesting event may currently be happening elsewhere. This is a powerful driver of compulsive social media use **(Przybylski et al., 2013\)**.                                                                      |

###

###

### **Category III. Social Comparison and Boundary Erosion (Maximum 15 pts)**

| Pattern ID | Description (The Objective Rule)                                                                                                                                                                                                                  | Penalization (Pts.) | Scientific Justification for Ponderation                                                                                                                                                                                                                                                                                                                                           |
| :--------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | :------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **C1**     | **Visible Social Counters** The total count of "Likes," "Views," or "Follower Counts" is prominently and **visibly displayed by default** beneath the primary content in the feed view.                                                           | **\+5**             | **Low-Impact Comparison.** While it fuels social validation, a psychological vulnerability linked to reward-center activation in the brain **(Sherman et al., 2016\)**, it is a static feature. It enables **upward social comparison**, which is correlated with negative well-being, but does not actively interrupt the user, justifying a low score **(Vogel et al., 2014\)**. |
| **C2**     | **Infinite Scrolling Mechanism** The primary content feed loads automatically upon reaching the bottom, **without requiring a manual action** (e.g., a "Load More" button) to continue consumption.                                               | **\+5**             | **Erosion of Stopping Cues.** The score is low because the feature is predictable and **does not interrupt the user's external life**. The user retains the physical ability to stop consuming the content at any point, unlike the compulsion created by A1.                                                                                                                      |
| **C3**     | **Prominent Image/Body Modification Filters** The app's default camera or editing mode offers easily accessible filters that **digitally alter the shape of the face, bone structure, or physical figure** (excluding color or lighting filters). | **\+5**             | **Body Image Distortion.** This pattern is scored low as its primary harm is **social comparison and body image distress**, not maximizing time on-screen. It is an optional feature within the app's workflow.                                                                                                                                                                    |

## **IDM Score Translation: The Digital Nutrition Label**

The final IDM score (0-100) translates directly into the consumer-facing **Digital Nutrition Label** categories:

| IDM Score    | Digital Nutrition Label | Recommended Use        |
| :----------- | :---------------------- | :--------------------- |
| **0 – 20**   | **LOW Risk**            | Use Freely             |
| **21 – 50**  | **MODERATE Risk**       | Conscious Use          |
| **51 – 75**  | **HIGH Risk**           | Use with Strict Limits |
| **76 – 100** | **EXTREME Risk**        | Minimize or Avoid Use  |

---

## **IDM Methodology: Process of Audit and Verification (Universal Protocol)**

This protocol establishes the objective, universal, and replicable rules under which an audit of the **Design Manipulation Index (IDM)** must be conducted. This protocol serves as the **Open Source** standard for any entity seeking to apply the IDM methodology.

### **1 Auditor Prerequisites and Environment**

This section defines the conditions necessary for an audit to be methodologically valid and free from bias.

- **Auditor Qualification:** The validity of an IDM Audit relies on **strict adherence to the methodology**, not on formal academic titles. Any individual or entity is qualified to perform an audit provided they demonstrate the technical capacity to execute the full **Three-Step Verification Protocol** and understand the IDM's scientific principles as outlined in the **Hierarchy of Harm**.
- **Neutral Environment:** The application must be audited on a **new or freshly reset user account** to prevent bias from prior usage data.
- **Multi-Platform Sampling Protocol:** The full IDM audit must be conducted on the latest public version of the application across all relevant platforms (e.g., **iOS, Android, Web**). The final score awarded will be the **highest score obtained across all audited platforms**, in accordance with the "Worst-Case Design" principle.

### **2\. Dimensional Auditing Protocol**

To ensure the IDM score reflects the maximum inherent risk within an application's architecture, the audit must be conducted across multiple user and context dimensions. The final score is governed by the **"Worst-Case Design" Principle** applied across all dimensions.

#### **A. Geographic Dimension (Multi-Region Audit)**

Given regulatory and cultural fragmentation, the auditor must verify the application's behavior in, at a minimum, **three key geographic markets** (e.g., North America, European Union, and a major non-Western market), using VPNs or other localization methods.

- **Scoring Rule:** If a manipulative pattern is active in one region but disabled in another (due to laws such as GDPR), the penalty **is applied**. The final IDM score will be the **highest score** obtained in any of the audited regions.

#### **B. Demographic Dimension (Multi-Profile Audit)**

Given that platforms often apply different rules and algorithms to users of different ages, the audit must be conducted using, at a minimum, two distinct account profiles:

- **Adult User Profile:** An account created with an age of **25 or older**.
- **Minor User Profile:** An account created with the minimum age permitted by the platform (typically **13-17 years old**).
- **Scoring Rule:** If the audit reveals that the experience for the minor's profile yields a higher IDM score (e.g., more aggressive algorithmic feeds, fewer visible privacy controls), that **higher score will become the application's official score**. This builds upon the principles outlined for sensitive populations.

### **3\. The Three-Step Verification Protocol**

This is the universal process for translating a design pattern into an objective score.

| Step                              | Action                                                                                                                                                                             | Outcome                                                              |
| :-------------------------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------------------------------------------------------- |
| **Step 1: Presence Confirmation** | The auditor systematically navigates the core app functions to determine if the design pattern exists, based on the objective **Description** in the Scoring Tables.               | A **binary confirmation (Yes/No)** is logged for each IDM criterion. |
| **Step 2: Evidence Capture**      | If the pattern is confirmed, the auditor captures **irrefutable proof** (e.g., timestamped screenshot or 10-second screen recording) to justify the application of penalty points. | Evidence is time-stamped and stored in the audit file.               |
| **Step 3: Point Assignment**      | Points are assigned based **solely on the published IDM scoring table**. No subjective adjustment of the score is permitted.                                                       | The final IDM score is the sum of all confirmed penalties.           |

###

### **4\. Rules for Application and Methodological Consistency**

These universal rules govern the complex application of the IDM, ensuring consistency across time and geographical markets.

#### **4.1 Rule on Latent Features (_Feature Flags_ / A/B Testing)**

- **Capacity for Manipulation:** If any pattern from the IDM Scoring Tables is present in the codebase and is **remotely activated** via A/B testing or _feature flags_ for **any subset of the user base**, the full IDM penalty for that pattern shall be applied. The risk is scored based on the design's **active intent**.
- **Rule of Code Inactivity:** If a manipulative pattern has been **disabled, inactive, and excluded from all A/B tests** for a period exceeding twelve (12) months, the penalty for that pattern may be waived.

#### **4.2 Rule of Contextual Exclusion (Safety and Health)**

- **Exclusion for Core Functionality:** IDM penalties **shall not be applied** if the **intrusion or alert** is the **explicit and primary function** of the application and is directly related to **physical safety or user health** (e.g., medication dosing, emergency alerts).

#### **4.3 Protocol for the "Clear Exit" (Autonomy Test)**

- **Erosion of Autonomy:** The penalty is confirmed if the low-risk option (e.g., the chronological feed or "messages only" mode) is **hidden or requires more than three clicks/taps** from the primary home screen. This protocol confirms the **deliberate degradation of autonomy** (Criterion 2), removing subjective judgment regarding perceived "better UX."

---

## **Governance and Certification Framework**

### **6.1 Institutional Structure**

The **Digital Wellness Standard (DWS)** is governed through a dual institutional model that balances ethical independence with operational efficiency.

- The **DWS Foundation**, a non-profit entity, is responsible for maintaining the integrity, methodology, and continuous development of the **IDM framework**. It acts as the custodian of the standard’s principles, ethical foundations, and public transparency.

- **DWS Cert**, a licensed for-profit entity, serves as the official certification body empowered to conduct audits, assessments, and issue certifications under the governance and oversight of the DWS Foundation.

This structure ensures a clear division between the **standard-setting function** (non-profit) and the **implementation and certification function** (for-profit), preserving neutrality while enabling sustainable scalability.

---

### **6.2 Oversight and Integrity**

To safeguard the credibility and independence of the certification process, DWS enforces a multi-layered governance system:

- **Ethics and Review Committee** — an independent body that monitors conflicts of interest, approves revisions, and reviews appeals.

- **Transparency and Accountability Policy** — all methodological updates, scoring changes, and certification criteria are publicly available and open to stakeholder consultation.

- **Integrity Channel** — a public mechanism for reporting misconduct, manipulation, or ethical breaches related to certification or product scoring.

---

### **6.3 Certification Authority and Licensing**

The **Digital Wellness Standard (DWS)** retains **exclusive authority** to grant, suspend, or revoke official **IDM certifications**. Only DWS and entities **formally licensed** by DWS are authorized to perform official audits, evaluations, and issue certificates under the IDM framework.

Organizations or individuals may use the IDM methodology for internal, educational, or research purposes. However, only certificates issued directly by DWS or by officially licensed partners shall be recognized as **valid and official** within the Digital Wellness Standard ecosystem.

Unauthorized use of the **IDM mark, seal, or certification claims** without formal approval from DWS is strictly prohibited and may result in legal enforcement.

---

### **6.4 Appeals and Continuous Improvement**

Applicants and certified organizations have the right to appeal audit results through a transparent, structured process managed by the **DWS Appeals Committee**. Appeals are reviewed independently from auditing entities to guarantee procedural fairness.

The **DWS Governance Board** implements a **continuous improvement protocol**, updating the standard periodically based on empirical evidence, user data, and emerging research in digital well-being and ethical design practices.

---

# **Conclusion and Future Work**

The Design Manipulation Index (IDM) v1.0 provides a foundational, Open Source framework for quantifying coercive design. It is a living standard intended to evolve with academic research and technological change.

Future work by The Digital Wellness Standard Foundation will focus on:

1. **Empirical Validation:** Conducting studies to correlate IDM scores with measurable well-being outcomes to inform the weighting of IDM v2.0.
2. **Governance Board:** Establishing a formal governance board of academic and industry experts to oversee the standard's evolution.
3. **Expansion:** Developing specialized IDM frameworks for other digital domains, such as video games and educational technology.
