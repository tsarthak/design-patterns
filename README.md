# Design patterns

## Overview

Anyone who has engaged themselves in any form of programming exercises or courses would have come along the term design patterns. Although a large portion of what that actually means is elusive. The attempt of this repository is to consolidate some of that and try to explain and understand these design patterns.

## What are design patterns?

_Design patterns_ is a software engineering term which is abstract in nature. It does not only apply to code that one writes, but extends to system design, algorithms and languages themselves. The definition says that it is a general, repeatable solution to a problem. However, it is not really a design by itself, but rather a description and a template which can be applied to a problem at hand.

It is key to note that although there are a bunch of design patterns, not all of them are valid across different languages, different programming paradigms or systems at hand. It is often the case that some languages lack features due to which a specific design pattern might exist.

## What are we dealing with here?

The work in this repository mainly deals with software design patterns and not system design patterns. Also, software programming principles being more abstract, utilise some of these design patterns (e.g. SOLID actively uses one of the creational design patterns in some languages).

## Types of design patterns

Design patterns can broadly be divided in to 3 categories

1. Creational design patterns :- These design patterns describe and control how objects and instances of any type are created. I use the word type because these could correspond to value or class types. Further, they can be divided by either class-creation patterns or instance-creation patterns. Class creation patterns rely on inheritance, where as object creation patterns rely on polymorphism and delegation.
2. Structural design patterns :- These design patterns describe composition of classes and objects. As the name suggests it structures classes based on is-a (inheritance, used for class structures) or has-a (composition, used for object structures) relationships as required.
3. Behavioral design patterns :- The name says it all. These patterns are used to control and describe communication between class objects. It essentially handles how data might flow, or conditions on which the data might be utilised by a consumer which has been emitted by a producer.

## Notes

1. It is crucial to note that design patterns are not fundamental to programming. These are more approaches to solving some problems which release code smell in some cases like deadlocks or lack of uniform interfaces. It is often found that incorrectly relying on design patterns itself leads to code smell. Hence, avoid design patterns all together when initiating your design discussions and if there are some problems which might require a "jig" or a "shim" to put together, that might be a job for a design pattern.
2. Design patterns are not all bad but not all good either. Many experts and academics discredit the validity of such tools, primarily because people use them to provide inefficient and insufficient abstraction. Another reason is that design patterns are largely ad-hoc. The classification above is not exhaustive, but it is not entirely minimal either. The definition of applicable patterns is vague, implementation is non-standard, and most certainly not algorithmically driven.


