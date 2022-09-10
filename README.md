# npm Libraries
Directory/relationship map of FGO Planner's custom npm packages. All of the packages and dependencies listed below use the `@fgo-planner` scope, unless marked as external.

### npm-lib-common ([repo](https://github.com/fgo-planner/npm-lib-common), [packages](https://github.com/orgs/fgo-planner/packages?repo_name=npm-lib-common))
* **common-types ([package](https://github.com/fgo-planner/npm-lib-common/pkgs/npm/common-types))**
  * no dependencies
* **common-utils ([package](https://github.com/fgo-planner/npm-lib-common/pkgs/npm/common-utils))**
  * `common-types`
  * `csv-parse` (external)
  * `date-fns` (external)

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

### npm-lib-transform ([repo](https://github.com/fgo-planner/npm-lib-transform), [packages](https://github.com/orgs/fgo-planner/packages?repo_name=npm-lib-transform))
* **transform-external ([package](https://github.com/fgo-planner/npm-lib-transform/pkgs/npm/transform-external))**
  * `common-types`
  * `common-utils`
  * `data-constants`
  * `data-types`
  * `data-utils`
  * `tranform-types`
  * `date-fns` (external)
* **transform-types ([package](https://github.com/fgo-planner/npm-lib-transform/pkgs/npm/transform-types))**
  * `data-types`
* **transform-utils**
  * TBD

### npm-lib-computation (TBD)
* **computation-types**
  * TBD
* **computation-utils**
  * TBD
