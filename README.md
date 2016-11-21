# nrs-births
Data on births for calendar years relate to the date of registration of the event and not the date of occurrence. Data on births between mid points of years are based on date of occurrence and refer to the number of births which occurred between 1 July of the previous year and 30 June of the year specified in the data.

Births are counted on the basis of the area of usual residence of the mother if that is in Scotland, otherwise they are counted on the basis of the place of birth.

Statistics provided by National Records of Scotland (NRS):  http://statistics.gov.scot/data/births

## License

Data is licensed under the Open Government License: http://www.nationalarchives.gov.uk/doc/open-government-licence/version/2/

## Requirements

- NodeJS
- npm

## Installation

Clone the repository

```
git clone https://github.com/EdinburghCityScope/nrs-births.git
```

Install npm dependencies

```
cd nrs-births
npm install
```

Run the API (from the nrs-births directory)

```
node .
```

Converting the extracted data into loopback data.

```
node scripts/featureCollectionToLoopbackJson.js
```

Re-build data files from the statistics.gov.scot API

```
node scripts/build-data.js
```
