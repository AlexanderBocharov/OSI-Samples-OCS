# OSIsoft OCS Samples

OSIsoft Cloud Services ([OCS](https://www.osisoft.com/Solutions/OSIsoft-Cloud-Services/)) is a highly flexible cloud-based platform that provides scalable, elastic,
centralized environment to aggregate data for reporting, advanced analytics, and third-party applications. OCS is powered by OSIsoft's Sequential Data Store (SDS). In this GitHub repo, we provide samples which will help you get started with the [OCS API](https://ocs-docs.osisoft.com/) against your [OCS instance](https://cloud.osisoft.com/welcome).

If you are interested in other OSIsoft samples please see [OSIsoft Samples](https://github.com/osisoft/OSI-Samples).

There is currently one type of sample in the repo:

- ![getting-started icon](miscellaneous/images/app-type-getting-started.png) Getting Started - OCS focused samples for a task, usually implemented as a simple console app or single page application. There are also base libraries that may be used in other apps.

- ![ctp icon](miscellaneous/images/ctp.png) This task and code uses services that are currently in preview. If you are interested in this functionality, please contact OCS support.

The official OCS samples are divided in multiple categories depending on the scenario and problem/task, accessible through the following table:

| Task                                                                                                                                                                                   | Description                                                                                                                                                                                                                                                                                                                                                                                                                        | Languages                                                                                                                                                                                                                                                                                                            | Test Status                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **[Authentication - Client Credentials](basic_samples/Authentication/ClientCredentialFlow)** ![getting-started icon](miscellaneous/images/app-type-getting-started.png)                | Click for [details](basic_samples/Authentication) on this type of authentication                                                                                                                                                                                                                                                                                                                                                   | [.NET](.basic_samples/Authentication/ClientCredentialFlow/DotNet)                                                                                                                                                                                                                                                    | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/Auth_CC_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=595&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **[Authentication - Hybrid Flow](.basic_samples/Authentication/HybridFlow/DotNet)** ![getting-started icon](miscellaneous/images/app-type-getting-started.png)                         | Click for [details](basic_samples/Authentication) on this type of authentication                                                                                                                                                                                                                                                                                                                                                   | [.NET](basic_samples/Authentication/HybridFlow/DotNet)                                                                                                                                                                                                                                                               | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/Auth_Hybrid_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=847&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **[Authentication - Authorization Code + PKCE](basic_samples/Authentication/AuthorizationCodeFlow/DotNet)** ![getting-started icon](miscellaneous/images/app-type-getting-started.png) | Click for [details](basic_samples/Authentication) on this type of authentication                                                                                                                                                                                                                                                                                                                                                   | [.NET](basic_samples/Authentication/AuthorizationCodeFlow/DotNet) </br> [JavaScript](basic_samples/Authentication/AuthorizationCodeFlow/JavaScript) </br> [PowerBI](.\basic_samples/Authentication/AuthorizationCodeFlow/PowerBI) </br> [Python](.\basic_samples/Authentication/AuthorizationCodeFlow/Python)        | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/Auth_PKCE_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=863&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/Auth_PKCE_JavaScript?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=1203&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/Auth_PKCE_PowerBI?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=996&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/Auth_PKCE_Python?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=1551&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **[Types, Streams, and retrieving Data -- WaveForm](basic_samples/SDS)** ![getting-started icon](miscellaneous/images/app-type-getting-started.png)                                    | Covers some typical operations against the SDS, including client credential authentication, creating, updating, and deleting types, streams and events. This uses a non-time Series Type. Some tasks are different from the other "Types, Streams, and retrieving Data" task, so look at the task readme for details. This is a recommended starting example, and a good a base for all other Tasks. [Details](basic_samples/SDS)  | [.NET Libraries](basic_samples/SDS/DotNet/SdsClientLibraries) </br> [.NET REST API](basic_samples/SDS/DotNet/SdsRestApiCore) </br> [Java](basic_samples/SDS/Java) </br> [Angular](basic_samples/SDS/JavaScript/Angular) </br> [NodeJS](basic_samples/SDS/JavaScript/NodeJS) </br> [Python](basic_samples/SDS/Python) | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_DotNet_Libs?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=887&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_DotNet_REST?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=888&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_Java?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=920&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_Angular?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=921&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_NodeJs?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=924&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_Python?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=925&branchName=master) |
| **[Types, Streams, and retrieving Data -- Time-Series](basic_samples/SDS_TimeSeries)** ![getting-started icon](miscellaneous/images/app-type-getting-started.png)                      | Covers some typical operations against the SDS, including client credential authentication, creating, and deleting types and streams. This sample is based on Time-Series data. Some tasks are different from the other "Types, Streams, and retrieving Data" task, so look at the task readme for details. This is a recommended starting example, and a good a base for all other Tasks. [Details](basic_samples/SDS_TimeSeries) | [Python](basic_samples/SDS_TimeSeries/Python) </br> [DotNet](basic_samples/SDS_TimeSeries/DotNet/Try)                                                                                                                                                                                                                | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_TS_Python?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=927&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/SDS_TS_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=926&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **[UOM](advanced_samples/UomsSample/Dotnet/UomsSample/UomsSample)** ![getting-started icon](miscellaneous/images/app-type-getting-started.png)                                         | Covers the basic functionality of the UOM system on OCS                                                                                                                                                                                                                                                                                                                                                                            | [.NET](advanced_samples/UomsSample/DotNet)                                                                                                                                                                                                                                                                           | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/UOM_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=928&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **[OMF Ingress](basic_samples/OmfIngress/DotNet/OmfIngressClientLibraries/OmfIngressClientLibraries)** ![getting-started icon](miscellaneous/images/app-type-getting-started.png)      | Covers the basic functionality of configuring and using the OMF Ingress                                                                                                                                                                                                                                                                                                                                                            | [.NET](basic_samples/OmfIngress/DotNet)</a>                                                                                                                                                                                                                                                                          | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/OMF_Ing_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=886&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **[CSV to OCS](advanced_samples/CSV/dotnet/CSVtoOCS)</a>**                                                                                                                             | Shows how to send a basic csv file to OCS using SDS calls                                                                                                                                                                                                                                                                                                                                                                          | [.NET](advanced_samples/CSV/dotnet/CSVtoOCS)                                                                                                                                                                                                                                                                         | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/CSVtoOCS_DotNet?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=1393&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **[Sample Libraries](library_samples)** ![getting-started icon](miscellaneous/images/app-type-getting-started.png)                                                                     | These sample libraries are used as the base for the other samples. They are designed to be straightforward implementations of the REST APIs. They are for use in the samples. [Details](library_samples)                                                                                                                                                                                                                           | [Java](library_samples/Java) </br> [Python](library_samples/Python)                                                                                                                                                                                                                                                  | ~~~~~~~~~~~~~~~~~~~ </br> ~~~~~~~~~~~~~~~~~~~                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| ![ctp icon](miscellaneous/images/ctp.png) **[Data Views](basic_samples/DataViews)** ![getting-started icon](miscellaneous/images/app-type-getting-started.png)                         | These samples highlight basic operations of Data Views for OCS, including creation, updating, getting data from and deletion of Data Views. [Details](basic_samples/DataViews)                                                                                                                                                                                                                                                     | [Java](basic_samples/DataViews/Java) </br> [Python](basic_samples/DataViews/Python)                                                                                                                                                                                                                                  | [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/DataViews_Java?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=884&branchName=master) </br> [![Build Status](https://dev.azure.com/osieng/engineering/_apis/build/status/product-readiness/OCS/DataViews_Python?branchName=master)](https://dev.azure.com/osieng/engineering/_build/latest?definitionId=885&branchName=master)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |

~~ These libraries are tested by being used in other apps.

**Note**: Tests with automated UI browser components (such as Hybrid Authentication, Authorization Code Flow and Angular samples) fail intermittently due to automatation issues.

For OMF to OCS samples please see the OMF repository: [OSIsoft-Samples--OMF](https://github.com/osisoft/OSIsoft-Samples--OMF)

## Credentials

A credential file is used in the samples unless otherwise noted in the sample. The name and location of the credential file should be noted in the sample's readme.  
**Note**: This is not a secure way to store credentials. This is to be used at your own risk.  
You will need to modify these files locally when you run the samples.

## About this repo

The [style guide](https://github.com/osisoft/OSI-Samples/blob/master/STYLE_GUIDE.md) describes the organization of the repo and the code samples provided. The [test guide](https://github.com/osisoft/OSI-Samples/blob/master/TEST_GUIDE.md) goes into detail about the included automated tests. The [on prem testing](https://github.com/osisoft/OSI-Samples/blob/master/miscellaneous/ON_PREM_TESTING.md) document describes the software installed on our internal OSIsoft build agent.

## Feedback

If you have a need for a new sample; if there is a feature or capability that should be demonstrated; if there is an existing sample that should be in your favorite language; please reach out to us and give us feedback at [https://feedback.osisoft.com](https://feedback.osisoft.com) under the OSIsoft GitHub Channel. [Feedback](https://feedback.osisoft.com/forums/922279-osisoft-github).

## Support

If your support question or issue is related to something with an OSIsoft product (an error message, a problem with product configuration, etc...), please open a case with OSIsoft Tech Support through myOSIsoft Customer Portal ([https://my.osisoft.com](https://my.osisoft.com)).

If your support question or issue is related to a non-modified sample (or test) or documentation for the sample; please email Samples@osisoft.com.

## Contributions

If you wish to contribute please take a look at the [contribution guide](https://github.com/osisoft/OSI-Samples/blob/master/CONTRIBUTING.md).

## License

[OSI Samples](https://github.com/osisoft/OSI-Samples) are licensed under the [Apache 2 license](LICENSE).
