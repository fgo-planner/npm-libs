# npm Libraries
Directory/relationship map of FGO Planner's custom npm packages. All of the packages below use the `@fgo-planner` scope.
### npm-lib-data ([repo](https://github.com/fgo-planner/npm-lib-data))
* **data-types**
  * no imports
  * exports types only
* **data-mongo**
  * imports `data-types`
  * exports Mongo (Mongoose) models and schemas
### npm-lib-common (planned)
* **common-utils**
  * TBD
### npm-lib-computation (planned)
* **computation-types**
  * imports `data-types`
  * exports types only
* **computation-utils**
  * imports `data-types`
  * imports `computation-types`
  * imports `transform-utils`
  * exports utility classes/function
### npm-lib-transform (planned)
* **transform-external**
  * imports `data-types`
* **transform-utils**
  * imports `data-types`
  * imports `computation-types`
  * exports utility classes/function
