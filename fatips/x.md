| FATIP | Title                                                        | Status | Category | Author                             | Created   |
| ----- | ------------------------------------------------------------ | ------ | -------- | ---------------------------------- | --------- |
| X     | Standard, Contributions, and Process Guidelines for the FAT Ecosystem | Final  | Meta     | Devon Katz \<<devonk@dbgrow.com>\> | 7-23-2018 |



# FATIP-X

[FATIP-X](/) is the initial standard that describes the core framework,
conventions, contribution guidelines, and ecosystem of FATIP standards.


# What Is An FATIP?

FATIP is a formal proposal and process for accepting and integrating new
standards into the FAT standard collection.


# Why Are They Important?

FATIP provides an open forum for the community to collaborate on and accept new
standards into the FAT ecosystem. FAT is completely open source, and we rely
on our community to keep us pointed in the right direction.


# Contributing

Create your submission in a markdown file following the guidelines defined in
[FATIP-X](x.md) and the [FATIP
Template](https://docs.google.com/document/d/1YqLhAWEvhWUf4osLYKcN_1sjIYNxAJ4VtHBZlxwYAq8/edit?usp=sharing)

To submit your standard, fork this repo and then submit a pull request to have
it reviewed and included for evaluation by the community.


# Proposal Categories


## Core

Standards that define the basic building blocks, technology, and conventions
that govern FATIP standards


## Token Standard

Standards that define application level token functionality


## Interface

Standards that define API architecture, conventions, and specs


## Information

Informal standards and informational resources about FATIP


## Meta

Standards about FATIP standards, processes, etc.


# Proposal Statuses


## Work In Progress (WIP)

The standard's information is sufficient to be reviewed by the community. This
is essentially an "Intent to submit" a FATIP standard. The community member(s)
submit a formatted pull request containing the preliminary version of the
proposed standard.

- If reviewed and denied, the proposal may be revised and improved unless it is
  explicitly rejected
- If reviewed and approved it is assigned a FATIP number and other metadata.
  The proposal moves on to drafting.


## Draft

The standard is in the progress of being revised. Follow up pull requests will
be accepted to revise the standard until it is ready to go through the last
call process


## Last Call

The token standard is open to final evaluation by the community and general
public.

- If the standard requires further changes, it reverts to drafting again.
- If the proposal is approved and it is a Core, FAT, or Interface FATIP
  standard then it will move onto accepted.
- If the proposal is approved and it is an information standard then it will
  move onto final.


## Accepted

The go ahead for development is given and the standard is finalized.
Implementation in clients and APIs can occur. When the community reaches
consensus on the implementation's success, the status will change to final.


## Final

The proposal has been finalized and accepted by the community. The proposal is
adorned with the final official prefix **FAT**, replacing the former **FATIP**
prefix. Errata may be formally submitted following this stage if required.


# Proposal Workflow

![](/home/devon/Desktop/Screenshot%20from%202018-08-15%2000-20-11.png)


# FATIP Editors

For each new FATIP that comes in, an editor does the following:

- Read the FATIP to check if it is ready: sound and complete. The ideas must
  make technical sense, even if they don't seem likely to get to final status.
- The title should accurately describe the content.
- Check the FATIP for language (spelling, grammar, sentence structure, etc.),
  markup (Github flavored Markdown), code style

If the FATIP isn't ready, the editor will send it back to the author for
revision, with specific instructions.

Once the FATIP is ready for the repository, the FATIP editor will:

- Assign an FATIP number (generally the PR number or, if preferred by the
  author, the Issue # if there was discussion in the Issues section of this
repository about this FATIP)
- Merge the corresponding pull request
- Send a message back to the FATIP author with the next step.

Many FATIP are written and maintained by developers with write access to the codebases
of FAT implementations. The FATIP editors monitor FATIP changes, and correct any
structure, grammar, spelling, or markup mistakes they see.




# Proposal Structure

A [FATIP Template](template) is supplied to begin writing your standard.


## Header

An informational header containing metadata about the FATIP being submitted,
like so:

| FATIP | Title         | Status | Category | Author                               | Created   |
| ----- | ------------- | ------ | -------- | ------------------------------------ | --------- |
| N     | Standard Name | Status | Category | Author Name \<<author@example.com>\> | 7-23-2018 |

Once accepted as a draft an editor will assign an official FATIP number.


## Summary

"If you can't explain it simply, you don't understand it well enough." Provide
a simplified and layman-accessible explanation of the FATIP.


## Motivation

Clearly explain why the existing protocol specification is inadequate to
address the problem that the FATIP solves. FATIP submissions without sufficient
motivation may be rejected outright. What motivated the design and why were
particular design decisions made?


## Specification

The technical specification should describe the syntax and semantics of any new
feature. The specification should be detailed enough to allow competing,
interoperable implementations for any of the current FAT platforms
([fat-js](https://github.com/DBGrow/fat-js), any future implementations).


## Implementation

The implementations must be completed before any FATIP is given status "Final",
but it need not be completed before the FATIP is given status "Accepted". While there is merit
to the approach of reaching consensus on the specification and rationale before
writing code, the principle of "rough consensus and running code" is still
useful when it comes to resolving many discussions of standard details.


## Copyright

The standard must have a copyright section that waives rights according to CC0:

```
Copyright and related rights waived via
[CC0](https://creativecommons.org/publicdomain/zero/1.0/).
```


# Inheritance

FAT standards can extend and inherit functionality and rules from others. The
`extends` \<FATIP #> Keyword and Tag denotes feature inheritance on a feature
by feature basis. The author of the FATIP must explain how and what is being
inherited, and if there are any changes being made.


# Copyright

Copyright and related rights waived via
[CC0](https://creativecommons.org/publicdomain/zero/1.0/).
