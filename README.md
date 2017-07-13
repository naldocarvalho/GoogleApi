## GoogleApi v3.0.0
Seamless Google Api integrations.
Supports Maps, Places, Roads, Custom Search and Translate.  
Feel free to contribute, ask questions or report issues. I usually reply within 24 hours.

##### Nuget: https://www.nuget.org/packages/GoogleApi (net4.5, netstandard1.2)

##### Version 3.0.0 Highlights: 
* Follow the progress for endpoints upgrade below.
* Downgrade to netstandard1.2 (more portable platforms support, i think).
* Walk-through of all endpoints aligned with Google Api Documentation.
* Request validation improved for all endpoints.
* Added missing endpoints. All Api's are now complete again.
* Search fully implemented and supported (possibly postponed to v3.1).
* Improvements to Language and Country Enums / Extensions (aligned with Google, isolated for all endpoints).
* Type and Namespace cleanup. Base / Common entities refactored.
* Test Suite expanded greatly. 90%+ coverage overall.
* and much more.


### Google Api Integrations:
##### Google Maps 3.0
  * Directions
  * Distance Matrix
  * Elevation
  * Geocoding
  * Reverse Geocoding
  * Geolocation
  * Roads
    * Nearest Roads
    * Snap To Roads
    * Speed Limits
  * Time Zone

##### Google Places
  * Place Search
    * Near By
	* Text
	* Radar
  * Place Details
  * Place Add
  * Place Delete
  * Place Photos
  * Place Autocomplete
  * Query Autocomplete

##### Google Search (*Alpha*)
  * Web
  * Image
  * Enterprise (Paid)

##### Google Translate 3.0
  * Detect
  * Languages
  * Translate

##### Google Functions 3.0
  * MergePolyLine
  * EncodePolyLine
  * DecodePolyLine
