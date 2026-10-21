[Home - Workshops about the ABAP Cloud development model (ABAP Cloud)](https://github.com/SAP-samples/abap-platform-rap-workshops/blob/main/README.md)

[![REUSE status](https://api.reuse.software/badge/github.com/SAP-samples/abap-platform-ad160)](https://api.reuse.software/info/github.com/SAP-samples/abap-platform-ad160)

# AD160 (aka RAP130) - Build apps and web APIs with ABAP Cloud using agentic AI
## Description

This repository contains the material for the hands-on session **AD160 (aka RAP130) - Build apps and web APIs with ABAP Cloud using agentic AI**.

You will build a transactional SAP Fiori elements app for travel management using the **ABAP RESTful Application Programming Model (RAP)** — entirely from **Visual Studio Code** that contains the installed [**ABAP Development Tools for VS Code**](https://marketplace.visualstudio.com/items?itemName=SAPSE.adt-vscode) extension, powered by the **ADT MCP Server** to generate and enhance your application.

**Table of Content**
- [Requirements](#requirements)
- [Overview](#overview)
- [Exercises](#exercises)
- [Known Issues](#known-issues)
- [How to obtain support](#how-to-obtain-support)
- [Further Information](#further-information)

<!--
## Requirements

To complete the practical exercises, you need:

> - Download and install [**Visual Studio Code** (VS Code)](https://code.visualstudio.com) in accordance to your operating system.
> - Download and install the **ABAP Development Tools extension** (a.k.a. ABAP development tools for Visual Studio Code—that includes the built-in ADT MCP Server—from the [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=SAPSE.adt-vscode).  
> ℹ️ **Note**:  The extension already contains the built-in ADT MCP Server. The installation steps are described in the tutorial [ABAP Development Tools for Visual Studio Code](https://developers.sap.com/tutorials/abap-environment-adt-vscode?from=abap-development-tools-for-visual-studio-code). Ensure that you have completed this tutorial in advance.  
> **IMPORTANT!** ℹ️ 
> - Install a **coding agent** extension in Visual Studio Code that supports a virtual workspace file system. It is required to call ADT MCP tools and read/edit ABAP files. 
> A **coding agent** extension in Visual Studio Code that supports Visual Studio Code's virtual workspace filesystem — required to call MCP tools and read/edit ABAP files. 
 > ℹ️ **Note**:  **GitHub Copilot** is the primary tested agent and the one used and recommended for this tutorial.

> - Connect your client with the ABAP system* by creating and adding a destination to your workspace.  
> ℹ️ **Note**:  (*) Only SAP Business AI ABAP environment, SAP S/4HANA Cloud Public Edition, SAP S/4HANA Cloud Private 2025, 2023, 2022, 2021 Edition are currently supported.

>- Ensure that [SAP Joule for developers, ABAP AI capabilities](https://me.sap.com/notes/3571857) has been enabled.  
>- Ensure that the [ABAP Flight Reference Scenario](https://github.com/SAP-samples/abap-platform-refscen-flight) has been imported using abapgit and the data has been generated.
-->

>> #### ⚠ Exception regarding SAP-led events, such as "ABAP Developer Day", "SAP TechEd", "SAP CodeJam", and so on:
>> → A dedicated ABAP system* for the hands-on session participants will be provided.  
>> → At dedicated SAP events, SAP will provide laptops. In this case, all the relevant software is already installed. This also includes a license for **GitHub Copilot** extension as **coding agend** in Visual Studio Code.  
>> → Access to the ABAP system* details for the session will be provided by the SAP instructors during the session.


## Overview

> In this hands-on session, you will learn how to use the **ADT MCP Server** to build a transactional SAP Fiori elements app entirely from Visual Studio Code an the ABAP Development Tools for Visual Studio Code extension — using AI-powered generation, code enhancement, and ABAP Unit test support — powered by ABAP Cloud and the ABAP RESTful Application Programming Model (RAP).

<details>
  <summary>🔵 Click to expand!</summary>

  This hands-on session covers the full developer journey from the setup of a Visual Studio Code environment to a fully functional, AI-enhanced transactional app.
 > You need to ...
  <!-- - Set up Visual Studio Code with the ADT for Visual Studio Code extension and connect it to your ABAP system*.-->
  - Connect ADT for VS Code extension to the ABAP system.
  - Verify the built-in **ADT MCP Server** enablement in the settings and its connection to the **coding agent**. 
  - Use ADT MCP tools to **generate a complete RAP UI service** (Travel + Booking) and its **OData UI service**—all through natural language prompts.
  - Explore and adjust the generated artifacts (CDS views, behavior definitions, metadata extensions) directly in Visual Studio Code.
  - Publish the service binding and preview the app in the default browser.
  - Add backend validations.  

  and optionally, to ...
  - Run ABAP Unit tests from Visual Studio Code.
  - Debugg the app from Visual Studio Code.
  - Adding the implementation of a new field to an existing RAP UI service using the **coding agent**.


</details>

## Exercises

Follow these steps to build a SAP Fiori App using the ADT MCP Server and a coding agent (GitHub Copilot or compatible) in Visual Studio Code.

| Exercises | -- |
| ------------- | -- |
| [Getting Started](exercises/ex0/README.md)| -- | 
| [Exercise 1: Get-to-Know and Verify the Enablement of the ADT MCP Server](exercises/ex01/README.md) | -- | 
| [Exercise 2: Generate the SAP Fiori App via MCP Tools](exercises/ex02/README.md) | -- | 
| [Exercise 3: Publish and Preview the Travel App](exercises/ex03/README.md)| -- |
| [Exercise 4: Add a Validation](exercises/ex04/README.md)| -- |
| [Exercise 5: Generate ABAP Unit Tests](exercises/ex05/README.md)| -- |

#### Optional Exercises

| Exercises | -- |
| ------------- | -- | 
| [Exercise 6: Debug ABAP Code in Visual Studio Code](exercises/ex06/README.md)| -- |
| [Exercise 7: Add a Field to the Existing RAP UI Service](exercises/ex07/README.md) | -- | 

<!--
## Known Issues
-->

## How to obtain support

This session is managed by several experts of SAP. Please raise your hand if you have any questions. An expert will then come to you.

<!--
[Create an issue](https://github.com/SAP-samples/abap-platform-ad160/issues) in this repository if you find a bug or have questions about the content.
 
For additional support, [ask a question](https://answers.sap.com/questions/ask.html) or see [ABAP Development](https://pages.community.sap.com/topics/abap) in SAP Community.

-->

## Further Information

You can find more information about ABAP AI, ABAP Cloud, RAP, and ADT for Visual Studio Code here:

- [AI in ABAP Cloud](https://help.sap.com/docs/abap-ai/generative-ai-in-abap-cloud/generative-ai-in-abap-cloud?locale=en-US)
- [Agentic AI for ABAP Development](https://help.sap.com/docs/abap-cloud/abap-development-tools-for-visual-studio-code/agentic-ai-development?locale=en-US)
- [ABAP Cloud Roadmap Information - GenAI](https://help.sap.com/docs/abap-cross-product/roadmap-info/genai?locale=en-US)
- [ABAP Development Tools for Visual Studio Code - Official Documentation](https://help.sap.com/docs/abap-cloud/abap-development-tools-for-visual-studio-code/abap-development-tools-for-visual-studio-code?locale=en-US)
- [ABAP Development Tools for Visual Studio Code: Everything You Need to Know](https://community.sap.com/t5/technology-blog-posts-by-sap/abap-development-tools-for-vs-code-everything-you-need-to-know/ba-p/14258129)
- [ABAP development tools for Visual Studio Code: Your Questions Answered](https://community.sap.com/t5/technology-blog-posts-by-sap/abap-development-tools-for-visual-studio-code-your-questions-answered/ba-p/14400848)
- [Behind the Design: How We Transformed the ABAP Development Tools Architecture to Support More IDEs](https://community.sap.com/t5/technology-blog-posts-by-sap/behind-the-design-how-we-transformed-the-abap-development-tools/ba-p/14258121)
- [Getting Started with ABAP RESTful Application Programming Model (RAP)](https://pages.community.sap.com/topics/abap/rap)

## Contributing
If you wish to contribute code, offer fixes or improvements, please send a pull request. Due to legal reasons, contributors will be asked to accept a DCO when they create the first pull request to this project. This happens in an automated fashion during the submission process. SAP uses [the standard DCO text of the Linux Foundation](https://developercertificate.org/).

## License
Copyright (c) 2026 SAP SE or an SAP affiliate company and abap-platform-ad160 contributors. All rights reserved. This project is licensed under the Apache Software License, version 2.0 except as noted otherwise in the [LICENSE](LICENSES/Apache-2.0.txt) file; you may not use any file of this project except in compliance with the License.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the LICENSE for the specific language governing permissions and limitations under the License.
