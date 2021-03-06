---
category: section-tools-geolocation
---

## Geolocation

You can use this API call for client-side or server-side detection of user's location. This API also works tightly with Paymentwall Risk Scoring.

##### Parameters

|Name|Description|
|---|---|
|key<br> *required*<br> **string**|The project key which can be found in Merchant Area→ My Projects. Project status should be LIVE to use this API.|
|uid<br> *required*<br> **string**| User's id. <br> User's account id used in your system.|
|user_ip<br> **string**|E.g. 255.255.255.255<br>IP address of the user.|
|callback<br> **string**|Callback function. Can be used for JSON on client side.|
