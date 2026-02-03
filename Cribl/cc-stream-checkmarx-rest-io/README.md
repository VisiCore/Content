# Checkmarx Rest Collector Rest Collector

## **About This Pack**

----
This Cribl Pack collects **audit trail events** from the [Checkmarx One API](https://checkmarx.stoplight.io/docs/checkmarx-one-api-reference-guide/branches/main/df69417e9e368-retrieve-audit-trail-events), giving you visibility into user and system actions within your Checkmarx environment. It enables centralized monitoring, compliance reporting, and correlation with other security telemetry in your observability stack.


## **Usage**

---
1. Configure Variables:
Within the Pack > Knowledge > Variables 

    - **DataType:**

    - **client_id:**

    - **client_secret**

    - **org_id:**

    - **Content-Type:**

    - **Grant-Type:**

    - **geo:**(examples below)
            
            anz.ast.checkmarx.net is for Australia & New Zealand.
            us.ast.checkmarx.net is for the United States.
            eu.ast.checkmarx.net is for the European Union.

2. Configure Secret:
Within the Pack > Sources > Rest > vct-checkmarx-rest > Configure as json > Click back to configure > enter client_secret

3. Configure Destination:
Within the Pack > Destinations

4. Adjust Route:
Current route uses default:default Destination

## **Author**

---

Andrew Hendrix - Andrewh@visicoretech.com

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