# Module

Title : Old bridge problem

Version : 1.1

## Introduction
---
There is an old, long rope bridge inside a dark cave. Groups of explorers are sent into the cave and each group needs to cross the bridge in order to continue exploring to other side of the cave. The groups are released one group at a time, and each group will be provided with one torchlight.

Since the bridge is old, only two persons are allowed to cross the bridge. Besides that, since the area is dark, each back and forth trip across the bridge requires torchlight guide. Example:
* People in a group: A, B and C
* Trip 1: A and B cross the bridge with torchlight, then A brings the torchlight back to starting location
* Trip 2: A bring C across the bridge with torchlight
* Trip finishes since all people have successfully cross the bridge.

## Description of project
---

##### Instruction

Each person will take `x` amount time to cross the bridge. Please write an algorithm that takes each `person's name` and `walking time`, and output the `person trip turn` and `total trip time` with the minimum total trip time as possible.

**Example:**

Input:

    >>> person_A = 1min
    >>> person_B = 2min
    >>> person_C = 5min
    >>> person_D = 10min

Output:

    >>> The people's turn is:
    >>> 1. person_A, person_B to end of bridge
    >>> 2. person_A to staring point
    >>> 3. person_C, person_D to end of bridge
    >>> 4. person_B to starting point
    >>> 5. person_A, person_B to end of bridge
    >>> All trips successful
    >>> Total trip time = 17 mins

## Requirement
---
- Please provide your answer in algorithm format (step by step) or in a executable program in any language.
- Your algorithm should provide the answer that can satisfy any number of people, ie write a generic algorithm that solve this optimization problem for any given number of people.
- Please provide narration/prove of why you choose to write each of the steps.

## References
---
```
- Google

Will update later - [Izzat](https://github.com/izzatinvigour) (or can request directly from the author)
```

## Contributors & Authors
---
1. [Izzat](https://github.com/izzatinvigour)