# npm Libraries

Directory/relationship map of FGO Planner's npm libraries.
## npm-lib-data (planned)
* ### data-types
  * no imports
  * exports types only
* ### data-ops
  * imports `data-types`
  * exports db models/schemas
## npm-lib-common (planned)
* ### common-utils
  * TBD
## npm-lib-computation (planned)
* ### computation-types
  * imports `data-types`
  * exports types only
* ### computation-utils
  * imports `data-types`
  * imports `computation-types`
  * imports `transform-utils`
  * exports utility classes/function
## npm-lib-transform (planned)
* ### transform-external
  * imports `data-types`
* ### transform-utils
  * imports `data-types`
  * imports `computation-types`
  * exports utility classes/function
