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
