# Lookouts.

# Highs.

|ID  |  Title                                                                                | Severity      |
|:---| :------------------------------------------------------------------------------------| :------------ |
|H-x| Price manipulation                                         | High          |

# Mediums.

|ID  |  Title                                                                                | Severity      |
|:---| :------------------------------------------------------------------------------------| :------------ |
|M-x| Use safeTransfer & safeTransferFrom instead of transfer                                         | Medium          |

# Lows.

|ID  |  Title                                                                                | Severity      |
|:---| :------------------------------------------------------------------------------------| :------------ |
|L-x| Avoid use of hard-coded chainIds and addresses whenever possible                                         | Low          |

# Informational.

|ID  |  Title                                                                                | Severity      |
|:---| :------------------------------------------------------------------------------------| :------------ |
|I| Save magic numbers in variables.                                          | Informational          |
|I| Follow CEI pattern. Emit events when necessary                                          | Informational          |
|I| Remove unused/redundant imports                                          | Informational          |
|I| No need for SafeMath when compiler version is ^0.8.0 as it has in-built under/overflow checks                                          | Informational          |
|I| Add non-zero address checks for all address type arguments                                          | Informational          |
|I| Declare modifiers before functions                                          | Informational          |
|I| Use custom errors instead of require statements whenever possible                                          | Informational          |
|I| Emit events in crucial places                                         | Informational          |
|I| Get rid of redundant functions                                         | Informational          |
|I| Prevent approvals to zero address                                         | Informational          |
|I| Don’t miss/mix up  licenses                                         | Informational          |
|I| Add NatSpec docs to all public methods, variables and functions                                         | Informational          |
|I| Import declaration should import specific identifiers rather than whole file whenever possible                                         | Informational          |
|I| Shoot for more than 80% of test coverage reports                                         | Informational          |

# Gas.

|ID  |  Title                                                                                | Severity      |
|:---| :------------------------------------------------------------------------------------| :------------ |
|G| Use calldata instead of memory whenever possible                                         | Gas          |
|G| Cache storage values in memory to minimise SLOADs                                         | Gas          |
|G| Don’t initialise variables with default values of 0                                         | Gas          |
|G| Default all constant variables to private. Anything that actually needs to be public should be                                         | Gas          |
|G| ++i/i++ should be unchecked{++i}/unchecked{i++} when it is not possible to result in an overflow                                         | Gas          |


- Twitter [@jvorex_](https://twitter.com/jvorex_)