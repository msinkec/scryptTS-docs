[scrypt-ts](../README.md) / ContractCalledEvent

# Interface: ContractCalledEvent<T\>

ContractCalledEvent is the relevant information when the contract is called, such as the public function name and function arguments when the call occurs.

## Type parameters

| Name |
| :------ |
| `T` |

## Table of contents

### Properties

- [args](ContractCalledEvent.md#args)
- [methodName](ContractCalledEvent.md#methodname)
- [nexts](ContractCalledEvent.md#nexts)

## Properties

### args

• **args**: `SupportedParamType`[]

function arguments

#### Defined in

dist/client/apis/contract-api.d.ts:30

___

### methodName

• **methodName**: `string`

name of public function

#### Defined in

dist/client/apis/contract-api.d.ts:28

___

### nexts

• **nexts**: `T`[]

If a stateful contract is called, `nexts` contains the contract instance containing the new state generated by this call.
If a stateless contract is called, `nexts` is empty.

#### Defined in

dist/client/apis/contract-api.d.ts:26
