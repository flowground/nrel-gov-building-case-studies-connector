# ![LOGO](logo.png) High Performance Building Database **flow**ground Connector

## Description

A generated **flow**ground connector for the High Performance Building Database API (version 1.0).

Generated from: https://api.apis.guru/v2/specs/nrel.gov/building-case-studies/1.0/swagger.json<br/>
Generated at: 2019-05-07T17:43:18+03:00

## API Description

The Buildings Database is a shared resource for the building industry. The Database, developed by the U.S. Department of Energy and the National Renewable Energy Laboratory (NREL), is a unique central repository of in-depth information and data on high-performance, green building projects across the United States and abroad.  

## Authorization

Supported authorization schemes:
- API Key
## Actions

### A filterable list of projects.

*Tags:* `project`

#### Input Parameters
* `output_format` - _required_ - Response Format
    Possible values: json, xml.
* `search` - _optional_ - Search Text
* `portal` - _optional_ - Portal ID
* `page` - _optional_ - Page Number
* `city` - _optional_ - City
* `province` - _optional_ - State or Province (ex: 'CO', 'AZ')
* `region` - _optional_ - Climate Region.  Use integer from mapping (256: '1A: Very Hot - Humid', 257: '1B: Very Hot - Dry', 258: '2A: Hot - Humid', 259: '2B: Hot - Dry', 260: '3A: Warm - Humid', 261: '3B: Warm - Dry', 262: '3C: Warm - Marine', 263: '4A: Mixed - Humid', 264: '4B: Mixed - Dry', 265: '4C: Mixed - Marine', 266: '5A: Cool - Humid', 267: '5B: Cool - Dry', 268: '5C: Cool - Marine', 269: '6A: Cold - Humid', 270: '6B: Cold - Dry', 271: '7: Very Cold', 272: '8: Subarctic')

### Project Details

> This API allows users to request metadata associated with the specific Document.

*Tags:* `project`

#### Input Parameters
* `output_format` - _required_ - Response Format
    Possible values: json, xml.
* `project_id` - _required_ - Project ID

## License

**flow**ground :- Telekom iPaaS / nrel-gov-building-case-studies-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
