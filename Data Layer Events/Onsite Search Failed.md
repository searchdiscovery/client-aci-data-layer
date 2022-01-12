# Onsite Search Failed

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "Onsite Search Failed",
    "onsiteSearch": {
        "keyword": {
            "searchTerm": "<searchTerm>",
            "searchType": "<searchType>"
        }
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|searchTerm|string|Describes the search keyword used after auto-correct, auto-complete, or keyword suggestion. |bluth, blue, red lobster|||||||
|searchType|string|Describes the domain of the search. |products, properties, articles, authors, coupons, publications|||||||




