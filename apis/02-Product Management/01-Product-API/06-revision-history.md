# Revision history

| Date | Changes |
| ---- | ---------------- |
| 2018-06-15 | Added support documentation about Per Stay Service Fees at the Rateplan level (GET,POST,PUT)
| 2017-08-10 | Added FAQ around managing deposit required flag in conjunction with the new Deposit API |
| 2017-08-07 | Added documentation about new `depositPolicy` link in Rate Plan's links section of the response payload on GET Rate Plan and GET Rate Plans operations. |
| 2017-07-31 | Added access to room type and rate plan resources without "/products" in endpoint path. |
| 2017-05-19 | Corrected list of support room views |
| 2016-11-12 | Released new feature to expose a rate plan's deposit required flag, create and last update dates in read-only format: these attributes can be read by partners via GET. They cannot be provided with a create request (deposit is set to false by default), and they cannot be changed in update requests. |
| 2016-10-20 | Released new feature to expose a room type's rate thresholds, in read-only format. Only GET operation is allowed on this sub resource. |
| 2016-10-18 | Released new feature to expose RatePlanLinkage information in read-only format in rate plan GET. Added links section to show rate plan resource's link to itself, his rate plan linkage parent if any, and/or its derived child rate plans if any. |
| 2016-09-29 | New section documenting changes between V1 and V2 was added in the [FAQ and Guides section](guides.html#/v1v2diff). |
| 2016-06-10 | Product API v2 now live. Versioning strategy changed from URL to using content-type and accept headers. As a result, URLs have all changed to have V1 removed when partners are ready to use V2. Room type resource changed significantly for defining bed types and occupancy. |
| 2016-05-02 | Added support for cancel policy exceptions |
| 2016-04-27 | Added support for Rate Plan Delete |
| 2016-04-04 | Refreshed list of supported value adds, added more pricing models supported, clarified required VS optional fields. |
| 2016-02-01 | Added support for room-level amenities (GET and PUT) |
| 2016-01-07 | Support for read/create/update room views and wheelchair accessibility in room type resource |
| 2015-12-07 | First version of the online API. Additional feature since last PDF version: support for read/create/update room size in room type resource |

