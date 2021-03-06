# WMaticWrapBridge

Inherits from [IWMaticWrap](https://docs.indexpool.org/developer/bridges/interfaces/iwmaticwrap). See code on [github](https://github.com/indexpool/indexpool-contracts/blob/main/contracts/bridges/trusted/WMaticWrapBridge/WMaticWrapBridge.sol).

## Wrap

Convert MATIC into WMATIC.

| **Input Name** | **Description**                                                                |
| -------------- | ------------------------------------------------------------------------------ |
| percentageIn   | Percentage of the balance of the MATIC that will be converted  (100000 = 100%) |

```javascript
function wrap(uint256 poolId, uint256 percentage) external;
```

## Unwrap

Convert WMATIC into MATIC.

| **Input Name** | **Description**                                                     |
| -------------- | ------------------------------------------------------------------- |
| percentageOut  | Percentage of the balance of WMATIC to be converted (100000 = 100%) |

```javascript
function unwrap(uint256 poolId, uint256 percentageOut) external;
```

