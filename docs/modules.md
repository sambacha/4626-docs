[solidity-hardhat-template](README.md) / Exports

# solidity-hardhat-template

## Table of contents

### Classes

- [ERC4626Router](classes/ERC4626Router.md)

### Interfaces

- [ERC4626RouterInterface](interfaces/ERC4626RouterInterface.md)

### Type aliases

- [ApprovalEvent](modules.md#approvalevent)
- [DepositEvent](modules.md#depositevent)
- [TransferEvent](modules.md#transferevent)
- [WithdrawEvent](modules.md#withdrawevent)

## Type aliases

### ApprovalEvent

Ƭ **ApprovalEvent**: `TypedEvent`<[`string`, `string`, `BigNumber`] & { `amount`: `BigNumber` ; `owner`: `string` ; `spender`: `string`  }\>

#### Defined in

types/ethers-contracts/ERC4626Router.d.ts:220

___

### DepositEvent

Ƭ **DepositEvent**: `TypedEvent`<[`string`, `string`, `BigNumber`, `BigNumber`] & { `assets`: `BigNumber` ; `caller`: `string` ; `owner`: `string` ; `shares`: `BigNumber`  }\>

#### Defined in

types/ethers-contracts/ERC4626Router.d.ts:228

___

### TransferEvent

Ƭ **TransferEvent**: `TypedEvent`<[`string`, `string`, `BigNumber`] & { `amount`: `BigNumber` ; `from`: `string` ; `to`: `string`  }\>

#### Defined in

types/ethers-contracts/ERC4626Router.d.ts:237

___

### WithdrawEvent

Ƭ **WithdrawEvent**: `TypedEvent`<[`string`, `string`, `string`, `BigNumber`, `BigNumber`] & { `assets`: `BigNumber` ; `caller`: `string` ; `owner`: `string` ; `receiver`: `string` ; `shares`: `BigNumber`  }\>

#### Defined in

types/ethers-contracts/ERC4626Router.d.ts:241
