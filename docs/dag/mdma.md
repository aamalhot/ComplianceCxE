# M365 DLP Migration Assistant


## What is M365 DLP Migration Assistant?

The MDMA tool is a Windows based desktop application that will migrate your DLP policies from other DLP platforms to our Unified DLP platform. 
Our tool takes you through a simple five-step migration process. It accepts Symantec DLP policy XML exports, performs mapping, and creates equivalent Unified DLP policies through PowerShell scripts.
You can safely use the MDMA tool to create DLP policies in test mode, which does not affect your live data or interact with current environment. 

## Migration tasks that M365 DMA performs

MDMA takes over many of the difficult or tedious tasks involved in a DLP migration project:

* In traditional migration scenario, you need to perform feasibility analysis between source & target DLP platforms, map features, migrate policies manually, and test and tweak DLP policies. Your migrated DLP policies can be up and running within minutes of starting the M365 DMA process.

* With M365 DMA, you can scale up your migration project quickly from moving a single policy manually to multiple policies at the same time.

* M365 DMA automatically identifies Sensitive Information Types (SITs) or Data Identifiers in source policies and creates Custom SITs in your Microsoft tenant moving over all your custom regular expressions and keywords in a few clicks.

* M365 DMA detects which conditions, exclusions & actions are currently being used in source policies and automatically creates new rules with the same conditions, exclusions & actions.

* M365 DMA provides you with a detailed migration report with policy wise migration status and recommendations.

* M365 DMA ensures that your DLP policy migration project is completely private and takes place within the boundaries of your organization.

* M365 DMA supports policy migration from Symantec Data Loss Prevention 15.7 or earlier.

### How does MDMA work?
![image](https://user-images.githubusercontent.com/52564314/138813155-645a8179-ec31-4f7c-ba71-81f921715642.png)

During a given instance of migration, the M365 DLP Migration Assistant works in **five** phases:

1. **Input**: MDMA ingests one or more Symantec DLP policy XML files.
2. **Analyze**: MDMA interprets the files & identifies Symantec DLP policy constructs.
3. **Rationalize**: MDMA maps the identified Symantec DLP policy constructs to Unified DLP capabilities. It performs validations for Unified DLP platform limitations.
4. **Migrate**: MDMA executes PowerShell scripts for the DLP scenarios identified & supported by the UDLP platform. 
5. **Reporting**: MDMA provides the user with a detailed migration report about which policies were migrated successfully, partially and/or not migrated. It also provides recommendations to improve the migration fidelity further.

## Download Process
Use the GitHub link to download the tool and follow instructions for how to install, run and configure the tool.

## Provide Feedback & Report Bugs
Please report errors, share feedback & any feature requests with us by opening a new issue in this Github repository. Alternatively, you can reach out to us at cxe-help@microsoft.com or via your CXE / Fasttrack / Microsoft partner to share your feedback and suggestions.
