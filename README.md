# Google Shopping Product Information

> Descriptions for each item including pruduct number, general description, product name (title), brand, category by name, age and player count, and specs (part number and GTIN)

## Related Projects

  - https://github.com/SDC-Musical/reviews-service
  - https://github.com/SDC-Musical/seller-catalog
  - https://github.com/SDC-Musical/images-service
  - https://github.com/SDC-Musical/Product-Info-Kimarie

## Table of Contents

1. [Usage](#Usage)
2. [Requirements](#Requirements)
3. [Development](#Development)
4. [Product-API](#Product-API)

## Usage

Execute db/models/schema.sql from command line with:
  `mysql -u root < db/models/schema.sql`

## Requirements

An `nvmrc` file is included if using [nvm](https://github.com/creationix/nvm).

- Node 6.13.0
- etc

## Development

## Product-API
**CRUD**
- POST /create creates a new product
- GET products/:product_id returns the product associated with that id number
- GET brand/:brand returns an array of products of that brand
- PUT /update/:product_id updates the product at that id with the given information
- DELETE /delete/:product_id removes the product at that id from the collection

**CROSSORIGIN REQUESTS**



### Installing Dependencies

From within the root directory:

```sh
npm install -g webpack
npm install
```

