# User Signed In

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "User Signed In",
    "user": {
        "custKey": "<custKey>",
        "system": "<system>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|custKey|string|Unique identifier of a customer.  Any id's considered PII must be hashed. ||||||||
|system|string|Describes the system that the user is logged into.  \(rarely used\). |admin, shop, member|||||||




