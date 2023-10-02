# di-export-subnetwork-by-rest
 ArcGis Blog for Utility Network Export Subnetwork
 
This repo is for sharing the workspace published in this two-part blog in ArcGIS Blog. The blog was written by Jon De Rose and Renato Salvaleon.

Leveraging Data for External Systems - Automating Export Subnetwork using Data Interoperability<br/>
[Part One ](https://www.esri.com/arcgis-blog/products/utility-network/data-management/exporting-subnetworks-using-data-interoperability/)<br/>
[Part Two ](https://www.esri.com/arcgis-blog/products/utility-network/data-management/exporting-subnetworks-using-data-interoperability-part2/)<br/>

This repo data interop workspace is also [available from part two of the blog](https://community.esri.com/t5/arcgis-utility-network-documents/sample-workbench-file-leveraging-data-for-external/ta-p/1053123). <br/>


## Features
* Converts result JSON of an export subnetwork REST API call to the following outputs: File GDB, geopackage and shapfile.
* This workspace includes generating description of the domain, asset groups, and asset types of the exported subnetwork.

## Instructions

1. Fork and then clone the repo. 
2. Read the blog before you re-configure your own utility network.
3. This workspace will not run without configuring correctly to your own enterprise utility network.
4. Since not all utility networks are created exactly the same, after you have configured your network, it is highly possible that source attributes, some transformers, and writers will have to be reconfigured after the update.

## Requirements

* Data Interoperability for ArcGIS Pro 2.6 or higher
* ArcGIS Pro 2.6 or  higher
* Enterprise Utility Network with a schema of UNv3 or higher

## Resources

Below are links to essential references used in the blogs.

Utility Network:<br/>
* [Export Subnetworks (Doc)](https://pro.arcgis.com/en/pro-app/latest/help/data/utility-network/export-subnetworks.htm)<br/>
* [Trace (Doc)](https://pro.arcgis.com/en/pro-app/latest/help/data/utility-network/about-tracing-utility-networks.htm)<br/>
* [Web Trace tool Blog](https://www.esri.com/arcgis-blog/products/utility-network/data-management/a-technical-walk-through-for-a-simple-utility-network-web-trace-tool-with-javascript/)<br/>
* [Command line automation for Utility Network blog](https://www.esri.com/arcgis-blog/products/utility-network/administration/automating-utility-network-functions-using-command-line/)<br/>
* [Utility Network Upgrade History (Doc)](https://pro.arcgis.com/en/pro-app/latest/help/data/utility-network/utility-network-upgrade-history.htm)<br/>
* [Export Subnetwork GP Tool (Doc)](https://pro.arcgis.com/en/pro-app/latest/tool-reference/utility-networks/export-subnetwork.htm)<br/>
* [Export Subnetwork Reast API (Doc)](https://developers.arcgis.com/rest/services-reference/enterprise/exportsubnetwork-utility-network-server-.htm)<br/>
* [Network Topology index (Pro SDK Doc)](https://github.com/esri/arcgis-pro-sdk/wiki/ProConcepts-Utility-Network#network-topology)<br/>
* [Tracing subset of the Utility Network (Pro SDK Doc)](https://github.com/esri/arcgis-pro-sdk/wiki/ProConcepts-Utility-Network#tracing)<br/>
* [Adding Description to Export Subnetwork JSON blog](https://community.esri.com/t5/arcgis-utility-network-questions/adding-descriptions-to-export-subnetwork-json/m-p/367933)<br/>

Data Interopearbility Automation <br/>
* [Spatial ETL Tool (Doc)](https://pro.arcgis.com/en/pro-app/latest/help/data/data-interoperability/spatial-etl-tools.htm)
* [Automate yor ETL Processes blog](https://community.esri.com/t5/arcgis-data-interoperability-blog/automate-your-etl-processes-on-a-schedule-two-ways/ba-p/883616)<br/>

JSON tutorial references:<br/>
* [Ontario511](https://pm.maps.arcgis.com/home/item.html?id=4ec1d2420089451bb173e90ce01e2e0a)<br/>
* [Import Building GeoJSON](https://pm.maps.arcgis.com/home/item.html?id=9da0f8ae5fee45aca11bf77f712884c8)<br/>
* [Learn JSON](https://www.youtube.com/watch?v=iiADhChRriM)<br/>



## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Esri welcomes contributions from anyone and everyone. Please see our [guidelines for contributing](https://github.com/esri/contributing).

## Licensing
Copyright 2021 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](https://github.com/salvaleonrp/di-data-driven-electric-utility-export-subnetwork/blob/main/license.txt) file.

[](Esri Tags: Data Interoperability for ArcGIS Pro)
[](Esri Tags: Utility Network)
