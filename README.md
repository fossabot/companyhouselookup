## Introduction
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fparj%2Fcompanyhouselookup.svg?type=shield)](https://app.fossa.io/projects/git%2Bgithub.com%2Fparj%2Fcompanyhouselookup?ref=badge_shield)


This is a pet project that I have written to integrate with the UK company house -> https://beta.companieshouse.gov.uk/search/companies

## To get this compiled on your PC

### Pre-requisities

You need 

* java 8+ installed 
* API key from company house. This can be obtained from https://developer.companieshouse.gov.uk/api/docs/

### Compilation steps

 * Clone the code
 * Set environment variable - `API_COMPANYHOUSE_KEY` with the api key. Example for Unix - `export API_COMPANYHOUSE_KEY='mylovelykey'`. For Windows - `set API_COMPANYHOUSE_KEY="mylovelykey"`
 * Run `./mvnw package`. 



## License
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fparj%2Fcompanyhouselookup.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fparj%2Fcompanyhouselookup?ref=badge_large)