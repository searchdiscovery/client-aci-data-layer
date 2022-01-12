# CTA Link Clicked

### 

## Javascript Code
```js
window.appEventData = window.appEventData || [];;;
appEventData.push({
  "event": "CTA Link Clicked",
    "linkInfo": {
        "linkId": "<linkId>",
        "linkRegion": "<linkRegion>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|linkId|string|Identifier of the link clicked|act now, cancel, ok, 3456, 8765|||||||
|linkRegion|string|Indicates the region on page for a clicked link within the hierarchy \[Site &gt; Page &gt; Region &gt; Container &gt; linkID\]|Top Nav, Footer Nav, Hero, Recommended, Also Shopped, Also Bought|||||||




