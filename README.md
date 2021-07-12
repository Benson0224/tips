# TIPs

TRON Improvement Proposals (TIPs) describe standards for the TRON platform, including core protocol specifications, client APIs, and contract standards.

****

## Contents
 * [TIPs](#tips)
    * [TIPs Index](#tips-index)
    * [To Submit a TIP](#to-submit-a-tip)
    * [TIP Status](#tip-status)
    * [TIP Types](#tip-types)
* [Proposals](./proposals/README.md)

## TIPs Index  

Please Check TIPs index at: [TIPs Index](./tips/README.md)

****

## To Submit a TIP

Before you submit a TIP, you need to create an issue for comment and add the issue URL to your TIP header.   

1.&nbsp;Fork the repository by clicking "Fork" in the top right.  

2.&nbsp;Add your TIP to your fork of the repository. There is a [TIP template](https://github.com/tronprotocol/TIPs/blob/master/template.md) here.  

3.&nbsp;Submit a Pull Request to TRON's TIPs repository.

Your first PR should be a first draft of the final TIP. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new TIP and assign it a number before merging it. 

Make sure you include a discussions-to header with the URL to a discussion forum or open GitHub issue where people can discuss the TIP as a whole. If a TIP is about the feature development of java-tron, and a PR of the development exists, in your TIP and your java-tron's PR you need to refer each other's github link.

When you believe your TIP is mature and ready to progress past the draft phase, you should do one of two things:

- For a Standards Track TIP of type Core, ask to have your issue added to the agenda of an upcoming All Core Devs meeting, where it can be discussed for inclusion in a future hard fork. If implementers agree to include it, the TIP editors will update the state of your TIP to 'Accepted'. 

- For all other TIPs, open a PR changing the state of your TIP to 'Final'. An editor will review your draft and ask if anyone objects to its being finalized. If the editor decides there is no rough consensus, they may close the PR and request you fix the issues in the draft before trying again.

****

## TIP Status

TIPs are separated into several statuses.

- **Draft**: A TIP that is undergoing rapid iteration and changes.  

- **Last Call**: A TIP that is done with its initial iteration and ready for review by a wide audience.  

- **Accepted**: A core TIP that has been in the Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author. The process for Core Devs to decide whether to encode a TIP into their clients as part of a hard fork is not part of the TIP process. If such a decision is made, the TIP will move to the final.  

- **Final (non-Core)**: A TIP that has been in the Last Call for at least 2 weeks and any technical changes that were requested have been addressed by the author.  

- **Final (Core)**: A TIP that the Core Devs have decided to implement and release in a future version or has already been released.

- **Active**: If the TIPs are never meant to be completed, the TIPs may have a status of “Active”. 

- **Abandoned**: If a TIP is no longer pursued by the original authors or it may not be a (technically) preferred option anymore.

- **Rejected**: A TIP that is fundamentally broken or a Core TIP that was rejected by the Core Devs and will not be implemented. 

- **Superseded**: A TIP which was previously Final but is no longer considered state-of-the-art. Another TIP will be in the Final status and cite the Superseded TIP.

- **Deferred**: A TIP which isn't accepted now, it may be accepted in the future. 

****

## TIP Types

TIPs are separated into several types, and each has its list of TIPs.

* **Standard Track**: Describes any change that affects most or all TRON implementations, such as a change in block or transaction validity rules, proposed application standards/conventions, or any change or addition that affects the interoperability of applications using TRON. Furthermore, Standard TIPs can be broken down into the following categories. 

   **1.Core**: Improvements requiring a consensus fork, as well as changes that are not necessarily consensus critical but may be relevant to "core dev" discussions.    

  **2.Networking**: Includes improvements around network protocol.      

  **3.Interface**: Includes improvements around client API/RPC specifications and standards.    

  **4.TRC**: Application-level standards and conventions, including contract standards such as token standards (TRC-20).    

  **5.VM**: Includes improvements around TRON Virtual Machine.    

* **Informational**: Describes a TRON design issue, or provides general guidelines or information to the TRON community, but does not propose a new feature.

***
# Proposals 

Proposal is designed to modify the dynamic parameters such as block rewards and transaction fees on the TRON network by TRON committee.

Please check all proposal histories from [Proposal Details](../tips/proposals/README.md)


For further discussion, please enter [Telegram](https://t.me/troncoredevscommunity)  
