<a href="https://www.cortex-ia.co.uk/" target="_blank"><img src="https://github.com/CortexIATest/CTXImages/blob/master/Cortex-350-120.png" alt="Welcome to Cortex!" width="350" height="120" border="0"></a>

# CTX-Logging
This module contains a Cortex subtask which allows users to log information to the database in a structured format

## Table of Contents
1) [Dependencies](#dependencies)
    * [Cortex Version](#cortex-version)
    * [OCIs](#ocis)
    * [Files](#files)
    * [Other](#other)
1) [Support and Warranty](#support-and-warranty)
1) [Installation](#installation)
1) [How to use](#how-to-use)
1) [How you can contribute](#how-you-can-contribute)
1) [Versioning](#versioning)
1) [Licensing](#licensing)

## Dependencies
### Cortex Version
This version of the CTX-Logging module was developed in Cortex v6.4.0. Some functionality may not be available in other verions of Cortex.

### OCIs
The CTX-Logging module requires a SQL database

### Files
The CTX-Logging module requires the following files:
* [CTX-Logging Studio Package](https://github.com/CortexIntelligentAutomation/CTX-Logging/releases/download/v2.3/CTX-Logging.studiopkg)
* [CTX-Logging Database create script](https://github.com/CortexIntelligentAutomation/CTX-Logging/releases/download/v2.3/Cortex-Logging-Install.sql)

### Other
The CTX-Logging module has no additional requirements

## Support and Warranty 
This module is supplied as a template that you can amend and extend to fit your requirements, as such it is not supported as part of the Cortex Product suite under the Cortex product support agreement.

## Installation
Details of how the module should be imported into Cortex can be found in the [Deployment Plan](https://github.com/CortexIntelligentAutomation/CTX-Logging/blob/master/CTX-Logging%20-%20Deployment%20Plan.pdf).

## How to use
A detailed User Guide has been provided with instructions on how to use the module, available [here](https://github.com/CortexIntelligentAutomation/CTX-Logging/blob/master/CTX-Logging%20-%20User%20Guide.pdf). Configuring the subtask's inputs and outputs are detailed in notes on the subtask workspace.

## How you can contribute
Unfortunately, we cannot offer pull requests at this time or accept any improvements.

## Versioning
The CTX-Logging module has the following versions, starting with the most recent:

Version | Release | Functionality | Notes
------------ | ------------- | ----------- | -----------
v1.0 | 04/12/2018 | Cortex logging | Created
v2.0 | 11/03/2019 | Cortex logging | Implemented SQL Table Partitioning. <br/>Updated SQL Procedures and Subtask.<br/>This is a breaking change from v1.0 due to DB Schema and Subtask changes.
v2.1 | 05/06/2019 | Cortex logging | Fixed User issue in SQL Script and updated Documentation (language)
v2.2 | 05/06/2019 | Cortex logging | Bug Fixes and additional free-usage column 'ProcessData'
v2.3 | 01/07/2021 | Cortex logging | Bug Fixes, replication implementation, stored procedure updates.

## Licensing
All functionality within this module is licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0).

Copyright 2018 Cortex Limited

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
