---
egip: <to be assigned>
title: <egip title>
author: <a list of the author's or authors' name(s) and/or username(s), or name(s) and email(s), e.g. (use with the parentheses or triangular brackets): FirstName LastName (@GitHubUsername), FirstName LastName <foo@bar.com>, FirstName (@GitHubUsername) and GitHubUsername (@GitHubUsername)>
discussions-to: <URL>
status: Draft
type: <Standards Track, Meta, or Informational>
category (*only required for Standards Track): <Core, Networking, Interface, or ERC>
created: <date created on, in ISO 8601 (yyyy-mm-dd) format>
requires (*optional): <egip number(s)>
replaces (*optional): <egip number(s)>
---

This is the suggested template for new egips.

Note that an egip number will be assigned by an editor. When opening a pull request to submit your egip, please use an abbreviated title in the filename, `egip-draft_title_abbrev.md`.

The title should be 44 characters or less.

## Simple Summary
If you can't explain it simply, you don't understand it well enough." Provide a simplified and layman-accessible explanation of the egip. Imagine an email subject line, GitHub PR title, or forum post title.

## Abstract
A short (~200 word) description of the technical issue being addressed. This should be a very terse and human-readable version of the specification section. Someone should be able to read only the abstract to get the gist of what this specification does.

## Motivation
The motivation section should describe the "why" of this egip. What problem does it solve? Why should someone want to implement this standard? What benefit does it provide to the Ethereum Genesys ecosystem? What use cases does this egip address?

## Specification
The technical specification should describe the syntax and semantics of any new feature. The specification should be detailed enough to allow competing, interoperable implementations for any of the current Ethereum Genesyts platforms (go-ethereum, open-ethereumj and [others](https://github.com/ethereum/wiki/wiki/Clients)).

## Rationale
The rationale fleshes out the specification by describing what motivated the design and why particular design decisions were made. It should describe alternate designs that were considered and related work, e.g. how the feature is supported in other languages.

## Backwards Compatibility
All egips that introduce backwards incompatibilities must include a section describing these incompatibilities and their severity. The egip must explain how the author proposes to deal with these incompatibilities. egip submissions without a sufficient backwards compatibility treatise may be rejected outright.

## Test Cases
Test cases for an implementation are mandatory for egips that are affecting consensus changes. Other egips can choose to include links to test cases if applicable.

## Reference Implementation
An optional section that contains a reference/example implementation that people can use to assist in understanding or implementing this specification.  If the implementation is too large to reasonably be included inline, then consider adding it as one or more files in `../assets/egip-####/`.

## Security Considerations
All egips must contain a section that discusses the security implications/considerations relevant to the proposed change. Include information that might be important for security discussions, surfaces risks and can be used throughout the life cycle of the proposal. E.g. include security-relevant design decisions, concerns, important discussions, implementation-specific guidance and pitfalls, an outline of threats and risks and how they are being addressed. egip submissions missing the "Security Considerations" section will be rejected. An egip cannot proceed to status "Final" without a Security Considerations discussion deemed sufficient by the reviewers.

## Copyright
Copyright and related rights waived via [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

