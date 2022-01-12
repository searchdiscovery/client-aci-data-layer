# User Detected

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "User Detected",
    "user": {
        "anonymousUserID": "<anonymousUserID>",
        "custKey": "<custKey>",
        "loginStatus": "<loginStatus>",
        "userType": "<userType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|anonymousUserID|string|When a user is not logged in,, this captures an anonymous user id.||||||||
|custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|loginStatus|string|Describes the login state of the user|logged in, logged out, guest|||||||
|userType|string|Describes the type of the user.  Often used to differentiate customers from employees or associates. |employee, guest, agent, customer|||||||




