# SailPoint V3 Search Rest Collector

## **About This Pack**

----

The /v3/search endpoint in the SailPoint IdentityNow API allows you to query a variety of object types, but specifically for events, you can retrieve audit or system activity logs that track changes, actions, and processes within your Identity Security Cloud environment
 The following objects are searchable: identities, roles, access profiles, entitlements, events, and account activities.

[SailPoint API Docs](https://developer.sailpoint.com/docs/api/v3/search)

## **Usage**

---
1. Configure Variables:
Within the Pack > Knowledge > Variables 

    - **DataType:**

    - **client_id:**

    - **endpoint_host:**

3. Configure Secret:
Within the Pack > Sources > Rest > _vct_rest_sailpoint_v3_search > Configure as json > Click back to configure > enter client_secret

4. Configure Destination:
Within the Pack > Destinations

5. Adjust Route:
Current route uses default:default Destination

## **Authors**

---

Andrew Hendrix - Andrewh@visicoretech.com

Stacy Simmons - ssimmons@cribl.io

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