# Listing Filter Added

### 

## Javascript Code
```js
window.appEventData2076 = window.appEventData2076 || [];
appEventData2076.push({
  "event": "Listing Filter Added",
    "listingDisplayed": {
        "matrixRefinementConversion": "<matrixRefinementConversion>"
    },
    "listingRefined": {
        "allFiltersAppliedAndValues": "<allFiltersAppliedAndValues>",
        "countOfStoresInFilter": "<countOfStoresInFilter>",
        "defaultFiltersAppliedAndValues": "<defaultFiltersAppliedAndValues>",
        "filterList": "<filterList>",
        "listingType": "<listingType>",
        "manualFiltersApplied": "<manualFiltersApplied>",
        "manualFiltersAppliedAndValues": "<manualFiltersAppliedAndValues>"
    }
});
```

## Variable Definitions

|Field|Type|Description|Example|Pattern|Min Length|Max Length|Minimum|Maximum|Multiple Of|
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|allFiltersAppliedAndValues|string|Captures all of the bread crumb values that are being used to make up the product assortment for the product matrix page that a customer is on. This is made up of both defaulted values and manually added filters. Example: color:blue|dresses|size:xl|tops|women||||||||
|countOfStoresInFilter|string|When a user is on a PMP and uses the filter area to refine by store(s), it captures the number of stores used in the filter and the radius in miles for the store that was farthest away||||||||
|defaultFiltersAppliedAndValues|string|The bread crumb values that were set as default by Kohl's for a customer when they landed on a product matrix. Does not contain any filters that were added. Example: shirts|tops|women||||||||
|filterList|string|A twice delimited string of filterType and filterValue pairs.  Use ~ between type and value.  Use | between pairs|sort~price ascending|color~green|size~medium|||||||
|listingType|string|The type of listings shown|Product, Location, Event, Room, Content|||||||
|manualFiltersApplied|string|Captures all filters that have been manually added by the customer on a product matrix. Example: color|size||||||||
|manualFiltersAppliedAndValues|string|Captures all filters that have been manually added by the customer on a product matrix. Example: color:blue|size:xl||||||||
|matrixRefinementConversion|string|Captures the matrix default value and the specific refinement used when a user filters on a product matrix page. Values captured in this format: mens|tops>size:xl||||||||
