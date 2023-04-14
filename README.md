 Outer pipes  Cell padding 
No sorting
| Error Type          | Error Desc                                          | App Error Code | HTTP Status Code | HTTP Status Desc      | Retry Possible | Retry Count | Ultimate action           | MS Error Level |
| ------------------- | --------------------------------------------------- | -------------- | ---------------- | --------------------- | -------------- | ----------- | ------------------------- | -------------- |
| LISTINGID_NOT_FOUND | listingId does not exit                             | MS-404         | 404              | Not Found             | No             | 0           | Caller to analyze         | ERROR          |
| SERVER_ERROR        | Internal server error occurred due to backend error | MS-500         | 500              | Internal Server Error | Yes            | 3           | Caller to inform Provider | FATAL          |
📋 Copy
Clear
Buy Me a Coffee at ko-fi.com