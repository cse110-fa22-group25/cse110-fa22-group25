# Filtering Simplification

## Context and Problem Statement

Should we simplify filtering for easier implementation?

Would categories and subcategories be too difficult to implement filtering?

Would collapsing different categories be too difficult to implement given the time?

## Considered Options

* Use categories and subcategories
* Only allow major categories

## Decision Outcome

Simplify to only allow major categories. A landlord isn't going to be keeping track of their tenants' iphone warranties. 

Display all items in one big tile grouping as shown in the current draft of Yong's wireframe. This is easier to implement as we do not need to consider collapsing groups and can easily filter based on groups. 