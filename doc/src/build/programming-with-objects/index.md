---
title: Programming Objects Tutorial Series
---

Sui is a blockchain centered on [objects](../../build/objects.md). Once you start programming non-trivial [smart contracts](../../build/move/index.md) on Sui, you will start dealing with Sui objects in the code. Sui includes a rich, comprehensive library and testing framework to allow you interact with objects in a safe and yet flexible way.

In this tutorial series, we will walk through all the powerful ways to interact with objects in [Sui Move](../../learn/sui-move-diffs.md). At the end, we will also explore the designs of a few (close-to-)real-world examples to demonstrate the tradeoffs of using different object types and ownership relationships.

Note, you can find Sui Move programming examples at: https://examples.sui.io/

## Prerequisites

Understand:
- [Learn about Sui](../../learn/about-sui.md)
- [Smart Contracts with Move](../../build/move/index.md)
- [Sui Objects](../../learn/objects.md)

Install:
- [Sui binaries](../install.md#binaries)
- [Sui source code](../install.md#source-code)

## Chapters

- [Chapter 1: Object Basics](../../build/programming-with-objects/ch1-object-basics.md)
  - Defining Move object types, creating objects, transferring objects.
- [Chapter 2: Using Objects](../../build/programming-with-objects/ch2-using-objects.md)
  - Passing Move objects as arguments, mutating objects, deleting objects.
- [Chapter 3: Immutable Objects](../../build//programming-with-objects/ch3-immutable-objects.md)
  - Freezing an object, using immutable objects.
- [Chapter 4: Object Wrapping](../../build/programming-with-objects/ch4-object-wrapping.md)
  - Wrapping objects in another object.
- [Chapter 5: Dynamic Fields](../../build/programming-with-objects/ch5-dynamic-fields.md)
  - Extending objects with fields keyed on other object that can be dynamically added, accessed, and removed.
- [Chapter 6: Collections](../../build/programming-with-objects/ch6-collections.md)
  - Working with objects in on-chain homogeneous and heterogeneous key-value stores built on top of dynamic fields.
