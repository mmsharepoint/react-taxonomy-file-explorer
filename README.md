# React Taxonomy File Explorer

## Summary

This solution renders a given Termset as a Tree and incorporates files similar than a folder structure in file explorer. Benefit: Due to multiple selection in the managed metadata column the same file can occur more than once.
Additionally with drag and drop options the file can be changed:
- By replacing the managed metadata column with the target term (Move)
- By adding the target term to the managed metadata column (Link)
- By copying the file to a new one with (only) the target term in the managed metadata column (Copy)

In action this looks like:

Link:

![Adding the target term to the managed metadata column (Link)](./assets/03Link.gif)

Move:

![Replacing the managed metadata column with the target term (Move)](./assets/04Move.gif)

Copy:

![Copying the file to a new one with (only) the target term in the managed metadata column (Copy)](./assets/05Copy.gif)

## Used SharePoint Framework Version

![version](https://img.shields.io/badge/version-1.13-green.svg)

## Applies to

- [SharePoint Framework](https://aka.ms/spfx)
- [Microsoft 365 tenant](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant)

> Get your own free development tenant by subscribing to [Microsoft 365 developer program](http://aka.ms/o365devprogram)

## Prerequisites

- A hierarchical Termset bound to a managed metadata column
- A document library using that managed metadata column and several documents with selected terms

## Solution

Solution|Author(s)
--------|---------
react-taxonomy-file-explorer| [Markus Moeller](https://github.com/mmsharepoint) ([@moeller2_0](http://www.twitter.com/moeller2_0))

## Version history

Version|Date|Comments
-------|----|--------
1.0|December 26, 2021|Initial release

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Minimal Path to Awesome

- Clone this repository
- Ensure that you are at the solution folder
- in the command-line run:
  - **npm install**
  - **gulp serve**

> Include any additional steps as needed.

## Features

This web part illustrates the following concepts:

- Use HTML5 drag and drop event handling
- Update Managed Metadata columns with PnPJS
- 
- [FluentUI Contextual Menu](https://developer.microsoft.com/en-us/fluentui#/controls/web/contextualmenu)


## References

- [Getting started with SharePoint Framework](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/set-up-your-developer-tenant)
- [Building for Microsoft teams](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/build-for-teams-overview)
- [Use Microsoft Graph in your solution](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/web-parts/get-started/using-microsoft-graph-apis)
- [Publish SharePoint Framework applications to the Marketplace](https://docs.microsoft.com/en-us/sharepoint/dev/spfx/publish-to-marketplace-overview)
- [Microsoft 365 Patterns and Practices](https://aka.ms/m365pnp) - Guidance, tooling, samples and open-source controls for your Microsoft 365 development

## Help


We do not support samples, but this community is always willing to help, and we want to improve these samples. We use GitHub to track issues, which makes it easy for  community members to volunteer their time and help resolve issues.

If you're having issues building the solution, please run [spfx doctor](https://pnp.github.io/cli-microsoft365/cmd/spfx/spfx-doctor/) from within the solution folder to diagnose incompatibility issues with your environment.

You can try looking at [issues related to this sample](https://github.com/pnp/sp-dev-fx-webparts/issues?q=label%3A%22sample%3A%20react-teams-graph-upload-as-pdf") to see if anybody else is having the same issues.

You can also try looking at [discussions related to this sample](https://github.com/pnp/sp-dev-fx-webparts/discussions?discussions_q=react-teams-graph-upload-as-pdf) and see what the community is saying.

If you encounter any issues while using this sample, [create a new issue](https://github.com/pnp/sp-dev-fx-webparts/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Abug-suspected%2Csample%3A%20react-teams-graph-upload-as-pdf&template=bug-report.yml&sample=react-teams-graph-upload-as-pdf&authors=@mmsharepoint&title=react-teams-graph-upload-as-pdf%20-%20).

For questions regarding this sample, [create a new question](https://github.com/pnp/sp-dev-fx-webparts/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Aquestion%2Csample%3A%20react-teams-graph-upload-as-pdf&template=question.yml&sample=react-teams-graph-upload-as-pdf&authors=@mmsharepoint&title=react-teams-graph-upload-as-pdf%20-%20).

Finally, if you have an idea for improvement, [make a suggestion](https://github.com/pnp/sp-dev-fx-webparts/issues/new?assignees=&labels=Needs%3A+Triage+%3Amag%3A%2Ctype%3Aenhancement%2Csample%3A%20react-teams-graph-upload-as-pdf&template=suggestion.yml&sample=react-teams-graph-upload-as-pdf&authors=@mmsharepoint&title=react-teams-graph-upload-as-pdf%20-%20).