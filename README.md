# Ethereum Genesys Improvement Proposals (EIPs)
# Based on EIP from Ethereum

Ethereum Genesys Improvement Proposals (EGIPs) describe standards for the Ethereum Genesys platform, including core protocol specifications, client APIs, and contract standards.

This repository tracks the ongoing status of EIPs. It contains:

- [Draft](https://eips.ethereumgenesys.org/all#draft) proposals which intend to complete the EIP review process.
- [Last Call](https://eips.ethereumgenesys.org/all#last-call) for proposals that may become final (see also [RSS feed](https://eips.ethereumgenesys.org/last-call.xml)).
- [Accepted](https://eips.ethereumgenesys.org/all#accepted) proposals which are awaiting implementation or deployment by Ethereum client developers.
- [Final](https://eips.ethereumgenesys.org/all#final) and [Active](https://eips.ethereumgenesys.org/all#active) proposals that are recorded.
- The [EGIP process](./EGIPS/egip-0001.md) that governs the EGIP repository.

Achieving "Final" status in this repository only represents that a proposal has been reviewed for technical accuracy. It is solely the responsibility of the reader to decide whether a proposal will be useful to them.

Browse all current and draft EGIPs on [the official EGIP site](https://eips.ethereumgenesys.org/).

Once your first PR is merged, we have a bot that helps out by automatically merging PRs to draft EGIPs. For this to work, it has to be able to tell that you own the draft being edited. Make sure that the 'author' line of your EGIP contains either your GitHub username or your email address inside <triangular brackets>. If you use your email address, that address must be the one publicly shown on [your GitHub profile](https://github.com/settings/profile).

## Project Goal

The Ethereum Genesys Improvement Proposals repository exists as a place to share concrete proposals with potential users of the proposal and the Ethereum Genesys community at large.

## Preferred Citation Format

The canonical URL for a EGIP that has achieved draft status at any point is at https://eips.ethereumgenesys.org/. For example, the canonical URL for EIP-1 is https://eips.ethereumgenesys.org/EIPS/eip-0001.

Please consider anything which is not published on https://eips.ethereumgenesys.org/ as a working paper.

And please consider anything published at https://eips.ethereumgenesys.org/ with a status of "draft" as an incomplete draft.

# Validation
TBD

# Automerger
TBD
(https://github.com/eip-automerger/automerger) bot.

# Local development

## Prerequisites

1. Open Terminal.

2. Check whether you have Ruby 2.1.0 or higher installed:

```sh
$ ruby --version
```

3. If you don't have Ruby installed, install Ruby 2.1.0 or higher.

4. Install Bundler:

```sh
$ gem install bundler
```

5. Install dependencies:

```sh
$ bundle install
```

## Build your local Jekyll site

1. Bundle assets and start the server:

```sh
$ bundle exec jekyll serve
```

2. Preview your local Jekyll site in your web browser at `http://localhost:4000`.

More information on Jekyll and GitHub pages [here](https://help.github.com/en/enterprise/2.14/user/articles/setting-up-your-github-pages-site-locally-with-jekyll).
