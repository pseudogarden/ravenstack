## Overview
flutterwave sandbox url: `https://ravesandboxapi.flutterwave.com`

flutterwave live url: `https://api.ravepay.co`

### Request Headers
```
Accept: application/json
Content-type: application/json
```
### Response
```json
{
  "status": "success",
  "message": "The request succeeded",
  "data": {
    //
  }
}

{
  "status": "error",
  "message": "No transaction found",
  "data": {
    "code": "NO TX",
    "message": "No transaction found"
  }
}

{
  // codes
  - 400 bad request
  - 404 Not Found
  - 500 Internal Server Error
  - 503 Service Unavailable
}
```