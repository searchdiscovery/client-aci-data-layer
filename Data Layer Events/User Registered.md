# User Registered

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "User Registered",
    "user": {
        "custKey": "<custKey>",
        "loginStatus": "<loginStatus>",
        "registrationType": "<registrationType>",
        "userType": "<userType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|loginStatus|string|Describes the login state of the user|logged in, logged out, guest|||||||
|registrationType|string|Describes the thing that was registered for |account, loyalty program, event, sweepstakes, warranty|||||||
|userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||




