# @layerzerolabs/devtools-evm-hardhat

## 0.2.10

### Patch Changes

- 9e78abe: Update hardhat-deploy
- Updated dependencies [9e78abe]
  - @layerzerolabs/io-devtools@0.1.4

## 0.2.9

### Patch Changes

- d0d1cb3: Mark hardhat tasks with exit code 1 if they were not successful

## 0.2.8

### Patch Changes

- e7ef1aa: Update @layerzero-labs dependencies to 2.1.15
- Updated dependencies [e7ef1aa]
  - @layerzerolabs/devtools-evm@0.2.7
  - @layerzerolabs/devtools@0.2.6

## 0.2.7

### Patch Changes

- b93a018: Update @layerzero-labs dependencies to 2.1.13
- Updated dependencies [b93a018]
  - @layerzerolabs/devtools-evm@0.2.6
  - @layerzerolabs/devtools@0.2.5

## 0.2.6

### Patch Changes

- 855fa36: Update to latest layerzerolabsmonorepo dependencies
- Updated dependencies [855fa36]
  - @layerzerolabs/export-deployments@0.0.3
  - @layerzerolabs/devtools-evm@0.2.5
  - @layerzerolabs/devtools@0.2.4

## 0.2.5

### Patch Changes

- 2732dfc: Add support for submitting transactions to Gnosis Safes using @safe-global
- Updated dependencies [2732dfc]
  - @layerzerolabs/devtools-evm@0.2.4

## 0.2.4

### Patch Changes

- f0392c5: Add export deployments hardhat task

## 0.2.3

### Patch Changes

- e0f41b5: Update @layerzero-labs dependencies
- Updated dependencies [e0f41b5]
  - @layerzerolabs/devtools-evm@0.2.3
  - @layerzerolabs/devtools@0.2.3

## 0.2.2

### Patch Changes

- 491b5a5: Upgrade contract Dependencies to 2.1.7
- Updated dependencies [491b5a5]
  - @layerzerolabs/devtools-evm@0.2.2
  - @layerzerolabs/devtools@0.2.2

## 0.2.1

### Patch Changes

- 71e355c: Update "@layerzerolabs/\*" dependencies
- Updated dependencies [71e355c]
  - @layerzerolabs/devtools-evm@0.2.1
  - @layerzerolabs/devtools@0.2.1

## 0.2.0

### Minor Changes

- 6e464f2: Specify EndpointV2 with the "V2" suffix wherever appropriate

### Patch Changes

- Updated dependencies [6e464f2]
  - @layerzerolabs/devtools-evm@0.2.0
  - @layerzerolabs/devtools@0.2.0

## 0.1.6

### Patch Changes

- 700168d: Move sign & send logic into a subtask

## 0.1.5

### Patch Changes

- 5675416: Fix problems with missing deployments when running lz:deploy

## 0.1.4

### Patch Changes

- 8227742: Update @layerzero-labs dependencies to 2.1.4
- 3a438b1: Compile project before depolying in lz:deploy
- Updated dependencies [8227742]
  - @layerzerolabs/devtools-evm@0.1.3
  - @layerzerolabs/devtools@0.1.4

## 0.1.3

### Patch Changes

- 5c58d69: Update @layerzerolabs dependencies to 2.1.3
- 253c79e: Add lz:deploy task; Add createClearDeployments utility
- Updated dependencies [253c79e]
- Updated dependencies [5c58d69]
  - @layerzerolabs/io-devtools@0.1.2
  - @layerzerolabs/devtools-evm@0.1.2
  - @layerzerolabs/devtools@0.1.3

## 0.1.2

### Patch Changes

- 40e8dba: Remove CommaSeparatedValuesSchema in favor of splitCommaSeparated; Move LogLevelSchema; Export isLogLevel
- Updated dependencies [40e8dba]
- Updated dependencies [4258ef3]
  - @layerzerolabs/io-devtools@0.1.1
  - @layerzerolabs/devtools@0.1.2

## 0.1.1

### Patch Changes

- f0036c5: Use monorepo 2.1.2 released dependencies
- Updated dependencies [f0036c5]
  - @layerzerolabs/devtools@0.1.1
  - @layerzerolabs/devtools-evm@0.1.1

## 0.1.0

### Minor Changes

- 120adf1: Make packages public

### Patch Changes

- Updated dependencies [120adf1]
  - @layerzerolabs/devtools-evm@0.1.0
  - @layerzerolabs/io-devtools@0.1.0
  - @layerzerolabs/devtools@0.1.0

## 0.0.11

### Patch Changes

- 17c8a23: Fix problems with --networks hardhat CLI argument parser

## 0.0.10

### Patch Changes

- 0877186: Update @layerzerolabs dependencies to 2.0.25 and 2.0.26-rc1
- Updated dependencies [0877186]
  - @layerzerolabs/devtools-evm@0.0.6
  - @layerzerolabs/devtools@0.0.5

## 0.0.9

### Patch Changes

- e5a9f35: Add hardhat CLI argument parsers for networks and for general CSV values

## 0.0.8

### Patch Changes

- 565b646: Allow project packages to specify the external artifacts and deployments in their hardhat config
- Updated dependencies [2b36ed9]
- Updated dependencies [2b36ed9]
  - @layerzerolabs/io-devtools@0.0.6

## 0.0.7

### Patch Changes

- 4318721: Fix an issue where transient artifacts would not be included in error parsing
- 4318721: Add signature to the output of lz:errors:list task
- Updated dependencies [8931fb2]
  - @layerzerolabs/devtools-evm@0.0.5

## 0.0.6

### Patch Changes

- 56706ff: Add a feature-flagged lz:deploy hasrhat task

## 0.0.5

### Patch Changes

- 1e375c9: Adding EVM testing abilities for hardhat and foundry

## 0.0.4

### Patch Changes

- af8cc25: Update dependencies
- Updated dependencies [af8cc25]
  - @layerzerolabs/devtools-evm@0.0.4
  - @layerzerolabs/io-devtools@0.0.4
  - @layerzerolabs/devtools@0.0.4

## 0.0.3

### Patch Changes

- 2183cfc: Add lz:errors:list task
- 2183cfc: Add getAllArtifacts helper
- fe1542e: Add getEidsByNetworkName utility
- Updated dependencies [5077bf1]
- Updated dependencies [5077bf1]
  - @layerzerolabs/io-devtools@0.0.3
  - @layerzerolabs/devtools-evm@0.0.3

## 0.0.2

### Patch Changes

- 5236166: Add a generic contract error parser for hardhat projects
- 6483544: Update dependency versions
- 70646b4: Add missing dependencies
- 8ac903c: Fix type extension imports for toolbox-hardhat
- Updated dependencies [e0be8b7]
- Updated dependencies [70646b4]
- Updated dependencies [b5991ca]
- Updated dependencies [2dac0da]
  - @layerzerolabs/io-devtools@0.0.2
  - @layerzerolabs/devtools-evm@0.0.2
  - @layerzerolabs/devtools@0.0.2

## 0.0.1

### Patch Changes

- b74afbe: Initial 0.0.1 version
- Updated dependencies [b74afbe]
  - @layerzerolabs/devtools-evm@0.0.1
  - @layerzerolabs/io-devtools@0.0.1

## 0.0.2

### Patch Changes

- 6964deb: Memoize create\* calls
