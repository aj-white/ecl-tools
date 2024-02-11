# ecl-tools
Collection of tools to process ECL queries

## Introduction

SNOMED Expression Constraint Language (ECL) is a way to define a set of SNOMED concepts.

For example the following means the descendents in the snomed hierarchy of the concept `Asthma`

```
<195967001 |Asthma| 
```

ECL queries can be used to return user defined subsets of snomed concepts e.g. from a terminology server.

Terminiology servers differ in the syntax that is permitted, some terminology servers do not accept human readable names surounded by the `|` operator.

This simple `ecl.html` strips the human readable names from an ECL query.

## Use

Simply copy the `ecl.html` file and open it in an internet browser. Paste the query and click `Remove Names`. Use the `Copy To Clipboard` button to easily paste the outputted ECL query into whichever terminology server i sbeing used.
