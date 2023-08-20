# Lookouts.

# Highs.

|ID  |  Title                                                                                | Severity      |
|:---| :------------------------------------------------------------------------------------| :------------ |
|H-x | Price manipulation                                         | High          |

# Mediums.

|ID  |  Title                                                                                | Severity      |
|:---| :------------------------------------------------------------------------------------| :------------ |
|M-x | Use safeTransfer & safeTransferFrom instead of transfer                                         | Medium          |

# Lows.

|ID  |  Title                                                                                | Severity      |
|:---| :------------------------------------------------------------------------------------| :------------ |
|L-x | Avoid use of hard-coded chainIds and addresses whenever possible                                         | Low          |

# Informational.

|ID  |  Title                                                                                | Severity      |
|:---| :------------------------------------------------------------------------------------| :------------ |
|I-x | Save magic numbers in variables.                                          | Informational          |

# Gas.

|ID  |  Title                                                                                | Severity      |
|:---| :------------------------------------------------------------------------------------| :------------ |
|G-x | Use calldata instead of memory whenever possible                                         | Gas          |
|G-x | Cache storage values in memory to minimise SLOADs                                         | Gas          |
|G-x | Don’t initialise variables with default values of 0                                         | Gas          |
|G-x | Default all constant variables to private. Anything that actually needs to be public should be                                         | Gas          |
|G-x | ++i/i++ should be unchecked{++i}/unchecked{i++} when it is not possible to result in an overflow                                         | Gas          |


- Twitter [@jvorex_](https://twitter.com/jvorex_)