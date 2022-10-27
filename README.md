# Vault Standards Proposals (VSPs)


A Vault Standards Proposal (VSP) describes standards for the Vault ecosystem. The Vault Standards Proposal GitHub is a community-based initiative.  
PSP process is not supposed to be a substitute for Vault Governance process and is meant to focus only on commonly agreed usage patterns rather than protocol adjustments.  

> __Disclaimer__: The Vault network is young and many ecosystem
projects are just getting started. As of now, we loosely accept proposals that we might
not actively endorse, do not expect to be implemented or might fall outside the
scope of the PSP. We think many standards will be adopted organically (with some
coordination) and change with time. We expect that a more firm process for
standardization will evolve as adoption takes place. Certain proposals might be
modified, replaced or deprecated. Many initial VSP's will mirror Polkadot Standards Proposal(s) to ensure interoperability between Vault Network <-> Polkadot <-> and Other Substrate-based chains.

---

- [Vault Standards Proposals (VSPs)](#vault-standards-proposals-vsps)
  - [:clipboard: Process](#clipboard-process)
  - [:pencil: Contributing](#pencil-contributing)

## :clipboard: Process  

Below is the workflow of a successful VSP:
```
1. Draft -> 2. Call for Feedback -> 3. Published -> 4. Integrated
```
1. **Draft:** A valid draft, which is merged into into the [draft
   subfolder](./VSPs/drafts) and actively improved together with the community.
2. **Call for Feedback:** The VSP will be shared on different channels for
   additional feedback for at least 2 weeks. The result of this step is either
   an acceptance of the standard (->Published) or the rejection (->Draft).
3. **Published:** Any further changes are unlikely, and developers can start
   integrating the VSP.
4. **Integrated:** The VSP is actively used and a reference implementation
   exists.

In order to be **merged or accepted** for the different stages, reviewers need to approve a PR. Reviewers should be known experts in the topic covered by the VSP. 

## :pencil: Contributing

A VSP should provide the motivation as well as a technical specification for the feature. 

1. Fork this repository.
2. In the newly created fork, create a copy of the template.
3. Fill out the [template](./PSPs/psp-template.md) with the details of your PSP. If your PSP requires images, the images should be integrated in a subdirectory of the src folder, which has your PSP number as the name.
4. Once you have completed the application, click on "create new pull request".
5. Rename the file with "psp-number_of_your_pr.md".
6. Update the pull request. 
