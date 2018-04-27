# definitions-openapi
This project is a collection of OpenAPI (also known as *OAS*) definitions and data schemas that are commonly used regardless of the domain in which a project might reside. 


## What is your purpose here?
The intention for this project is to be a collaborative 'common' data repository, ensuring that data for these common areas fully encompass the needs of all domains. 
For example: Does the financial industry utilize an address differently than the logistics industry? 
 - How is the data used differently - *what is the use case*? 
 - What data elements are new/used/unused - *is the schema both valid **and** efficient*?
 - How do we ensure that those differences, when incorporated, don't negatively affect other domains - *standardization*?

## How are you going about it?
We are using OpenAPI 3.x definitions, and incorporating OData queries as a commonality. We've actually borrowed a few of the OData [parameter definitions](schema/odata/parameters.json) from their examples: [OData to OpenAPI Mapping Version 1.0](http://docs.oasis-open.org/odata/odata-openapi/v1.0/cnprd01/odata-openapi-v1.0-cnprd01.html)


## What is needed?
A small laundry list of TODOs include:
- [x] Complete the [Address](schema/common/Address.json) Schema
- [x] Complete the [Country](schema/common/Country.json) Schema
- [x] Complete the [Subdivision](schema/common/Subdivision.json) Schema
- [x] Complete the [TimeZone](schema/common/TimeZone.json) Schema
- [ ] Start the Address API specification
- [ ] Complete the [Country API](api/common) specification
- [ ] Start the Subdivision API specification
- [ ] Start the TimeZone API specification
- [ ] Conquer the world


Special appreciation to the following teams for their outstanding efforts:
- [OAI OpenAPI Specification Team](https://github.com/OAI/OpenAPI-Specification)
- [OASIS Team](https://www.oasis-open.org)
