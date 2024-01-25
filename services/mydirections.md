# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://maps.googleapis.com/maps/api/directions/json?origin=place_id:ChIJ_8ztAq32K4gRF44mljnynd0&destination=place_id:ChIJaV_Nz-BhK4gRpYcpDyiCfyM&departure_time=1706290200&mode=transit&transit_routing_preference=fewer_transfers&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE 
```

Copy/paste the JSON results and save them into the empty file ```mydirections.json``` in this repository

## Optional URLs
In my first year of undergrad at UW I didn't have a car, but was felt homesick often so the best way was to take transit to the GO station in Burlington where my parents would pick me up. 

### Origin & destination 
The University of Waterloo, Waterloo, ON: https://www.google.com/maps/place/?q=place_id:ChIJ_8ztAq32K4gRF44mljnynd0
Burlington GO Station, Burlington, ON: https://www.google.com/maps/place/?q=place_id:ChIJaV_Nz-BhK4gRpYcpDyiCfyM

### Origin & destination JSON return
University of Waterloo: https://maps.googleapis.com/maps/api/place/details/json?placeid=ChIJ_8ztAq32K4gRF44mljnynd0&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE
Burlington GO: https://maps.googleapis.com/maps/api/place/details/json?placeid=ChIJaV_Nz-BhK4gRpYcpDyiCfyM&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE 

### Simple option:

(returns map-preferred) Maps PlaceID search: https://www.google.com/maps/place/?q=place_id:ChIJFfiCrdo4Qm0RqPwuOAVtaj8
### Efficient option

(returns JSON) API PlaceID link https://maps.googleapis.com/maps/api/place/details/json?placeid=ChIJV2BQ4laeekgRFauLvdXbFXE&key=<INSERTKEY>

  which the JSON will have a CID that can be directly used as a URL like https://maps.google.com/?cid=4569584641105657000


____
## Rubric

Note: MarkDown (.md) documents are not HTML and therefore are best viewed in the github.com website, not on the pages github.io page. Marking will occur using the github.com source. 

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown and results in the JSON file with a unique origin and destination in directions earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%. Explore the API documentation for parameters we have not used.
4. Tell the story of your route. Include more than 2 "stops", and/or including additional links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
