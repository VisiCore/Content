# Cribl Billing Credits REST Collector

## **About This Pack**

---

This Cribl REST Collector is configured to retrieve billing credits data from the Cribl Cloud API:  
`https://api.cribl.cloud/v4/organizations/<orgID>/billing/credits`

The collector provides a reliable, secure, and automated way to fetch billing credits information from the Cribl Cloud platform. This data can then be used to:

- Monitor usage trends  
- Track licensing and credit consumption  
- Integrate billing metrics into broader observability or cost-management workflows  

## **Why Use This Collector?**

---

Not everyone has direct access to FinOps tools or billing dashboards. In some organizations, responsibility for monitoring license consumption may sit with another team or platform. With this REST Collector, you can independently pull credit consumption data directly from Cribl’s API and make it available in your own environment.  

## **Important Note**

---

This collector leverages an **internal API endpoint** that is subject to change. As of now, this endpoint is undocumented, so use with caution and validate against your organization’s needs.  

## **Usage**

---

1. Configure Variables: Within the Pack > Knowledge > Variables 

    - **datatype:**

    - **orgID:**

    - **client_id:**

2. Configure Secret:
Within the Pack > Sources > Rest > vct-checkmarx-rest > Configure as json > Click back to configure > enter client_secret

3. Configure Destination:
Within the Pack > Destinations

5. Adjust Route:
Current route uses default:default Destination

If needed: Define datatype in knowledge objects - Defaults to 'cribl_cloud_credits'

### **Sample Data**

---

API response example can be found at ```sample_payload_billing_credits.log```

## **Authors**

---

Andrew Hendrix - Andrewh@visicoretech.com

Brandon Swanson - Brandon.Swanson@blackbaud.com

## **Release Notes**

---
- Version 1.0.0 - 2025-10-21
    - Initial release


## **Contributing to the Pack**

---

To contribute to this Pack, or to report any issues or enhancement requests, please contact us at <CriblPacks@VisiCoreTech.com>

## **License**

---

This Pack uses the following license: [`Apache 2.0`](https://github.com/criblio/appscope/blob/master/LICENSE).
