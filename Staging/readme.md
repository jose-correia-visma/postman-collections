
# Settings Api

Postman collection tailored for internal-api in staging environment.

Collection tailored for the Settings API, which serves as the backend service responsible for storing user-specific data utilized to populate the dashboards within the Reports module

**Base Url** : `https://settings.staging.e-conomic.com`

[Read more](https://github.com/e-conomic/settings) 

## GET `/v2/e-conomic/-1/:aggreement/user/:userId/dashboard_v2`
Get user settings 

## PUT `/v2/e-conomic/-1/:aggreement/user/:userId/dashboard_v2`
Edit user settings

**Request Payload**

```
{
    "charts": [
        {
            "id": "3fdea0f4-c7ba-4b18-9e93-12d33c9fbb7b",
            "name": "Top overdue sales invoices 2321321",
            "chartType": 4,
            "dataType": 2
        },
        ...
    ]
}
```
## DELETE `/v2/e-conomic/-1/:aggreement/user/:userId/dashboard_v2`
Delete user settings

