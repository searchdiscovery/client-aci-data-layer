# Report Viewed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "Report Viewed",
    "reportAction": {
        "reports": [
            {
                "reportID": "<reportID>",
                "reportType": "<reportType>"
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|reportID|string|Unique ID for a Report||||||||
|reportType|string|The type of the report|Transactions, Financial|||||||




