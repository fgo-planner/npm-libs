# npm Libraries
Directory/relationship map of FGO Planner's custom npm packages. All of the packages and dependencies listed below use the `@fgo-planner` scope, unless marked as external.
### npm-lib-data ([repo](https://github.com/fgo-planner/npm-lib-data), [packages](https://github.com/orgs/fgo-planner/packages?repo_name=npm-lib-data))
* **data-constants ([package](https://github.com/fgo-planner/npm-lib-data/pkgs/npm/data-constants))**
  * `common-types`
  * `data-types`
* **data-mongo ([package](https://github.com/fgo-planner/npm-lib-data/pkgs/npm/data-mongo))**
  * `data-types`
  * `mongoose` (external)
* **data-test-resources ([package](https://github.com/fgo-planner/npm-lib-data/pkgs/npm/data-test-resources))**
  * `common-types`
  * `data-types`
* **data-types ([package](https://github.com/fgo-planner/npm-lib-data/pkgs/npm/data-types))**
  * no dependencies
* **data-utils ([package](https://github.com/fgo-planner/npm-lib-data/pkgs/npm/data-utils))**
  * `common-types`
  * `common-utils`
  * `data-constants`
  * `data-types`
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
