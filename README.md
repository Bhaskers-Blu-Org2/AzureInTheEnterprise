# Introduction

This is a landing for related content for customers to get started using Azure in the context of medium to large enterprises. The content is pointers to videos and other content produced by teams inside Microsoft, from Core Services Engineering & Operations, to other internal engineering teams, to our field teams that are working with our large customers day in and day out.

The focus of *Azure in the Enterprise* is to serve the ***practictioners*** working on Azure day in and out, but *not* feature release information. That stuff is already greatly covered by shows such as [Azure Friday](https://azure.microsoft.com/resources/videos/azure-friday/). *Azure in the Enterprise* is meant to focus on how to put the platform itself together to solve customer challenges.

What we're working on is below. Just a note - in general, we may put placeholders on content we're working on, and then adding the live links in when they're released, so don't freak out if a link isn't active yet - it means we're working on it now.

After our content listing - head down to the tools and links section for stuff you should be using TODAY, and other content from Microsoft.

## YouTube Episode Listing

- 2017.11.09 - [Enabling Azure SQL Database Auto-Tuning at Scale for Microsoft IT](https://www.youtube.com/watch?v=hmYL5wyJnfA)

## Other Content for enterprises on their Azure journey

- [Microsoft IT Showcase](https://www.microsoft.com/itshowcase) - TONS of content on Microsoft's own digital transformation
- [Azure Architecture Center](https://docs.microsoft.com/azure/architecture/) - includes cloud fundamentals, reference architectures, build and deploy architectures, design guides and cloud adoption frameworks
- [Azure Secure DevOps Toolkit](https://github.com/azsk/DevOpsKit) and [Getting Started with the Secure DevOps Kit for Azure on **Azure Friday**](https://channel9.msdn.com/Shows/Azure-Friday/Getting-started-with-the-Secure-DevOps-Kit-for-Azure-AzSK)

## Core Services Engineering & Operations (formerly Microsoft IT)'s High Level Story

What does it look like when Microsoft’s own Core Services Engineering & Operations (CSEO) organization runs the Line of Business applications for the company on the full suite of Microsoft Cloud services including Azure, Microsoft 365 and Azure DevOps?

As of January 2019, here’s what it looks like:

- SaaS (1st or 3rd party) -> PaaS -> IaaS -> On-prem VM strategy
- $9 Million per month on Azure Spend with more on PaaS than IaaS
- 10k+ IaaS VMs which accounts for >90% of our VM footprint
- 100s of Azure Subscriptions
- 100s of Line of Business Applications
- ~5k Full Time Employees (FTEs) and ~9k Vendors all in the same Azure DevOps project
- 1k+ Azure DevOps BUILD Pipelines executed PER DAY
- 1k+ Azure DevOps RELEASE Pipelines executed PER DAY
- 1000s of work items created and completed per day
- 1000s of pull requests and commits per day
- Migration from 12 data centers to 2

## Azure Secure DevOps Kit

You should be using this today! PowerShell add-in to scan your subscription, an enterprise governance view, a visual studio add-in for secure code, and Azure DevOps CI/CD pipelines.

- [Azure Secure DevOps Kit](http://aka.ms/devopskit) - Used across Microsoft's own internal Line of Business Azure Subscriptions, you can use it too. An introduction video is on [Azure Friday](http://aka.ms/devopskit/azurefriday). For the developers, it's as simple as running these lines in PowerShell:
  - Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
  - Install-Module AzSK -Scope CurrentUser
  - Get-AzSKSubscriptionSecurityStatus -SubscriptionId

## Corporate Strategy from our Chief Digital Officer and our Chief Information Security Officer

- [Microsoft Ignite 2018 - Kurt DelBene, Chief Digital Officer at Microsoft - Transforming IT: Key insights about Microsoft's own digital transformation](https://myignite.techcommunity.microsoft.com/sessions/66276)
- [Microsoft Envision 2018 - Kurt DelBene, Chief Digital Officer at Microsoft - Microsoft's business transformation: Lessons learned along the way with 3 leading experts in their field](https://myenvision.microsoft.com/sessions/66030)
- [Microsoft Envision 2018 - Bret Arsenault, Chief Information Security Officer at Microsoft - Cybersecurity strategy at Microsoft](https://myenvision.microsoft.com/sessions/66107)
- [Microsoft Envision 2018 - Bret Arsenault, Chief Information Security Officer at Microsoft - Cybersecurity: Bring it to the boardroom](https://myenvision.microsoft.com/sessions/67163)

## Other selected videos from Channel 9 with our CSE&O Engineers

- [Enterprise Cloud at Microsoft - October 2018](https://www.youtube.com/watch?v=eacCccm-vg4) - A walk through of the Microsoft Executive Briefing Center's Enterprise Cloud at Microsoft slide deck and their journey over the last 5 years.
- [Operations at big scale: Inside the Microsoft enterprise](https://channel9.msdn.com/events/Build/2018/THR3602)- [Pete Apple](https://twitter.com/petebobapple) speaking at Microsoft's //BUILD 2018 conference around the migration from on-premise to Azure.
- [Building secure cloud apps – lessons learned from Microsoft’s internal security and software engineering teams](https://channel9.msdn.com/Events/Build/2018/BRK4001) - Robert Venable speaking at Microsoft's //BUILD 2018 conference.

## Contact Information

Please feel free to reach out with questions or a suggestion for content you'd like to see. Just reach out on [twitter](https://twitter.com/lyledodge) or [email](mailto:lyle.dodge@microsoft.com).

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution. For details, visit [https://cla.microsoft.com](https://cla.microsoft.com).

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide a CLA and decorate the PR appropriately (e.g., label, comment). Simply follow the instructions provided by the bot. You will only need to do this once across all repositories using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/). For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

## Legal Notices

Microsoft and any contributors grant you a license to the Microsoft documentation and other content in this repository under the [Creative Commons Attribution 4.0 International Public License](https://creativecommons.org/licenses/by/4.0/legalcode),
see the [LICENSE](LICENSE) file, and grant you a license to any code in the repository under the [MIT License](https://opensource.org/licenses/MIT), see the
[LICENSE-CODE](LICENSE-CODE) file.

Microsoft, Windows, Microsoft Azure and/or other Microsoft products and services referenced in the documentation
may be either trademarks or registered trademarks of Microsoft in the United States and/or other countries.
The licenses for this project do not grant you rights to use any Microsoft names, logos, or trademarks.
Microsoft's general trademark guidelines can be found at [http://go.microsoft.com/fwlink/?LinkID=254653](http://go.microsoft.com/fwlink/?LinkID=254653).

Privacy information can be found at [https://privacy.microsoft.com/en-us/](https://privacy.microsoft.com/en-us/).

Microsoft and any contributors reserve all other rights, whether under their respective copyrights, patents,
or trademarks, whether by implication, estoppel or otherwise.
