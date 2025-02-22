[@zeldafan0225/stable_horde](../README.md) / [Exports](../modules.md) / ActiveModel

# Interface: ActiveModel

## Hierarchy

- [`ActiveModelLite`](ActiveModelLite.md)

  ↳ **`ActiveModel`**

## Table of contents

### Properties

- [count](ActiveModel.md#count)
- [eta](ActiveModel.md#eta)
- [name](ActiveModel.md#name)
- [performance](ActiveModel.md#performance)
- [queued](ActiveModel.md#queued)

## Properties

### count

• `Optional` **count**: `number`

How many workers in this horde are running this model.

#### Inherited from

[ActiveModelLite](ActiveModelLite.md).[count](ActiveModelLite.md#count)

#### Defined in

[index.ts:2092](https://github.com/MrlolDev/stable_horde/blob/07c9e41/index.ts#L2092)

___

### eta

• `Optional` **eta**: `number`

Estimated time in seconds for this model's queue to be cleared

#### Defined in

[index.ts:2085](https://github.com/MrlolDev/stable_horde/blob/07c9e41/index.ts#L2085)

___

### name

• `Optional` **name**: `string`

The name of a model available by workers in this horde.

#### Inherited from

[ActiveModelLite](ActiveModelLite.md).[name](ActiveModelLite.md#name)

#### Defined in

[index.ts:2090](https://github.com/MrlolDev/stable_horde/blob/07c9e41/index.ts#L2090)

___

### performance

• `Optional` **performance**: `number`

The average speed of generation for this model

#### Defined in

[index.ts:2081](https://github.com/MrlolDev/stable_horde/blob/07c9e41/index.ts#L2081)

___

### queued

• `Optional` **queued**: `number`

The amount waiting to be generated by this model

#### Defined in

[index.ts:2083](https://github.com/MrlolDev/stable_horde/blob/07c9e41/index.ts#L2083)
