
# Data Product Canvas - Berlin LOR Housing Stock

## Metadata

* owner: Open Lifeworlds
* description: Data product providing Berlin housing stock data on different LOR hierarchy levels
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock
* license: CC-BY 4.0
* updated: 2025-11-07

## Input Ports

### berlin-lor-geodata

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-geodata/refs/heads/main/data-product-manifest.yml

### berlin-lor-housing-stock-source-aligned

* manifest URL: https://raw.githubusercontent.com/open-data-product/open-data-product-berlin-lor-housing-stock-source-aligned/refs/heads/main/data-product-manifest.yml

## Transformation Steps

* [Data extractor](https://github.com/open-lifeworlds/open-lifeworlds-python-lib/blob/main/openlifeworlds/extract/data_extractor.py) extracts data from inout ports
* [Data blender](https://github.com/open-lifeworlds/open-lifeworlds-python-lib/blob/main/openlifeworlds/transform/data_blender.py) blends csv data into geojson files

## Output Ports

### berlin-lor-housing-stock-geojson
name: Berlin Lor Housing Stock Geojson
* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/tree/main/data/03-gold/berlin-lor-housing-stock-geojson
* license: CC-BY 4.0
* updated: 2025-11-07

**Files**

* [berlin-lor-housing-stock-2015-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2015-00-district-regions.geojson)
* [berlin-lor-housing-stock-2015-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2015-00-districts.geojson)
* [berlin-lor-housing-stock-2015-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2015-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2015-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2015-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2016-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2016-00-district-regions.geojson)
* [berlin-lor-housing-stock-2016-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2016-00-districts.geojson)
* [berlin-lor-housing-stock-2016-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2016-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2016-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2016-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2017-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2017-00-district-regions.geojson)
* [berlin-lor-housing-stock-2017-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2017-00-districts.geojson)
* [berlin-lor-housing-stock-2017-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2017-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2017-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2017-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2018-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2018-00-district-regions.geojson)
* [berlin-lor-housing-stock-2018-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2018-00-districts.geojson)
* [berlin-lor-housing-stock-2018-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2018-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2018-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2018-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2019-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2019-00-district-regions.geojson)
* [berlin-lor-housing-stock-2019-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2019-00-districts.geojson)
* [berlin-lor-housing-stock-2019-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2019-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2019-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2019-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2020-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2020-00-district-regions.geojson)
* [berlin-lor-housing-stock-2020-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2020-00-districts.geojson)
* [berlin-lor-housing-stock-2020-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2020-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2020-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2020-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2021-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2021-00-district-regions.geojson)
* [berlin-lor-housing-stock-2021-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2021-00-districts.geojson)
* [berlin-lor-housing-stock-2021-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2021-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2021-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2021-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2022-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2022-00-district-regions.geojson)
* [berlin-lor-housing-stock-2022-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2022-00-districts.geojson)
* [berlin-lor-housing-stock-2022-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2022-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2022-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2022-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2023-00-district-regions.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2023-00-district-regions.geojson)
* [berlin-lor-housing-stock-2023-00-districts.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2023-00-districts.geojson)
* [berlin-lor-housing-stock-2023-00-forecast-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2023-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2023-00-planning-areas.geojson](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-geojson/berlin-lor-housing-stock-2023-00-planning-areas.geojson)


### berlin-lor-housing-stock-statistics
name: Berlin Lor Housing Stock Statistics
* owner: Open Lifeworlds
* url: https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/tree/main/data/03-gold/berlin-lor-housing-stock-statistics
* license: CC-BY 4.0
* updated: 2025-11-07

**Files**

* [berlin-lor-housing-stock-statistics.json](https://media.githubusercontent.com/media/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/refs/heads/main/data/03-gold/berlin-lor-housing-stock-statistics/berlin-lor-housing-stock-statistics.json)


## Observability

### Quality metrics

 * name: geojson_property_completeness
 * description: The percentage of geojson features that have all necessary properties

| Name | Value |
| --- | --- |
| berlin-lor-housing-stock-2015-00-districts.geojson | 100 |
| berlin-lor-housing-stock-2015-00-forecast-areas.geojson | 98 |
| berlin-lor-housing-stock-2015-00-district-regions.geojson | 97 |
| berlin-lor-housing-stock-2015-00-planning-areas.geojson | 79 |
| berlin-lor-housing-stock-2016-00-districts.geojson | 100 |
| berlin-lor-housing-stock-2016-00-forecast-areas.geojson | 98 |
| berlin-lor-housing-stock-2016-00-district-regions.geojson | 97 |
| berlin-lor-housing-stock-2016-00-planning-areas.geojson | 79 |
| berlin-lor-housing-stock-2017-00-districts.geojson | 100 |
| berlin-lor-housing-stock-2017-00-forecast-areas.geojson | 98 |
| berlin-lor-housing-stock-2017-00-district-regions.geojson | 97 |
| berlin-lor-housing-stock-2017-00-planning-areas.geojson | 79 |
| berlin-lor-housing-stock-2018-00-districts.geojson | 100 |
| berlin-lor-housing-stock-2018-00-forecast-areas.geojson | 98 |
| berlin-lor-housing-stock-2018-00-district-regions.geojson | 97 |
| berlin-lor-housing-stock-2018-00-planning-areas.geojson | 79 |
| berlin-lor-housing-stock-2019-00-districts.geojson | 100 |
| berlin-lor-housing-stock-2019-00-forecast-areas.geojson | 98 |
| berlin-lor-housing-stock-2019-00-district-regions.geojson | 97 |
| berlin-lor-housing-stock-2019-00-planning-areas.geojson | 80 |
| berlin-lor-housing-stock-2020-00-districts.geojson | 100 |
| berlin-lor-housing-stock-2020-00-forecast-areas.geojson | 98 |
| berlin-lor-housing-stock-2020-00-district-regions.geojson | 97 |
| berlin-lor-housing-stock-2020-00-planning-areas.geojson | 80 |
| berlin-lor-housing-stock-2021-00-districts.geojson | 100 |
| berlin-lor-housing-stock-2021-00-forecast-areas.geojson | 98 |
| berlin-lor-housing-stock-2021-00-district-regions.geojson | 97 |
| berlin-lor-housing-stock-2021-00-planning-areas.geojson | 80 |
| berlin-lor-housing-stock-2022-00-districts.geojson | 100 |
| berlin-lor-housing-stock-2022-00-forecast-areas.geojson | 88 |
| berlin-lor-housing-stock-2022-00-district-regions.geojson | 81 |
| berlin-lor-housing-stock-2022-00-planning-areas.geojson | 67 |
| berlin-lor-housing-stock-2023-00-districts.geojson | 100 |
| berlin-lor-housing-stock-2023-00-forecast-areas.geojson | 88 |
| berlin-lor-housing-stock-2023-00-district-regions.geojson | 81 |
| berlin-lor-housing-stock-2023-00-planning-areas.geojson | 67 |


## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

consumer-aligned


---
This data product canvas uses the template of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).