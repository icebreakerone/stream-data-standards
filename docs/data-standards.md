# Data standards for the Stream programme

This is the current data standards for the Stream programme. The data standards are published here for use by the Stream Programme, the partners, and data consumers.

A glossary of terms used in the data standards is available in the [Stream Data Standards Glossary](data-standards-glossary.md).

The process for suggesting changes to the data standards is available in the [Updating process for Stream data standards](governance/update-process.md#stream-process-for-merging-a-pull-request).

The governance for Stream data standards is managed by the Stream Data Standards Workstream. The governance documentation is linked from the [README file](README.md).

## Data Standards

## Metadata standard

The standard for Metadata is the [Gemini 2.3 standard](https://knowledge-base.inspire.ec.europa.eu/index_en) which is based on the [INSPIRE Metadata Directive](https://knowledge-base.inspire.ec.europa.eu/index_en). The ESRI platform can displaying Gemini 2.3 using the INSPIRE metadata standard built into the ESRI platform. To ensure that metadata using the INSPIRE standard is Gemini 2.3 compliant, please refer to this [Gemini 2.3 metedata guidance on the ArcGIS website](https://govportal.maps.arcgis.com/home/item.html?id=ad26f71f42e24d1eaf7fb3e347a049a9).

### CSV datasets

The standard for CSV format datasets used for Stream data is described in [RFC 4180](https://datatracker.ietf.org/doc/html/rfc4180).

### Geospatial vector datasets

The Shapefile format will be used for initial publication of geospatial data on Stream. The Shapefile definition is described on the ESRI website in the [ESRI Shapefile Technical Description (PDF document)](https://www.esri.com/content/dam/esrisites/sitecore-archive/Files/Pdfs/library/whitepapers/pdfs/shapefile.pdf).

It has been noted by the Stream programme that the Shapefile format is not an [open standard](https://en.wikipedia.org/wiki/Open_standard). The decision to use the Shapefile standard may change in the future as the Stream programme develops and matures.

### Data standards for other geographical datasets

GSS codes will be used for geocoding some data published on the Stream platform. GSS Codes [UK Government Statistical Service (GSS) geography codes](https://en.wikipedia.org/wiki/GSS_coding_system). The full dataset of geographical codes is available from the [Register of Geographic Codes (December 2023) for the United Kingdom](https://geoportal.statistics.gov.uk/datasets/2219f72d5b8042c496e47488efd04b16/about). 
