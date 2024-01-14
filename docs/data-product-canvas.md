# Data Product Canvas - Berlin LOR Housing Stock

## Input Ports

**Input ports define the format and protocol in which data can be read (database, file, API, visualizations)**

This data product uses LOR geodata provided by data
product [open-lifeworlds-data-product-berlin-lor-geodata](https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-geodata)
published under the following URLs

* [berlin-lor-districts/berlin-lor-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-geodata/main/data/berlin-lor-districts/berlin-lor-districts.geojson)
* [berlin-lor-forecast-areas-until-2020/berlin-lor-forecast-areas-until-2020.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-geodata/main/data/berlin-lor-forecast-areas-until-2020/berlin-lor-forecast-areas-until-2020.geojson)
* [berlin-lor-forecast-areas-from-2021/berlin-lor-forecast-areas-from-2021.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-geodata/main/data/berlin-lor-forecast-areas-from-2021/berlin-lor-forecast-areas-from-2021.geojson)
* [berlin-lor-district-regions-until-2020/berlin-lor-district-regions-until-2020.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-geodata/main/data/berlin-lor-district-regions-until-2020/berlin-lor-district-regions-until-2020.geojson)
* [berlin-lor-district-regions-from-2021/berlin-lor-district-regions-from-2021.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-geodata/main/data/berlin-lor-district-regions-from-2021/berlin-lor-district-regions-from-2021.geojson)
* [berlin-lor-planning-areas-until-2020/berlin-lor-planning-areas-until-2020.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-geodata/main/data/berlin-lor-planning-areas-until-2020/berlin-lor-planning-areas-until-2020.geojson)
* [berlin-lor-planning-areas-from-2021/berlin-lor-planning-areas-from-2021.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-geodata/main/data/berlin-lor-planning-areas-from-2021/berlin-lor-planning-areas-from-2021.geojson)

and statistical housing stock data provided by data
product [open-lifeworlds-data-product-berlin-lor-housing-stock-source-aligned](https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock-source-aligned)
published under the following URLs

* [berlin-lor-housing-stock-2015-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00.csv)
* [berlin-lor-housing-stock-2016-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00.csv)
* [berlin-lor-housing-stock-2017-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00.csv)
* [berlin-lor-housing-stock-2018-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00.csv)
* [berlin-lor-housing-stock-2019-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00.csv)
* [berlin-lor-housing-stock-2020-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00.csv)
* [berlin-lor-housing-stock-2021-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00.csv)
* [berlin-lor-housing-stock-2022-00.csv](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00.csv)

