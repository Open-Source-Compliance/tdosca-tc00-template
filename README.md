# Test-Driven Open Source Compliance Automation Test Case No. X:

## General Context
The "Test-Driven Open Source Compliance Automation" is an initiative initiated by Deutsche Telekom AG and hosted and driven by the [Open Chain Reference Tooling Work Group](http://oss-compliance-tooling.org/).

![openchain-reference-tooling-work-group-logo.png](img/logo.png)

The project scope statement and further information of ***TDOSCA*** can be found at [https://github.com/Open-Source-Compliance/tdosca](https://github.com/Open-Source-Compliance/tdosca).

## Test Case Definition

### Structure

This test case follows the general pattern of a TDOSCA test case:
* It has its own repository [https://github.com/Open-Source-Compliance/tdosca-tc??-?????hw](https://github.com/Open-Source-Compliance/tdosca-tc??-???????)
* and contains the following parts:
  - **compliance-traps.md**: *describes the traps / challenges implemented by and in the test case* [used to manually control whether a tested compliance tool really overcomes all difficulties]
  - **input-sources**: *contains all sources to create the distributable (binary package)* [used by the tested tool to create the compliance artifacts]
  - **README.md**: *this file*
  - **reference-compliance-artifacts**: *the compliance compliance artifacts a tool (chain) must/should generate*
    - **bom.csv**: *a list of all differently licensed open source components of a package*
    - **oscf.md**: *the open source compliance file* [fulfills the compliance requirements if combined with the distributed source- or binary package]
    - **prerequisites.csv**: *a list of preinstalled tools and libs, required by the software but not delivered as part of the software package*

### Intention

TBD

## Licensing Statement

(c) 2020, TBD

* The software delivered as content of the test case directory ``input-sources`` is licensed under the licenses the test case uses to challenge the compliance tools. Contributions take place under the same licenses.

* Unless otherwise specified, all other files are distributed under the terms of the [CC-BY-4.0 license](https://creativecommons.org/licenses/by/4.0/): If you share or adapt ithis test case or files of it, please attribution: "based on [https://github.com/Open-Source-Compliance/tdosca-tc???-???](https://github.com/Open-Source-Compliance/tdosca-tc??-???) initiated by Deutsche Telekom AG"
