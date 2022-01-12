# User Subscribed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "User Subscribed",
    "subscription": {
        "subscribeMethod": "<subscribeMethod>",
        "subscriptionType": "<subscriptionType>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|subscribeMethod|string|Describes the method used to subscribe. |footer field, registration opt in, order placed, notification preferences|||||||
|subscriptionType|string|Describes the type of subscription. |news, updates, sales, events|||||||




