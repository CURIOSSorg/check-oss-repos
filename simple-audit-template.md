# Repository Review Checklist

This template is meant to be useful for helping contributors and maintainers for understanding how to judge the health of a repository. Some of these tasks may be more focused on maintainers improving their repository, but some of these are also useful for understanding repository health from the contributor perspective.

None of these are mandatory; this is meant to be a guide.

### Reviewing the Repository Docs

- [ ] Is there a README?
- [ ] Is there a Code of Conduct, such as the [Contributor Covenant](https://www.contributor-covenant.org/)?
  - [ ] Is it mentioned in the Contribute section of the README? (Note: this isn't needed if you mention it in your `CONTRIBUTING.md` and it is in this repository.)
  - [ ] Does it explain how reports are handled and how it is enforced?
  - [ ] Does more than one person receive reports?
- [ ] Is there a `LICENSE` file?
- [ ] Is there a `.github` folder, or an organization-wide `.github` repository that provides default community files?
  - [ ] Are there [issue forms](https://docs.github.com/en/communities/using-templates-to-encourage-useful-issues-and-pull-requests/syntax-for-issue-forms) in `.github/ISSUE_TEMPLATE/` ([example](https://github.com/babel/babel/issues/new/choose))?
- [ ] Is there a `CONTRIBUTING.md` file?
  - [ ] Does it mention how to make a PR?
  - [ ] Does it mention what sort of issues you'd like?
  - [ ] Does it mention the `good first issue` and `help wanted` labels as starting points?
  - [ ] Does it point to a place for community conversation, like GitHub Discussions, Discord, or Matrix?
  - [ ] Does it encourage conversations in issues before opening huge PRs?
  - [ ] Does it specify where to ask questions on process?
- [ ] Does it state a policy on AI-assisted contributions?
- [ ] _(Research software)_ Is there a `CITATION.cff` file?

### Process
- [ ] Can I install easily?
- [ ] Can I use this easily?

### Issues and Pull Requests
- [ ] How many open issues are there?
- [ ] How many PRs have been open with no activity for more than 30 days?
- [ ] Are the labels being used? What share of open issues are labeled?

### Security
- [ ] Is there a `SECURITY.md`?

### CI and Releases
- [ ] Do tests run automatically on every PR?
- [ ] Are the tests passing on the default branch?
- [ ] Are releases tagged and versioned with [semver](https://semver.org/)?

### Governance and Sustainability
- [ ] Is it clear who the maintainers are, through a `CODEOWNERS` file or a maintainers section?
- [ ] Is there a `GOVERNANCE.md`, or a section explaining how decisions are made?
- [ ] Is there a `.github/FUNDING.yml`, if the project accepts funding?


### Metadata
- [ ] Is there a description on GitHub?
- [ ] Are the topics useful?
- [ ] Is there a website?

### Package Metadata


- [ ] Is there a package published somewhere other than GitHub for this code, like in npm, Cargo, or other registries?

### TODO

- [ ] Anything else you would note?


## Contribute back?

This checklist is open source! If you have suggestions or think it could be better, contribute back on https://github.com/CURIOSSOrg/check-oss-repos/!

Thank you!
