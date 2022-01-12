# Content Listing Item Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "Content Listing Item Clicked",
    "listingItemClicked": {
        "listing": [
            {
                "content": {
                    "contentID": "<contentID>",
                    "contentTitle": "<contentTitle>",
                    "itemPosition": <itemPosition>
                }
            }
        ]
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|contentID|string|Unique identifer of the content.||||||||
|contentTitle|string|Title of a piece of content. |50 ways to use jello, Another look at pandas, Year end giving|||||||
|itemPosition|integer|Captures the position of each content item in a content listing. |1, 2, 3, 4, 5|||||||




