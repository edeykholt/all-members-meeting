# [DRAFT] RBIs 
Rchain Ballot Items (RBIs) are proposals for the RChain membership to vote on.

Proposals should be clear, specific, and actionable.

# Contributing

 1. Review [RBI-1](RBIS/rbi-1.md).
 2. Fork the repository by clicking "Fork" in the top right.
 3. Add your RBI to your fork of the repository. There is a [template RBI here](RBI-X.md).
 4. Submit a Pull Request to RChains's [RBPs repository](https://github.com/rchain/all-members-meetings/RBIS).

Your first PR (pull request) should be a first draft of the final RBI. It must meet the formatting criteria enforced by the build (largely, correct metadata in the header). An editor will manually review the first PR for a new RBI and assign it a number before merging it. Make sure you include a `discussions-to` header with the URL to a discussion forum or open GitHub issue where people can discuss the RBI as a whole.

If your RBI requires images, the image files should be included in a subdirectory of the `assets` folder for that RBI as follow: `assets/RBI-X` (for RBI **X**). When linking to an image in the RBI, use relative links such as `../assets/RBI-X/image.png`.

Once your first PR is merged, we have a bot that helps out by automatically merging PRs to draft RBIs. For this to work, it has to be able to tell that you own the draft being edited. Make sure that the 'author' line of your RBI contains either your Github username or your email address inside <triangular brackets>. If you use your email address, that address must be the one publicly shown on [your GitHub profile](https://github.com/settings/profile).

When you believe your RBI is mature and ready to progress past the draft phase, you should do one of two things:

 - **For all other RBIs**, open a PR changing the state of your RBI to 'Final'. An editor will review your draft and ask if anyone objects to its being finalised. If the editor decides there is no rough consensus - for instance, because contributors point out significant issues with the RBI - they may close the PR and request that you fix the issues in the draft before trying again.

# RBI status terms
* **Draft** - an RBI that is open for consideration
* **Accepted** - an RBI that is planned for immediate adoption, i.e. expected to be included in the next hard fork (for Core/Consensus layer RBIs).
* **Final** - an RBI that has been adopted in a previous hard fork (for Core/Consensus layer RBIs).
* **Deferred** - an RBI that is not being considered for immediate adoption. May be reconsidered in the future for a subsequent hard fork.
