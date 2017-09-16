# Esri TechCrunch SF Hackathon Resources
_Also find Esri and OS projects on [Github](https://esri.github.io/)!_

- [Activate your account and credits](#activate-your-account-and-credits)
- [See what's possible](#see-whats-possible)
- [Get started](#get-started)
- [Use cool services](#use-cool-services)
- [Find cool datasets](#find-cool-datasets)
- [Use cool datasets](#use-cool-datasets)
- [Explore global data and content](#explore-global-data-and-content)

## Activate your account and credits
1.	Sign-up for a free developer account at <http://developers.arcgis.com>
2.	Sign in to your account
3.	Click your name at the top right, click “Redeem Voucher”, then enter DISRUPTSF17 for 1000 credits

## See what's possible

![Manhattan Preview Full](/images/manhattan-preview-full.png?raw=true)

- [Visualize the US River Network](https://github.com/richiecarmichael/Esri-Hydro-Hierarchy)
- [Baltimore Flood Explorer](https://maps.esri.com/rc/water/index.html)
- [Esri + PubNub delivery tracking demo](https://github.com/Esri/pubnub-delivery-tracking-demo)
- [Explore buildings in NYC](https://esri.github.io/Manhattan-skyscraper-explorer/)
- [SF urban growth and demographics](https://coolmaps.esri.com/#5)
- [Urban planning with the City of Philadelphia](https://www.arcgis.com/apps/CEWebViewer/viewer.html?3dWebScene=86f88285788a4c53bd3d5dde6b315dfe)

## Get started
- [Core developer functionality](https://developers.arcgis.com/features/)
- [Quick start tutorials](https://developers.arcgis.com/labs/)
- Host your custom data as a service:
  - [Create an empty service](https://developers.arcgis.com/labs/data/create-a-new-dataset/)
  - [Import your data](https://developers.arcgis.com/labs/data/import-data)
- API & SDK tutorials
  - [Javascript](https://developers.arcgis.com/labs/develop/#javascript)
  - [Android](https://developers.arcgis.com/labs/develop/#android)
  - [iOS](https://developers.arcgis.com/labs/develop/#ios)
  - [And more!](https://developers.arcgis.com/labs/develop/index.html)
- [Full API & SDK sample code and documentation](https://developers.arcgis.com/documentation/#sdks)

## Use cool services
- [Trace water downstream from a given location](https://developers.arcgis.com/rest/elevation/api-reference/trace-downstream.htm)
- [Evaluate watersheds and where water will go](https://developers.arcgis.com/rest/elevation/api-reference/watershed.htm)

## Find cool datasets

![Population Data](/images/population-data.png?raw=true)

- SF Downtown buildings: [Viewer](https://sfgis-portal.sfgov.org/arcgis/home/webscene/viewer.html?layers=1fc011c6e82a46bfad429628d37c5175) and [REST endpoint](https://sfgis-portal.sfgov.org/srv/rest/services/Hosted/Downtown_textured3D_P2010_bldg/SceneServer/layers/0)
- SF Downtown building shapes: [Viewer](https://sfgis-portal.sfgov.org/arcgis/home/webscene/viewer.html?layers=4c79dbab169d46f78cad35503659b899) and [REST endpoint](https://sfgis-portal.sfgov.org/srv/rest/services/Hosted/City_noTex_bldg3d_mpgz/SceneServer/layers/0)
- SF City facilities: [Viewer](http://www.arcgis.com/home/webmap/viewer.html?url=https%3A%2F%2Fsfgis-svc.sfgov.org%2Farcgis%2Frest%2Fservices%2Fsfgis%2Fcity_facilities_on_sfgis_svc%2FFeatureServer%2F0&source=sd) and [REST endpoint](https://sfgis-svc.sfgov.org/arcgis/rest/services/sfgis/city_facilities_on_sfgis_svc/FeatureServer/0)
- SF Hospitals: [Viewer](http://hub.arcgis.com/datasets/a9c42521cf68466eb39d16d582279b66_0) and [REST endpoint](https://services3.arcgis.com/YZdItf6NReIVcw7j/arcgis/rest/services/HospitalMap_WFL1/FeatureServer/0/query?outFields=*&where=1%3D1)
- SF Land use: [Viewer](http://hub.arcgis.com/datasets/Stanford::sf-land-use) and [REST Endpoint](https://services.arcgis.com/7CRlmWNEbeCqEJ6a/arcgis/rest/services/SF_Parcels/FeatureServer/0/query?outFields=*&where=1%3D1)
-	SF Tree canopies: [Viewer](http://hub.arcgis.com/datasets/Stanford::sf-tree-canopy) and [REST Endpoint](https://services.arcgis.com/7CRlmWNEbeCqEJ6a/arcgis/rest/services/SF_Parcels/FeatureServer/1/query?outFields=*&where=1%3D1)
-	SF Population: [Viewer](http://hub.arcgis.com/datasets/Stanford::population) and [REST Endpoint](https://services.arcgis.com/7CRlmWNEbeCqEJ6a/arcgis/rest/services/SF_Population/FeatureServer/0/query?outFields=*&where=1%3D1)
-	CDC Social Vulnerability Index—socioeconomic CVI: [Viewer](http://hub.arcgis.com/datasets/4759ce4869d3412895b6024c02a71d35_0?geometry=-122.446%2C37.782%2C-122.384%2C37.794) and [REST Endpoint](https://services3.arcgis.com/ZvidGQkLaDJxRSJ2/arcgis/rest/services/socioeconomic_2014_tract/FeatureServer/0/query?outFields=*&where=1%3D1)

_Note, we call datasets "layers"--these are just spatial data tables with metadata, rendering info, and operations exposed as a REST endpoint. The data table rows in each "layer" are called "features" and "features" have "attributes"_

## Use cool datasets
1. [Create a Web Map or 3d Scene](https://developers.arcgis.com/labs/design/index.html) to aggregate and stylize the datasets and add them to an app with [just an item id](https://developers.arcgis.com/labs/develop/index.html) (see "Display a web map") __OR__
2. [Add the data directly](https://developers.arcgis.com/labs/develop/index.html) (see "Create a 2d Map/3d Scene with a layer")

_Note, if there isn't a tutorial here, there's also __sample code__ for [each of the SDKs](https://developers.arcgis.com/documentation/)--just search for "layers"_

## Explore global data and content
- [Overview of ready to use content](http://www.arcgis.com/features/maps/index.html)
- [Open data hub](http://hub.arcgis.com/pages/open-data)
- [Living Atlas of the World](https://livingatlas.arcgis.com/en/#s=0)