and statistical population data provided by data
product [open-lifeworlds-data-product-berlin-lor-population](https://github.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population)
published under the following URLs

* [berlin-lor-population-statistics/berlin-lor-population-statistics.json](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-population/main/data/berlin-lor-population-statistics/berlin-lor-population-statistics.json)

## Data Product Design

**Describe everything you need to design a data product on a conceptual level.**
**Ingestion, storage, transport, wrangling, cleaning, transformations, enrichment, augmentation, analytics, SQL
statements, or used data platform services.**

* [blends statistical data into geojson](../lib/transform/data_blender.py) on different LOR area hierarchy levels
* [aggregates statistical data into json](../lib/transform/data_blender.py) on different LOR area hierarchy levels

## Output Ports

**Output ports define the format and protocol in which data can be exposed (db, file, API, visualizations)**

The data of this data product is available under the following URLs

* [berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-district-regions.geojson)
* [berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-districts.geojson)
* [berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2015-00/berlin-lor-housing-stock-2015-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-district-regions.geojson)
* [berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-districts.geojson)
* [berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2016-00/berlin-lor-housing-stock-2016-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-district-regions.geojson)
* [berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-districts.geojson)
* [berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2017-00/berlin-lor-housing-stock-2017-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-district-regions.geojson)
* [berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-districts.geojson)
* [berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2018-00/berlin-lor-housing-stock-2018-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-district-regions.geojson)
* [berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-districts.geojson)
* [berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2019-00/berlin-lor-housing-stock-2019-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-district-regions.geojson)
* [berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-districts.geojson)
* [berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2020-00/berlin-lor-housing-stock-2020-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-district-regions.geojson)
* [berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-districts.geojson)
* [berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2021-00/berlin-lor-housing-stock-2021-00-planning-areas.geojson)
* [berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-district-regions.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-district-regions.geojson)
* [berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-districts.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-districts.geojson)
* [berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-forecast-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-forecast-areas.geojson)
* [berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-planning-areas.geojson](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-2022-00/berlin-lor-housing-stock-2022-00-planning-areas.geojson)

Additionally, statistics are available under the following URLs

* [berlin-lor-housing-stock-statistics/berlin-lor-housing-stock-statistics.json](https://raw.githubusercontent.com/open-lifeworlds/open-lifeworlds-data-product-berlin-lor-housing-stock/main/data/berlin-lor-housing-stock-statistics/berlin-lor-housing-stock-statistics.json)

## Metadata

### Ownership

**Domain, data product owner, organizational unit, license, version and expiration date**

* ownership: Open Lifeworlds
* domain: geodata
* license: CC-BY-4.0

### Schema

**Attributes, data types, constraints, and relationships to other elements**

* `apartments`: number of apartments
* `apartments_with_1_room`: number of apartments with 1 room
* `apartments_with_2_rooms`: number of apartments with 2 rooms
* `apartments_with_3_rooms`: number of apartments with 3 rooms
* `apartments_with_4_rooms`: number of apartments with 4 rooms
* `apartments_with_5_rooms`: number of apartments with 5 rooms
* `apartments_with_6_rooms`: number of apartments with 6 rooms
* `apartments_with_7_rooms_or_more`: number of apartments with 7 rooms or more
* `apartments_rooms`: number of rooms in apartments
* `apartments_living_area`: living area in apartments
* `residential_buildings`: number of residential buildings
* `residential_buildings_living_area`: living area in residential buildings
* `residential_buildings_apartments`: number of apartments in residential buildings
* `residential_buildings_with_1_apartment`: number of residential buildings with 1 apartment
* `residential_buildings_with_1_apartment_living_area`: living area of residential buildings with 1 apartment
* `residential_buildings_with_2_apartments`: number of residential buildings with 2 apartments
* `residential_buildings_with_2_apartments_living_area`: living area of residential buildings with 2 apartments
* `residential_buildings_with_2_apartments_apartments`: apartments in residential buildings with 2 apartments
* `residential_buildings_with_3_apartments`: number of residential buildings with 3 apartments
* `residential_buildings_with_3_apartments_living_area`: living area of residential buildings with 3 apartments
* `residential_buildings_with_3_apartments_apartments`: apartments in residential buildings with 3 apartments

### Semantics

**Description, logical model**

### Security

**Security rules applied to the data product usage e.g. public org, internal, personally identifiable information (PII)
attributes**

## Observability

### Quality metrics

**Requirements and metrics such as accuracy, completeness, integrity, or compliance to Data Governance policies**

Completeness of this data product is verified via [data_metrics.py](../lib/metrics/data_completeness.py).

### Operational metrics

**Interval of change, freshness, usage statistics, availability, number of users, data versioning, etc.**

### SLOs

**Thresholds for service level objectives to up alerting**

## Consumer

**Who is the consumer of the Data Product?**

Consumers of this data product may include projects that display statistical data based on LOR areas on maps or graphs.

## Use Case

**We believe that ...**
**We help achieving ...**
**We know, we are getting there based on ..., ..., ...**

We believe that this data product can be used to display statistical data related to LOR areas in Berlin on an
interactive map.

## Classification

**The nature of the exposed data (source-aligned, aggregate, consumer-aligned)**

This data product is consumer-aligned since it is meant to be used for display on maps or graphs.

## Ubiquitous Language

**Context-specific domain terminology (relevant for Data Product), Data Product polysemes which are used to create the
current Data Product**

* **LOR**: (German: Lebensweltlich orientierte Räume) life-world oriented spaces
* **district**: (German: Bezirk)
* **forecast area**: (German: Prognoseraum)
* **district region**: (German: Bezirksregion)
* **planning area**: a spatial unit whose spatial development is planned by the public authorities

---
This data product canvas uses the template
of [datamesh-architecture.com](https://www.datamesh-architecture.com/data-product-canvas).
