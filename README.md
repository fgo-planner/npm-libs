# npm Libraries
Directory/relationship map of FGO Planner's custom npm packages. All of the packages and dependencies listed below use the `@fgo-planner` scope, unless marked as external.

### npm-lib-common ([repo](https://github.com/fgo-planner/npm-lib-common), [packages](https://github.com/orgs/fgo-planner/packages?repo_name=npm-lib-common))
- **common-core ([package](https://github.com/fgo-planner/npm-lib-common/pkgs/npm/common-utils))**
  - Dependencies:
    - `common-types`
    - `csv-parse` (external)
    - `date-fns` (external)
  - Re-exports:
    - `common-types`
- **common-types ([package](https://github.com/fgo-planner/npm-lib-common/pkgs/npm/common-types))**
  - No dependencies

### npm-lib-data ([repo](https://github.com/fgo-planner/npm-lib-data), [packages](https://github.com/orgs/fgo-planner/packages?repo_name=npm-lib-data))
- **data-core ([package](https://github.com/fgo-planner/npm-lib-data/pkgs/npm/data-core))**
  - Dependencies:
    - `common-core`
    - `data-types`
    - `data-test-resources` (dev)
  - Re-exports:
    - `data-types`
- **data-mongo ([package](https://github.com/fgo-planner/npm-lib-data/pkgs/npm/data-mongo))**
  - Dependencies:
    - `data-core`
    - `mongoose` (external)
  - Re-exports:
    - `data-core`
    - `data-types` (with `number` substituted by `ObjectId` where applicable)
- **data-test-resources ([package](https://github.com/fgo-planner/npm-lib-data/pkgs/npm/data-test-resources))**
  - Dependencies:
    - `common-types`
    - `data-types`
- **data-types ([package](https://github.com/fgo-planner/npm-lib-data/pkgs/npm/data-types))**
  - No depndencies

### npm-lib-transform ([repo](https://github.com/fgo-planner/npm-lib-transform), [packages](https://github.com/orgs/fgo-planner/packages?repo_name=npm-lib-transform))
- **transform-core ([package](https://github.com/fgo-planner/npm-lib-transform/pkgs/npm/transform-core))**
  - Dependencies:
    - `common-core`
    - `data-core`
    - `date-fns` (external)
    - `data-test-resources` (dev)

### npm-lib-computation (TBD)
- **computation-core (TBD)**
