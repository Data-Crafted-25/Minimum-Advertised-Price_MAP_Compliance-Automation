# **Project Overview**

The Minimum Advertised Price (MAP) Policies Compliance System is a strategic initiative designed to protect brand integrity, ensure fair market competition, and enforce pricing discipline among resellers. This project aims to develop an automated, scalable, and intelligent system that monitors, detects, and enforces compliance with the client’s MAP policies across multiple online marketplaces.

Non-compliance with MAP policies can lead to significant risks, including price erosion, brand devaluation, and unfair competitive advantages for rogue resellers. To mitigate these risks, this system will proactively track advertised prices, identify violators—even when they operate under different names across platforms—and apply graduated enforcement actions, including warnings and category suspensions.

## **Business Problem**
Brand owners and manufacturers often establish Minimum Advertised Price (MAP) policies to maintain the perceived value of their products and prevent destructive price competition. However, enforcing these policies manually across numerous digital marketplaces is time-consuming, error-prone, and inefficient.

Currently, resellers may advertise products below the allowed threshold—specifically below the Lowest Possible Price (LPP), which is derived from the MAP—under different business names or storefronts on various platforms. Without a centralized system to link these identities and monitor pricing in real time, violations go undetected or are addressed too late, undermining brand equity and disadvantaging compliant partners.

This project addresses the need for:

- Automated monitoring of seller advertised prices (SAP) across e-commerce platforms.
- Accurate identification of resellers using name variations or alternate storefronts.
- Timely enforcement through standardized communication and corrective actions.
- A structured process to escalate consequences for repeated violations.

  ## **Project Objectives**
The primary objective of the MAP Compliance System is to automate the detection and enforcement of MAP policy violations, ensuring consistent adherence by all authorized resellers. 
Specific goals include:

- **Real-Time Price Monitoring**: Continuously scan major online marketplaces (e.g., Amazon, eBay, Walmart, Shopify stores) to collect advertised prices for each SKU.
- **Reseller Identity Mapping**: Use fuzzy matching and partial lookup algorithms to map seemingly distinct seller names across platforms to a single reseller entity (e.g., “Smart Place Store” → “7-Eleven”).
- **Violation Detection**: Compare Seller Advertised Prices (SAP) against the predefined LPP (typically set at 95% of MAP) to detect underpricing.
- **Automated Warning System**: Generate and send personalized warning letters to non-compliant resellers via email or integrated partner portals, referencing specific SKUs, dates, and violation details.
- **Enforcement Workflow**: Implement a tiered response mechanism where repeat offenders face progressive penalties, culminating in the suspension of product categories until compliance is restored.
- **Audit & Reporting**: Maintain a full audit trail of detected violations, communications sent, and enforcement actions taken for legal and operational review.

## **Project illustration**

**System Workflow – Example Scenario**
Consider the following real-world scenario illustrating how the system operates:

SKU: GT53XL
MAP: $100.00
LPP: $95.00 (i.e., 95% of MAP)
Reseller: 7-Eleven (operating as "Smart Place Store" on one platform)

- **Step 1: Monitoring**
The system crawls a major marketplace and detects that “Smart Place Store” is advertising SKU GT53XL at $90.00, which is below the LPP of $95.00.

- **Step 2: Reseller Mapping**
Using the internal reseller mapping database and fuzzy matching algorithms, the system identifies “Smart Place Store” as a storefront associated with the registered reseller 7-Eleven.

- **Step 3: Violation Alert & Action**
A violation record is created. The system automatically generates a formal Warning Letter (based on the template in Warning Letter.docx) addressed to 7-Eleven, detailing:

  The violating SKU and price
  The applicable MAP and LPP
  The date and location of detection
  A clear statement of policy breach
  Instructions for correction and consequences of future violations
  The letter is sent via email and logged in the compliance dashboard.

- **Step 4: Follow-Up Enforcement**
  If 7-Eleven continues to advertise GT53XL below $95.00 after a defined grace period, the system triggers the next level of enforcement:

   Category Suspension: All products within the same category (e.g., “Premium Ink Cartridges”) are suspended for 7-Eleven in the client’s distribution
   system, preventing further shipments or listings until compliance is verified.

 ## **Deliverables**
     **MAP Compliance Monitoring Platform**
          - Web-based dashboard for real-time visibility into compliance status.
          - Integration with third-party marketplace APIs for price data collection.
     **Reseller Identity Resolution Engine**
         - Database of known resellers with aliases and cross-platform mappings.
         - Fuzzy matching algorithm for detecting new alias usage.
     **Automated Alerting & Communication Module**
         - Template-driven warning letter generator (aligned with Warning Letter.docx).
         - Email/SMS notification system with delivery tracking.
     **Enforcement Management System**
         - Rule-based workflow engine for issuing warnings, tracking responses, and applying sanctions.
         - Category suspension module linked to inventory or partner management systems.
     **Reporting and Analytics Suite**
         - Monthly compliance reports.
         - Heatmaps of violation trends by region, category, or reseller.
         - Audit logs for regulatory or contractual purposes.

## Expected Outcomes and Benefits
Upon successful implementation, the MAP Compliance System will deliver the following benefits:

**Preservation of Brand Value**: Prevents race-to-the-bottom pricing that damages brand perception.

**Level Playing Field**: Ensures all resellers compete fairly based on service and customer experience—not predatory pricing.

**Operational Efficiency**: Reduces manual labor in monitoring and enforcement by over 80%, enabling faster response times.

**Legal Protection**: Creates a documented chain of evidence for disputes or contract terminations.

**Stronger Partner Relationships**: Rewards compliant resellers with continued access and support, fostering loyalty.

**Market Stability**: Contributes to healthier margins across the ecosystem and more predictable revenue streams.
         
