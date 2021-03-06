# MSI30: Migrating IaaS Workloads to Azure

[![Learning Path](https://img.shields.io/badge/Learning%20Path-MSI-fe5e00?logo=microsoft)](https://github.com/microsoft/ignite-learning-paths-training-msi)

## Session Abstract

Now that the migration of their server hosts from Windows Server 2008 R2 to Windows Server 2019 is complete, Tailwind Traders wants to begin the process of “lift and shift”: migrating some of their on-premises VMs they’ve been running in their datacenter.  

In this session, learn about how Tailwind Traders began the process of migrating some of their existing VM workloads to Azure and how this allowed them to retire aging server hardware and close datacenter and server rooms that were costing the organization a substantial amount of money.


## Table of Contents

| Resources         | Links                            |
|-------------------|----------------------------------|
| PowerPoint        | - [Presentation](presentations.md) |
| Videos            | - [Dry Run Rehearsal](https://globaleventcdn.blob.core.windows.net/assets/msi/msi30/MSI30%20Migrating%20IaaS%20Workloads%20to%20Azure.mp4) <br/>- [Microsoft Ignite Orlando Recording](https://myignite.techcommunity.microsoft.com/sessions/82978?source=global-search) <br/>- [Director's Cut of Presentation](https://globaleventcdn.blob.core.windows.net/assets/msi/msi30/MSI30-Directors-cut.mp4) |
| Demos             | - [Demo 1 - Extend AD Environment](https://globaleventcdn.blob.core.windows.net/assets/msi/msi30/MSI30-Demo-AD-extend.mp4)  <br/>- [Demo 2 - Workload Migration](https://globaleventcdn.blob.core.windows.net/assets/msi/msi30/MSI30-Demo-AzMig.mp4) |


## Session Story

In this session, you'll be playing the role of the Tailwind Traders senior system administrator. You'll be walking the audience through the steps that TWT took to migrate workloads from on-premises to the cloud.  You'll discuss the steps needed to plan and execute the migration.

* We start by identifying the workloads and all the parts needed for the migration of a workload. We cover this to ensure that nothing gets missed or broken as part of the migration.

    * Workloads and owners,  Systems maps, and dependencies.
    * Networking dependencies,  Address space, subnets...
    * Storage inventory and clean-up
    * Identity Management model

* We continue with the identity posture.  It's critical to use the right flavour of AD for the migration.
** quickly go through the differences between Active Directory (AD), Azure Active Directory (AAD), and Azure AD domain services (AADDS).
** Demo our AD extensions to the cloud.  We choose AD in Azure because of the multi-geographie nature or our deployments, and because our VMs use GPO and Service Accounts to run, and we have Domain trusts in our environment.

* Storage migration:  for the storage migration, we discuss the challenges with moving large amounts of data. We talk about the availability of Databox service, but we don't demo it since it would take too long for a 45 minutes session.

* Database migration: This session is about migrating VM based workloads we will not discuss the migration to a managed service, but we do point to the MOD20: Moving your Database​ to Azure session that concentrates on that topic

* Finally, the last section of the sessions we walk through the Azure Migrate service to move one of our applications from On-Prem to Azure.


## How To Use

Welcome, Presenter!

We're glad you are here and look forward to your delivery of this amazing content. As an experienced presenter, we know you know HOW to present so this guide will focus on WHAT you need to present. It will provide you a full run-through of the presentation created by the presentation design team.

Along with the video of the presentation, this document will link to all the assets you need to successfully present including PowerPoint slides and demo instructions &
code.

1.  Read document in its entirety.
2.  <a href="https://globaleventcdn.blob.core.windows.net/assets/msi/msi30/MSI30 Migrating IaaS Workloads to Azure.mp4" target="_blank">Watch the video presentation</a>
3.  Ask questions of the Lead Presenter


## Assets in Train-The-Trainer kit

- PowerPoint presentation including notes for each slide [<a href="https://globaleventcdn.blob.core.windows.net/assets/msi/msi30/msi30-2019-10_Oct-24.pptx" target="_blank">here</a>]


Demos:
-   Extend AD environment - Video can be found <a href="https://globaleventcdn.blob.core.windows.net/assets/msi/msi30/MSI30-Demo-AD-extend.mp4" target="_blank">here</a>
-   Workload Migration - Video can be found <a href="https://globaleventcdn.blob.core.windows.net/assets/msi/msi30/MSI30-Demo-AzMig.mp4" target="_blank">here</a>

Recording or the session in different formats
- Full-length recording of presentation [<a href="https://globaleventcdn.blob.core.windows.net/assets/msi/msi30/MSI30 Migrating IaaS Workloads to Azure.mp4" target="_blank">here</a>]
- Director Cut Full-length recording of presentation [<a href="https://globaleventcdn.blob.core.windows.net/assets/msi/msi30/MSI30-Directors-cut.mp4" target="_blank">here</a>]
- Recording of the Ignite Orlando delivery can be found <a href="https://myignite.techcommunity.microsoft.com/sessions/82978?source=global-search" target="_blank">here</a>.

## Become a Trained Presenter

You don't need anything to present this content, it's all there to be used. However, by becoming a *Trained Presenter* the scalable content team will recognize you as well. *Trained Presenter* see their contact information (name, picture, website) in the bottom of each session.  
 
To become a *Trained Presenter*, contact [scalablecontent@microsoft.com](mailto:scalablecontent@microsoft.com). In your email please include:

- Complete name:
- The code of this presentation: \<Session Code (ex:AFUN10)\>
- Link to an unlisted YouTube video of you presenting around 10 minutes of the content for this specific session.


## Trained Presenters

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->

<table>
<tr>
    <td align="center"><a href="http://orinthomas.com">
        <img src="https://avatars1.githubusercontent.com/u/44561273?s=460&v=4" width="100px;" alt="Orin-Thomas"/><br />
        <sub><b>Orin-Thomas</b></sub></a><br />
            <a href="https://github.com/microsoft/ignite-learning-paths-training-afun/commits?author=Orin-Thomas" title="talk">📢</a>
            <a href="https://github.com/microsoft/ignite-learning-paths-training-afun/commits?author=Orin-Thomas" title="Documentation">📖</a> 
    </td>
</tr></table>

<!-- ALL-CONTRIBUTORS-LIST:END -->
