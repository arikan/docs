[avalanche](../README.md) › [AVMAPI-Credentials](../modules/avmapi_credentials.md) › [SecpCredential](avmapi_credentials.secpcredential.md)

# Class: SecpCredential

## Hierarchy

* [Credential](avmapi_credentials.credential.md)

  ↳ **SecpCredential**

## Index

### Constructors

* [constructor](avmapi_credentials.secpcredential.md#constructor)

### Properties

* [sigArray](avmapi_credentials.secpcredential.md#protected-sigarray)

### Methods

* [addSignature](avmapi_credentials.secpcredential.md#addsignature)
* [fromBuffer](avmapi_credentials.secpcredential.md#frombuffer)
* [getCredentialID](avmapi_credentials.secpcredential.md#getcredentialid)
* [toBuffer](avmapi_credentials.secpcredential.md#tobuffer)

## Constructors

###  constructor

\+ **new SecpCredential**(`sigarray`: Array‹[Signature](avmapi_types.signature.md)›): *[SecpCredential](avmapi_credentials.secpcredential.md)*

*Inherited from [Credential](avmapi_credentials.credential.md).[constructor](avmapi_credentials.credential.md#constructor)*

*Defined in [src/apis/avm/credentials.ts:70](https://github.com/ava-labs/avalanche.js/blob/eabcc2f/src/apis/avm/credentials.ts#L70)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`sigarray` | Array‹[Signature](avmapi_types.signature.md)› | undefined |

**Returns:** *[SecpCredential](avmapi_credentials.secpcredential.md)*

## Properties

### `Protected` sigArray

• **sigArray**: *Array‹[Signature](avmapi_types.signature.md)›* = []

*Inherited from [Credential](avmapi_credentials.credential.md).[sigArray](avmapi_credentials.credential.md#protected-sigarray)*

*Defined in [src/apis/avm/credentials.ts:35](https://github.com/ava-labs/avalanche.js/blob/eabcc2f/src/apis/avm/credentials.ts#L35)*

## Methods

###  addSignature

▸ **addSignature**(`sig`: [Signature](avmapi_types.signature.md)): *number*

*Inherited from [Credential](avmapi_credentials.credential.md).[addSignature](avmapi_credentials.credential.md#addsignature)*

*Defined in [src/apis/avm/credentials.ts:42](https://github.com/ava-labs/avalanche.js/blob/eabcc2f/src/apis/avm/credentials.ts#L42)*

Adds a signature to the credentials and returns the index off the added signature.

**Parameters:**

Name | Type |
------ | ------ |
`sig` | [Signature](avmapi_types.signature.md) |

**Returns:** *number*

___

###  fromBuffer

▸ **fromBuffer**(`bytes`: any, `offset`: number): *number*

*Inherited from [Credential](avmapi_credentials.credential.md).[fromBuffer](avmapi_credentials.credential.md#frombuffer)*

*Defined in [src/apis/avm/credentials.ts:47](https://github.com/ava-labs/avalanche.js/blob/eabcc2f/src/apis/avm/credentials.ts#L47)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`bytes` | any | - |
`offset` | number | 0 |

**Returns:** *number*

___

###  getCredentialID

▸ **getCredentialID**(): *number*

*Overrides [Credential](avmapi_credentials.credential.md).[getCredentialID](avmapi_credentials.credential.md#abstract-getcredentialid)*

*Defined in [src/apis/avm/credentials.ts:81](https://github.com/ava-labs/avalanche.js/blob/eabcc2f/src/apis/avm/credentials.ts#L81)*

**Returns:** *number*

___

###  toBuffer

▸ **toBuffer**(): *Buffer*

*Inherited from [Credential](avmapi_credentials.credential.md).[toBuffer](avmapi_credentials.credential.md#tobuffer)*

*Defined in [src/apis/avm/credentials.ts:59](https://github.com/ava-labs/avalanche.js/blob/eabcc2f/src/apis/avm/credentials.ts#L59)*

**Returns:** *Buffer*
